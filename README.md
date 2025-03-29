# Landing-page
<!DOCTYPE html><html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>اطلب ساعتك الآن</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; background-color: #f8f8f8; padding: 20px; }
        .container { background: white; padding: 20px; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.1); max-width: 400px; margin: auto; }
        .input-field { width: 100%; padding: 10px; margin: 10px 0; border: 1px solid #ccc; border-radius: 5px; }
        .submit-btn { background-color: #007bff; color: white; padding: 10px; border: none; border-radius: 5px; cursor: pointer; }
        .submit-btn:hover { background-color: #0056b3; }
    </style>
</head>
<body>
    <div class="container">
        <h2>📢 اطلب ساعتك الفاخرة الآن!</h2>
        <p>املأ المعلومات أدناه وسنتواصل معك لتأكيد الطلب:</p>
        <form action="https://formspree.io/YOUR_EMAIL" method="POST">
            <input type="text" name="name" class="input-field" placeholder="الاسم الكامل" required>
            <input type="tel" name="phone" class="input-field" placeholder="رقم الهاتف" required>
            <input type="text" name="address" class="input-field" placeholder="العنوان الكامل" required>
            <select name="color" class="input-field">
                <option value="أسود">أسود</option>
                <option value="ذهبي">ذهبي</option>
                <option value="فضي">فضي</option>
            </select>
            <button type="submit" class="submit-btn">✅ اطلب الآن</button>
        </form>
    </div>
</body>
</html>
