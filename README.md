from selenium import webdriver

webdriver_path = "path/to/chromedriver"

driver = webdriver.Chrome(webdriver_path)
driver.get("https://example.com/login")

username_field = driver.find_element_by_id("username")
password_field = driver.find_element_by_id("password")

username_field.send_keys("your_username")
password_field.send_keys("your_password")

login_button = driver.find_element_by_id("login_btn")
login_button.click()

driver.implicitly_wait(10)

driver.quit()
