<!DOCTYPE html>
<html>
<head>
    <title>Basic HTML Page with CSS Styling</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }

        h1 {
            margin: 0;
            padding: 20px;
        }

        main {
            margin: 20px;
            padding: 10px;
            background-color: white;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        footer {
            text-align: center;
            background-color: #333;
            color: white;
            padding: 10px 0;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        li {
            background-color: #f9f9f9;
            padding: 10px;
            margin-bottom: 5px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to my Basic HTML Page</h1>
    </header>

    <main>
        <ul>
            <li>Item 1</li>
            <li>Item 2</li>
            <li>Item 3</li>
        </ul>
    </main>

    <footer>
        <p>&copy; 2021 My Website. All rights reserved.</p>
    </footer>
</body>
</html>
