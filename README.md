<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>環島物品清單</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
        main {
            padding: 20px;
        }
        h1 {
            font-size: 24px;
            margin-bottom: 10px;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        li {
            background: white;
            margin: 5px 0;
            padding: 10px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            display: flex;
            align-items: center;
        }
        input[type="checkbox"] {
            margin-right: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>環島物品清單</h1>
    </header>
    <main>
        <h2>必備物品</h2>
        <ul>
            <li><input type="checkbox">護照 / 身份證</li>
            <li><input type="checkbox">原住民的內褲</li>
            <li><input type="checkbox">檜木採伐身證</li>
            <li><input type="checkbox">黑豬肉香腸</li>
            <li><input type="checkbox">老二</li>
            <li><input type="checkbox">我想去湖口，我們在新竹住一晚吧</li>
        </ul>
        <h2>選擇性物品</h2>
        <ul>
            <li><input type="checkbox">范怡婷</li>
            <li><input type="checkbox">張芷情</li>
            <li><input type="checkbox">陳綵於</li>
        </ul>
    </main>
</body>
</html>
