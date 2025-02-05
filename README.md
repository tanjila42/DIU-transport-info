<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DIU Transport Management System</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        .header {
            background-color: #004d99;
            color: white;
            padding: 1rem;
            text-align: center;
        }

        .nav {
            background-color: #003366;
            padding: 1rem;
            display: flex;
            justify-content: center;
            gap: 2rem;
        }

        .nav a {
            color: white;
            text-decoration: none;
            padding: 0.5rem 1rem;
            border-radius: 4px;
            transition: background-color 0.3s;
        }

        .nav a:hover {
            background-color: #0066cc;
        }

        .main {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1rem;
        }

        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .feature-card {
            border: 1px solid #ddd;
            padding: 1.5rem;
            border-radius: 8px;
            background-color: #f9f9f9;
        }

        .emergency-contact {
            background-color: #ff6b6b;
            color: white;
            padding: 1rem;
            border-radius: 8px;
            margin-top: 2rem;
            text-align: center;
        }

        .footer {
            background-color: #004d99;
            color: white;
            text-align: center;
            padding: 1rem;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .button {
            display: inline-block;
            padding: 0.5rem 1rem;
            background-color: #0066cc;
            color: white;
            text-decoration: none;
            border-radius: 4px;
            margin-top: 1rem;
        }
    </style>
</head>
<body>
    <header class="header">
        <h1>DIU Transport Management System</h1>
    </header>

    <nav class="nav">
        <a href="#schedule">Bus Schedule</a>
        <a href="#drivers">Driver Info</a>
        <a href="#registration">Registration</a>
        <a href="#contact">Contact</a>
    </nav>

    <main class="main">
        <h2>Welcome to DIU Transport Management</h2>
        <p>Efficient and safe transportation services for students and staff.</p>

        <div class="features">
            <div class="feature-card">
                <h3>Bus Schedule</h3>
                <p>View real-time bus schedules and track bus locations. Plan your journey efficiently with our updated timetable.</p>
                <a href="#" class="button">View Schedule</a>
            </div>

            <div class="feature-card">
                <h3>Driver Information</h3>
                <p>Access contact details and availability status of our bus drivers. Direct communication for queries and assistance.</p>
                <a href="#" class="button">Driver Details</a>
            </div>

            <div class="feature-card">
                <h3>Student Registration</h3>
                <p>Register for transport services with emergency contact information and medical details for enhanced safety.</p>
                <a href="#" class="button">Register Now</a>
            </div>
        </div>

        <div class="emergency-contact">
            <h3>Emergency Contact</h3>
            <p>24/7 Transport Help Desk: +880 1234567890</p>
        </div>
    </main>

    <footer class="footer">
        <p>&copy; 2025 Daffodil International University Transport Management System</p>
    </footer>
</body>
</html>
