<!DOCTYPE html>
<html lang="he">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>בונה מערכות אוטומטיות - MAD</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #1a1a1a;
            color: #ffffff;
        }
        header {
            background: #35424a;
            padding: 10px 0;
            text-align: center;
        }
        header img {
            width: 150px;
            margin-bottom: 10px;
        }
        nav {
            margin: 15px 0;
        }
        nav a {
            color: #e8491d;
            padding: 10px 15px;
            text-decoration: none;
            border-radius: 5px;
            transition: background 0.3s;
        }
        nav a:hover {
            background: #e8491d;
            color: #ffffff;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        footer {
            background: #35424a;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .content {
            padding: 20px;
            background: #262626;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
            margin-bottom: 20px;
        }
        h2 {
            color: #e8491d;
        }
        .testimonials {
            background: #333;
            padding: 15px;
            border-radius: 8px;
            margin-bottom: 20px;
        }
        .testimonials p {
            margin: 5px 0;
            font-style: italic;
        }
        .form-group {
            margin-bottom: 15px;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background-color: #e8491d;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #d7381b;
        }
    </style>
</head>
<body>

<header>
    <img src="לינק-ללוגו-שלך" alt="לוגו MAD">
    <h1>ברוכים הבאים לבונה מערכות אוטומטיות - MAD</h1>
    <nav>
        <a href="#about">אודות</a>
        <a href="#services">שירותים</a>
        <a href="#testimonials">מרוצים</a>
        <a href="#contact">צור קשר</a>
    </nav>
</header>

<div class="container">
    <div class="content" id="about">
        <h2>אודות</h2>
        <p>אנו מתמחים בבניית מערכות אוטומטיות עם טכנולוגיות AVR ו-CUBV...</p>
    </div>
    
    <div class="content" id="services">
        <h2>שירותים</h2>
        <ul>
            <li>תכנון וייעוץ למערכות אוטומטיות</li>
            <li>פיתוח תוכנה למערכות AVR</li>
            <li>קורסים והדרכות בתחומי האוטומציה</li>
        </ul>
    </div>
    
    <div class="content" id="testimonials">
        <h2>מרוצים מהשירות שלנו</h2>
        <div class="testimonials">
            <p>"שירות מעולה, אני ממליץ עליהם בחום!" - יוסי</p>
            <p>"המערכת פשוט מושלמת! תודה רבה!" - מרים</p>
            <p>"מקצועיות ורצינות, באמת חוויה טובה!" - אורי</p>
        </div>
    </div>
    
    <div class="content" id="contact">
        <h2>צור קשר</h2>
        <form>
            <div class="form-group">
                <label for="name">שם:</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="form-group">
                <label for="email">מייל:</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="message">הודעה:</label>
                <textarea id="message" name="message" rows="4" required></textarea>
            </div>
            <button type="submit">שלח</button>
        </form>
    </div>
</div>

<footer>
    <p>&copy; 2023 בונה מערכות אוטומטיות - MAD</p>
</footer>

</body>
</html>
