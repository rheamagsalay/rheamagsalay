<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Resume</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Georgia', serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to right, #f0f8e7, #d4e8c9); /* Light green & beige gradient */
            color: #444;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        /* Resume Container */
        .resume {
            background: #ffffff;
            width: 70%;
            max-width: 800px;
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.2);
        }

        /* Header Styling */
        .header {
            text-align: center;
            padding-bottom: 15px;
            border-bottom: 3px solid #81c784; /* Green line */
        }

        .profile-pic {
            width: 80px; /* Small size */
            height: 80px;
            border-radius: 50%; /* Circular shape */
            object-fit: cover;
            display: block;
            margin: 10px auto; /* Centering */
            border: 2px solid #81c784; /* Green border */
        }

        .header h1 {
            color: #2e7d32;
            font-size: 32px;
            margin-bottom: 5px;
        }

        .header p {
            color: #555;
            font-size: 16px;
        }

        /* Section Styling */
        .section {
            margin: 20px 0;
            padding: 15px;
            background: #f7fff0;
            border-radius: 8px;
            border-left: 5px solid #66bb6a; /* Green side border */
        }

        .section h2 {
            color: #388e3c;
            border-bottom: 2px solid #81c784;
            padding-bottom: 5px;
            margin-bottom: 10px;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        ul li {
            padding: 6px 0;
            font-size: 16px;
        }

        /* Footer */
        .footer {
            text-align: center;
            margin-top: 20px;
            font-size: 14px;
            color: #666;
        }
    </style>
</head>
<body>

    <div class="resume">
        <div class="header">
            <img src="photos.jpg" alt="Profile Picture" class="profile-pic">
            <h1>Rhea M. Magsalay</h1>
            <p>Purok Bombil, Sugod, Tukuran, Zamboanga Del Sur</p>
            <p>📞 09126139925</p>
        </div>

        <div class="section">
            <h2>Career Objective</h2>
            <p>To utilize my knowledge and passion for education, inspiring students and enhancing my teaching skills.</p>
        </div>

        <div class="section">
            <h2>Personal Background</h2>
            <ul>
                <li>🎂 <strong>Birthdate:</strong> June 15, 2006</li>
                <li>📍 <strong>Birthplace:</strong> Sugod, Tukuran, Zamboanga Del Sur</li>
                <li>🏠 <strong>Address:</strong> Sugod, Tukuran, Zamboanga Del Sur</li>
                <li>👨‍👩‍👧 <strong>Parents:</strong> Reynelyn Bello Morontos & Reck Lumingkit Magsalay</li>
                <li>🎂 <strong>Age:</strong> 18</li>
                <li>⚖️ <strong>Weight:</strong> 48kg</li>
            </ul>
        </div>

        <div class="section">
            <h2>Educational Background</h2>
            <ul>
                <li>📖 <strong>Elementary:</strong> Sugod Elementary School</li>
                <li>📘 <strong>Secondary:</strong> Potenciano Solon Bandolon Memorial National High School</li>
                <li>🎓 <strong>Tertiary:</strong> Zamboanga Del Sur Provincial Government College - Tukuran Campus</li>
            </ul>
        </div>

        <div class="section">
            <h2>Skills</h2>
            <ul>
                <li>💻 Computer Literacy</li>
                <li>🛠️ Electrical Wiring</li>
                <li>📸 Photography</li>
                <li>🎨 Graphic Editing</li>
            </ul>
        </div>

        <div class="section">
            <h2>Reference</h2>
            <p><strong>Reychelle Magsalay</strong></p>
            <p>📍 Alindahaw, Tukuran</p>
            <p>📞 09129867408</p>
        </div>

        <div class="footer">
            <p>🌿 Designed with  | Rhea M. Magsalay</p>
        </div>
    </div>

</body>
</html>