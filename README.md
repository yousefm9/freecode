<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>احصل على الكوينات</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f5f5f5;
            padding: 20px;
            direction: rtl;
        }
        .container {
            max-width: 500px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #333;
        }
        p {
            color: #666;
        }
        button {
            background-color: #007bff;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 18px;
            border-radius: 5px;
            cursor: pointer;
            margin: 10px 0;
        }
        button:hover {
            background-color: #0056b3;
        }
        .code-container {
            display: none;
            margin-top: 10px;
            padding: 10px;
            background: #d4edda;
            border: 1px solid #c3e6cb;
            border-radius: 5px;
            color: #155724;
        }
    </style>
</head>
<body>

    <div class="container">
        <h2>احصل على كود الكوينات 💰</h2>
        <p>اضغط على الزر أدناه للحصول على **10 كوينات** بعد مشاهدة الإعلان.</p>
        <button onclick="showAdAndCode('code1', 'ABC123')">احصل على 10 كوينات</button>
        <div id="code1" class="code-container"></div>

        <hr>

        <p>اضغط على الزر أدناه للحصول على **20 كوينات** بعد مشاهدة الإعلان.</p>
        <button onclick="showAdAndCode('code2', 'DEF456')">احصل على 20 كوينات</button>
        <div id="code2" class="code-container"></div>

        <hr>

        <p>اضغط على الزر أدناه للحصول على **40 كوينات** بعد مشاهدة الإعلان.</p>
        <button onclick="showAdAndCode('code3', 'XYZ789')">احصل على 40 كوينات</button>
        <div id="code3" class="code-container"></div>
    </div>

    <script>
        function showAdAndCode(codeId, codeValue) {
            // فتح إعلان Adsterra في نافذة جديدة
            window.open("https://www.effectiveratecpm.com/ieqm7o9y?key=27ff0a99da2890f0e219be1008948eef", "_blank");

            // تأخير ظهور الكود بعد 5 ثوانٍ
            setTimeout(function() {
                document.getElementById(codeId).innerHTML = "🎉 كودك: <strong>" + codeValue + "</strong>";
                document.getElementById(codeId).style.display = "block";
            }, 5000);
        }
    </script>

</body>
</html>
