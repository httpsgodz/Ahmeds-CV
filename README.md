<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ahmed Waleed Portfolio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #d3d3d3;
            background-image: 
                url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/svgs/solid/code-branch.svg'),
                url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/svgs/solid/cogs.svg');
            background-repeat: repeat;
            background-position: top left, bottom right;
            background-size: 50px 50px, 60px 60px;
        }
        header {
            background: linear-gradient(90deg, #1e3a8a, #2563eb);
            color: white;
            text-align: center;
            padding: 1rem 0;
            animation: fadeIn 2s ease-in-out;
        }
        header h1 {
            margin: 0;
        }
        section {
            padding: 2rem;
            max-width: 800px;
            margin: auto;
            background: white;
            margin-top: 2rem;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
            animation: fadeInUp 1s ease-in-out;
        }
        section h2 {
            color: #1e3a8a;
            margin-bottom: 1rem;
        }
        section p, section ul {
            font-size: 1rem;
            line-height: 1.6;
            color: #333;
        }
        ul {
            padding-left: 20px;
        }
        footer {
            text-align: center;
            padding: 1rem;
            background-color: #1e3a8a;
            color: white;
            margin-top: 2rem;
            animation: fadeIn 2s ease-in-out;
        }
        .animated {
            animation: fadeIn 2s ease-in-out;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .icon {
            font-size: 1.5rem;
            margin-right: 10px;
        }

        .honor-item {
            display: flex;
            align-items: center;
            margin-bottom: 10px;
        }

        .honor-item i {
            font-size: 1.5rem;
            margin-right: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ahmed Waleed Portfolio <i class="fas fa-laptop-code icon"></i></h1>
    </header>

    <section>
        <h2>About Me</h2>
        <p><i class="fas fa-user icon"></i> IT student at Fathalla IATS, specializing in Programming and Information Systems. Experienced in competitive programming, reaching finals in events like ECPC, and mentoring in IEEE YESIST 12. Passionate about technology and community service.</p>
        <p><i class="fas fa-map-marker-alt icon"></i> Location: El Agamy, El bitash, Alexandria, Egypt</p>
        <p><i class="fas fa-phone icon"></i> Phone: (+20) 1221578285 | <i class="fas fa-envelope icon"></i> Email: <a href="mailto:ahmedwaleedhosny@gmail.com">ahmedwaleedhosny@gmail.com</a> | <i class="fab fa-whatsapp icon"></i> WhatsApp: 0121578285</p>
    </section>

    <section>
        <h2>Work Experience</h2>
        <p><strong><i class="fas fa-briefcase icon"></i> Technical Support</strong><br> Fathalla Market</p>
        <p>Managed cashier issues</p>
        <p>Scales problems</p>
        <p>System issues</p>
        <p>Temperature sensors installation</p>
        <p>Camera installation</p>
        <p>Printer fixing</p>
    </section>

    <section>
        <h2>Projects</h2>
        <p><strong><i class="fas fa-project-diagram icon"></i> Blinds Digital Assistant</strong> [15 Nov 2022 – Current]</p>
        <p>A "AI-Powered Assistance for the Visually Impaired: Enhancing Daily Living". This research introduces an innovative mobile application employing cutting-edge artificial intelligence (AI) technology tailored to facilitate the day-to-day tasks of individuals living with visual impairments.</p>

        <p><strong><i class="fas fa-project-diagram icon"></i> Tone-Tune</strong> [7 Oct 2024 – 11 Jan 2025]</p>
        <p>A groundbreaking project designed to analyze and optimize vocal tones and speech clarity, particularly in call centers. Tone-Tune helps in evaluating employee performance through precise metrics, ensuring communication efficiency and professionalism in customer service.</p>
    </section>

    <section>
        <h2>Honours and Awards</h2>
        <ul>
            <li class="honor-item">
                <i class="fas fa-trophy icon"></i> ICPC: 42nd place in the final competition (22 Jul 2024)
            </li>
            <li class="honor-item">
                <i class="fas fa-medal icon"></i> ISEF: Participated two years in a row (2023, 2024)
            </li>
            <li class="honor-item">
                <i class="fas fa-certificate icon"></i> The 24th Arab Conference: 2nd place
            </li>
        </ul>
    </section>

    <section>
        <h2>Language Skills</h2>
        <p><i class="fas fa-language icon"></i> Arabic (native), English (proficient)</p>
    </section>

    <section>
        <h2>Skills</h2>
        <ul>
            <li><i class="fas fa-laptop-code icon"></i> Proficient in Microsoft Office Suite (Word, Excel, PowerPoint)</li>
            <li><i class="fas fa-laptop-code icon"></i> Software development</li>
            <li><i class="fas fa-comments icon"></i> Good communication skills</li>
            <li><i class="fas fa-code icon"></i> Programming: Python, C++, C#, Flutter, HTML, CSS, and Arduino</li>
        </ul>
    </section>

    <section>
        <h2>Hobbies</h2>
        <ul>
            <li><i class="fas fa-utensils icon"></i> Cooking</li>
            <li><i class="fas fa-basketball-ball icon"></i> Basketball</li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2025 Ahmed Waleed (GODZzz). All rights reserved.</p>
    </footer>
</body>
</html>
