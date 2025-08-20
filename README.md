<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Emirates Wealth Support - Under Maintenance</title>
    <!-- Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&family=Raleway:wght@300;400;500&display=swap" rel="stylesheet">
    <style>
        /* Base Styles & Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body, html {
            height: 100%;
            font-family: 'Raleway', sans-serif;
            overflow: hidden;
        }

        /* Animated Gradient Background */
        body {
            background: linear-gradient(-45deg, #ff9a9e, #fad0c4, #a1c4fd, #c2e9fb);
            background-size: 400% 400%;
            animation: gradientBG 15s ease infinite;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: #333;
        }

        @keyframes gradientBG {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        /* Animated Circles Background */
        .circles {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            overflow: hidden;
            z-index: -1;
        }

        .circles li {
            position: absolute;
            display: block;
            list-style: none;
            width: 20px;
            height: 20px;
            background: rgba(255, 255, 255, 0.4);
            animation: float 25s infinite linear;
            bottom: -150px;
            border-radius: 50%;
        }

        .circles li:nth-child(1) {
            left: 25%;
            width: 80px;
            height: 80px;
            animation-delay: 0s;
            background: rgba(77, 182, 255, 0.2);
        }

        .circles li:nth-child(2) {
            left: 10%;
            width: 20px;
            height: 20px;
            animation-delay: 2s;
            animation-duration: 12s;
            background: rgba(255, 173, 96, 0.3);
        }

        .circles li:nth-child(3) {
            left: 70%;
            width: 20px;
            height: 20px;
            animation-delay: 4s;
            background: rgba(255, 102, 196, 0.2);
        }

        .circles li:nth-child(4) {
            left: 40%;
            width: 60px;
            height: 60px;
            animation-delay: 0s;
            animation-duration: 18s;
            background: rgba(78, 225, 180, 0.3);
        }

        .circles li:nth-child(5) {
            left: 65%;
            width: 20px;
            height: 20px;
            animation-delay: 0s;
            background: rgba(147, 112, 219, 0.2);
        }

        .circles li:nth-child(6) {
            left: 75%;
            width: 110px;
            height: 110px;
            animation-delay: 3s;
            background: rgba(255, 215, 0, 0.2);
        }

        .circles li:nth-child(7) {
            left: 35%;
            width: 150px;
            height: 150px;
            animation-delay: 7s;
            background: rgba(255, 99, 132, 0.2);
        }

        .circles li:nth-child(8) {
            left: 50%;
            width: 25px;
            height: 25px;
            animation-delay: 15s;
            animation-duration: 45s;
            background: rgba(54, 162, 235, 0.2);
        }

        .circles li:nth-child(9) {
            left: 20%;
            width: 15px;
            height: 15px;
            animation-delay: 2s;
            animation-duration: 35s;
            background: rgba(255, 159, 64, 0.2);
        }

        .circles li:nth-child(10) {
            left: 85%;
            width: 150px;
            height: 150px;
            animation-delay: 0s;
            animation-duration: 11s;
            background: rgba(153, 102, 255, 0.2);
        }

        @keyframes float {
            0% { transform: translateY(0) rotate(0deg); opacity: 1; }
            100% { transform: translateY(-1000px) rotate(720deg); opacity: 0; }
        }

        /* Main Content Container */
        .container {
            background: rgba(255, 255, 255, 0.9);
            padding: 3rem;
            border-radius: 25px;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.2);
            max-width: 700px;
            width: 90%;
            animation: fadeIn 1.5s ease-out;
            z-index: 1;
            backdrop-filter: blur(5px);
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* Logo Styling */
        .logo {
            margin-bottom: 2rem;
        }

        .logo-main {
            font-family: 'Montserrat', sans-serif;
            font-size: 3.5rem;
            font-weight: 700;
            color: #0066cc;
            text-transform: uppercase;
            letter-spacing: 3px;
            margin-bottom: 0.5rem;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1);
        }

        .logo-sub {
            font-family: 'Montserrat', sans-serif;
            font-size: 1.8rem;
            font-weight: 600;
            color: #ff9900;
            letter-spacing: 2px;
        }

        /* Main Heading */
        h1 {
            font-family: 'Montserrat', sans-serif;
            font-size: 2.2rem;
            margin-bottom: 1.5rem;
            color: #222;
        }

        /* Message Text */
        .message {
            font-size: 1.2rem;
            line-height: 1.7;
            margin-bottom: 2rem;
            color: #444;
        }

        .highlight {
            color: #0066cc;
            font-weight: 600;
        }

        /* Countdown Timer */
        .countdown {
            margin: 2rem 0;
            padding: 1.5rem;
            background: rgba(0, 102, 204, 0.1);
            border-radius: 15px;
        }

        .countdown-title {
            font-size: 1.2rem;
            margin-bottom: 1rem;
            color: #0066cc;
            font-weight: 600;
        }

        .timer {
            display: flex;
            justify-content: center;
            gap: 15px;
        }

        .time-unit {
            background: white;
            padding: 15px;
            border-radius: 10px;
            min-width: 80px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }

        .time-value {
            font-size: 2.5rem;
            font-weight: 700;
            color: #0066cc;
            font-family: 'Montserrat', sans-serif;
        }

        .time-label {
            font-size: 0.9rem;
            color: #666;
            text-transform: uppercase;
            margin-top: 5px;
        }

        /* Progress Bar */
        .progress-container {
            width: 100%;
            height: 20px;
            background: rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            overflow: hidden;
            margin: 2rem 0;
        }

        .progress-bar {
            height: 100%;
            width: 65%;
            background: linear-gradient(90deg, #0066cc, #0099ff);
            border-radius: 10px;
            animation: loadingShift 3s infinite ease-in-out;
            position: relative;
        }

        .progress-bar::after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            bottom: 0;
            right: 0;
            background-image: linear-gradient(
                -45deg, 
                rgba(255, 255, 255, 0.2) 25%, 
                transparent 25%, 
                transparent 50%, 
                rgba(255, 255, 255, 0.2) 50%, 
                rgba(255, 255, 255, 0.2) 75%, 
                transparent 75%, 
                transparent
            );
            z-index: 1;
            background-size: 50px 50px;
            animation: move 2s linear infinite;
        }

        @keyframes move {
            0% { background-position: 0 0; }
            100% { background-position: 50px 50px; }
        }

        @keyframes loadingShift {
            0% { background-position: 0% 0; }
            100% { background-position: 100% 0; }
        }

        /* Contact Information */
        .contact-info {
            margin: 2rem 0;
        }

        .contact-text {
            font-size: 1.1rem;
            margin-bottom: 1rem;
            color: #444;
        }

        /* Telegram Link Styling */
        .telegram-link {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            background: linear-gradient(to right, #0088cc, #2AABEE);
            color: white !important;
            text-decoration: none;
            padding: 12px 25px;
            border-radius: 50px;
            font-weight: 600;
            font-size: 1.1rem;
            transition: all 0.3s ease;
            box-shadow: 0 5px 15px rgba(0, 136, 204, 0.4);
        }

        .telegram-link i {
            margin-right: 10px;
            font-size: 1.3rem;
        }

        .telegram-link:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 20px rgba(0, 136, 204, 0.6);
        }

        /* Footer */
        .footer {
            margin-top: 2rem;
            font-size: 0.9rem;
            color: #666;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .container {
                padding: 2rem 1.5rem;
            }
            
            .logo-main {
                font-size: 2.5rem;
            }
            
            .logo-sub {
                font-size: 1.4rem;
            }
            
            h1 {
                font-size: 1.8rem;
            }
            
            .message {
                font-size: 1rem;
            }
            
            .time-unit {
                min-width: 60px;
                padding: 10px;
            }
            
            .time-value {
                font-size: 1.8rem;
            }
            
            .timer {
                gap: 10px;
            }
        }
    </style>
</head>
<body>
    <!-- Animated background elements -->
    <ul class="circles">
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
    
    <div class="container">
        <!-- Logo -->
        <div class="logo">
            <div class="logo-main">EMIRATES</div>
            <div class="logo-sub">WEALTH SUPPORT</div>
        </div>
        
        <!-- Main Heading -->
        <h1>System Upgrade in Progress</h1>
        
        <!-- Message -->
        <p class="message">
            We're enhancing your <span class="highlight">Emirates Wealth Support</span> experience with a major upgrade. Our team is working hard to implement new features and improvements.
            <br><br>
            We appreciate your patience and look forward to serving you better with our upgraded platform. The maintenance is expected to be completed shortly.
        </p>

        <!-- Countdown Timer (set for 3 hours) -->
        <div class="countdown">
            <div class="countdown-title">Estimated Time Remaining</div>
            <div class="timer">
                <div class="time-unit">
                    <div class="time-value" id="hours">03</div>
                    <div class="time-label">Hours</div>
                </div>
                <div class="time-unit">
                    <div class="time-value" id="minutes">00</div>
                    <div class="time-label">Minutes</div>
                </div>
                <div class="time-unit">
                    <div class="time-value" id="seconds">00</div>
                    <div class="time-label">Seconds</div>
                </div>
            </div>
        </div>

        <!-- Progress Bar -->
        <div class="progress-container">
            <div class="progress-bar"></div>
        </div>

        <!-- Contact Information -->
        <div class="contact-info">
            <p class="contact-text">For urgent inquiries, contact us on Telegram:</p>
            <a href="https://t.me/emirates_wealth_2" target="_blank" class="telegram-link">
                <i class="fab fa-telegram-plane"></i> @emirates_wealth_2
            </a>
        </div>

        <!-- Footer -->
        <p class="footer">&copy; 2023 Emirates Wealth Support. All Rights Reserved.</p>
    </div>

    <!-- JavaScript for Countdown Timer -->
    <script>
        // Set the countdown time (3 hours from now)
        const countdownTime = new Date();
        countdownTime.setHours(countdownTime.getHours() + 3);
        
        function updateCountdown() {
            const now = new Date();
            const difference = countdownTime - now;
            
            if (difference <= 0) {
                document.getElementById('hours').textContent = '00';
                document.getElementById('minutes').textContent = '00';
                document.getElementById('seconds').textContent = '00';
                return;
            }
            
            const hours = Math.floor(difference / (1000 * 60 * 60));
            const minutes = Math.floor((difference % (1000 * 60 * 60)) / (1000 * 60));
            const seconds = Math.floor((difference % (1000 * 60)) / 1000);
            
            document.getElementById('hours').textContent = hours.toString().padStart(2, '0');
            document.getElementById('minutes').textContent = minutes.toString().padStart(2, '0');
            document.getElementById('seconds').textContent = seconds.toString().padStart(2, '0');
        }
        
        // Update countdown every second
        setInterval(updateCountdown, 1000);
        updateCountdown(); // Initial call
    </script>
</body>
</html>
