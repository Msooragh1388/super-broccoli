html_content = """
<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>صلوات شمار</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-family: Arial, sans-serif;
        }
        #counter {
            font-size: 2em;
        }
        button {
            margin: 10px;
            padding: 10px 20px;
            font-size: 1em;
        }
    </style>
</head>
<body>
    <div>
        <div id="counter">0</div>
        <button onclick="addSalawat()">اضافه کردن صلوات</button>
    </div>

    <script>
        let count = 0;
        function addSalawat() {
            count += 1;
            document.getElementById('counter').innerText = count;
        }
    </script>
</body>
</html>
"""

print(html_content)
html_content = """
<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>صلوات شمار</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-family: Arial, sans-serif;
        }
        #counter {
            font-size: 2em;
        }
        button {
            margin: 10px;
            padding: 10px 20px;
            font-size: 1em;
        }
    </style>
</head>
<body>
    <div>
        <div id="counter">0</div>
        <button onclick="addSalawat()">اضافه کردن صلوات</button>
    </div>

    <script>
        let count = 0;
        function addSalawat() {
            count += 1;
            document.getElementById('counter').innerText = count;
        }
    </script>
</body>
</html>
"""

print(html_content)
