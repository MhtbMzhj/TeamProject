<!DOCTYPE html>
<html>
<head>
    <title>Basic HTML Page with Python Interaction</title>
</head>
<body>
    <header>
        <h1>Welcome to my Basic HTML Page</h1>
    </header>

    <main>
        <form id="calculation_form">
            <input type="number" id="num1" placeholder="Enter the first number">
            <input type="number" id="num2" placeholder="Enter the second number">
            <button type="button" id="calculate_btn">Calculate Product</button>
        </form>

        <p id="product_result"></p>
        <p id="square_result"></p>
    </main>

    <footer>
        <p>&copy; 2021 My Website. All rights reserved.</p>
    </footer>

    <script>
        // Function to calculate the product of two numbers
        function calculateProduct(num1, num2) {
            return num1 * num2;
        }

        // Function to calculate the square of a number
        function calculateSquare(num) {
            return num * num;
        }

        document.getElementById('calculate_btn').addEventListener('click', function() {
            var num1 = parseInt(document.getElementById('num1').value);
            var num2 = parseInt(document.getElementById('num2').value);

            var productResult = calculateProduct(num1, num2);
            document.getElementById('product_result').innerText = "The product of " + num1 + " and " + num2 + " is: " + productResult;

            var num = parseInt(prompt("Enter a number to calculate its square:"));
            var squareResult = calculateSquare(num);
            document.getElementById('square_result').innerText = "The square of " + num + " is: " + squareResult;
        });
    </script>
</body>
</html>
    
