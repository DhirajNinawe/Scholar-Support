<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Scholar Support - Fully Functional</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&family=Arial+Rounded+MT+Bold&display=swap" rel="stylesheet">
    <!-- Link to your external CSS file -->
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Header -->
    <header class="site-header" id="site-header">
        <div class="logo" id="logo-btn">
            <img src="https://i.ibb.co/ZRgpz3KH/a-logo-design-featuring-the-text-scholar-A6y-DD5u-NTwen-OL8l4-DHOjg-N5-Xs-Tw-YCQz-Qg-ALMEaz-R6-A-rem.png" alt="Scholar Support Logo" />
        </div>
        <div class="search-bar-wrapper" id="hero-search-wrapper">
            <div class="search-bar" id="search-bar-container">
                <input type="text" id="hero-search-input" placeholder="Search schemes..." autocomplete="off" />
                <button id="hero-search-btn">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <circle cx="11" cy="11" r="8" />
                        <path d="m21 21-4.3-4.3" />
                    </svg>
                </button>
            </div>
            <div class="suggestions-box" id="hero-suggestions"><ul></ul></div>
        </div>
    </header>

    <!-- Main Content -->
    <main>
        <!-- Hero Section -->
        <section class="hero-section">
            <div class="hero-content">
                <img src="https://i.ibb.co/ZRgpz3KH/a-logo-design-featuring-the-text-scholar-A6y-DD5u-NTwen-OL8l4-DHOjg-N5-Xs-Tw-YCQz-Qg-ALMEaz-R6-A-rem.png" alt="Scholar Support Logo" class="hero-logo-display" />
                <div class="hero-headline-text">Welcome!</div>
                <button class="hero-button">EXPLORE SCHEMES</button>
            </div>
        </section>
    </main>

    <!-- Schemes Section (Slide-up panel) -->
    <section id="schemes-section">
        <div class="schemes-header">
             <div class="search-bar-wrapper">
                <div class="scheme-search-bar">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <circle cx="11" cy="11" r="8" />
                        <path d="m21 21-4.3-4.3" />
                    </svg>
                    <input type="text" id="scheme-search-input" placeholder="Search all schemes..." autocomplete="off"/>
                </div>
                <div class="suggestions-box" id="scheme-suggestions"><ul></ul></div>
            </div>
        </div>
       
        <div class="scheme-categories-container">
            <!-- Categories and cards here -->
            <div class="scheme-category">
                <h2 class="category-title">Schemes for Girls</h2>
                <div class="schemes-grid">
                    <div class="scheme-card" data-keywords="technical education girls">
                        <h3>AICTE Pragati Scholarship for Girls</h3>
                        <p>Provides financial assistance for the advancement of girls participating in technical education.</p>
                        <button class="apply-btn">View Details</button>
                    </div>
                    <div class="scheme-card" data-keywords="minority community">
                        <h3>Begum Hazrat Mahal National Scholarship</h3>
                        <p>For meritorious girl students from minority communities who cannot continue their education due to financial constraints.</p>
                        <button class="apply-btn">View Details</button>
                    </div>
                    <div class="scheme-card" data-keywords="engineering college mentor">
                        <h3>CBSE Udaan Scheme</h3>
                        <p>A project by CBSE to mentor girl students to compete for admission in premier engineering colleges.</p>
                        <button class="apply-btn">View Details</button>
                    </div>
                     <div class="scheme-card" data-keywords="maharashtra backward class 5th 10th">
                        <h3>Savitribai Phule Scholarship (Maharashtra)</h3>
                        <p>Financial aid for girls from backward classes in standards 5th to 10th to encourage education.</p>
                        <button class="apply-btn">View Details</button>
                    </div>
                </div>
            </div>

            <div class="scheme-category">
                <h2 class="category-title">Education Loans</h2>
                <div class="schemes-grid">
                    <div class="scheme-card" data-keywords="interest subsidy weaker section">
                        <h3>Central Sector Interest Subsidy Scheme</h3>
                        <p>Provides full interest subsidy during the moratorium period on loans for students from economically weaker sections.</p>
                        <button class="apply-btn">View Details</button>
                    </div>
                     <div class="scheme-card" data-keywords="bank loan portal">
                        <h3>Vidya Lakshmi Portal</h3>
                        <p>A single-window portal for students to access information and apply for educational loans from various banks.</p>
                        <button class="apply-btn">View Details</button>
                    </div>
                    <div class="scheme-card" data-keywords="overseas studies obc ebc">
                        <h3>Dr. Ambedkar Central Sector Scheme</h3>
                        <p>Interest subsidy on educational loans for overseas studies for students belonging to OBC and EBC categories.</p>
                        <button class="apply-btn">View Details</button>
                    </div>
                </div>
            </div>

            <div class="scheme-category">
                <h2 class="category-title">Internship Opportunities</h2>
                <div class="schemes-grid">
                    <div class="scheme-card" data-keywords="niti aayog policy">
                        <h3>NITI Aayog Internship Scheme</h3>
                        <p>An opportunity for young individuals to familiarize themselves with the work of NITI Aayog and contribute to policy formulation.</p>
                        <button class="apply-btn">View Details</button>
                    </div>
                     <div class="scheme-card" data-keywords="swachh bharat village summer">
                        <h3>Swachh Bharat Summer Internship</h3>
                        <p>Engages youth across the country in Swachh Bharat related activities at the village level.</p>
                        <button class="apply-btn">View Details</button>
                    </div>
                </div>
            </div>

            <div class="scheme-category">
                <h2 class="category-title">Post-Graduate Studies</h2>
                <div class="schemes-grid">
                    <div class="scheme-card" data-keywords="single girl child masters degree">
                        <h3>Post-Graduate Indira Gandhi Scholarship</h3>
                        <p>For single girl children pursuing full-time Master's degree courses in any designated university or college.</p>
                        <button class="apply-btn">View Details</button>
                    </div>
                    <div class="scheme-card" data-keywords="minorities phd matric">
                        <h3>Post-Matric Scholarship for Minorities</h3>
                        <p>For students from minority communities studying in classes 11th to PhD. Provides financial support for their education.</p>
                        <button class="apply-btn">View Details</button>
                    </div>
                     <div class="scheme-card" data-keywords="university rank holder masters">
                        <h3>PG Scholarship for University Rank Holders</h3>
                        <p>For undergraduate rank holders to pursue their Master's degree in any of the recognized universities in India.</p>
                        <button class="apply-btn">View Details</button>
                    </div>
                </div>
            </div>
        </div>
        
        <p id="no-results-message">This scheme is yet to be uploaded on the portal.</p>

        <div class="back-btn-container">
            <button id="back-to-hero-btn" class="back-btn">← Back to Home</button>
        </div>
    </section>

    <!-- Backdrop Overlay -->
    <div id="backdrop-overlay"></div>

    <!-- Sidebar Navigation -->
    <div class="sidebar" id="sidebar">
        <div class="sidebar-content">
            <button class="close-btn" id="close-sidebar-btn">✖</button>
            <h2>Navigation</h2>
            <ul>
                <li><a data-panel="login-panel">🔐 Login</a></li>
                <li><a data-panel="profile-panel">👤 Your ID</a></li>
                <li><a data-panel="about-panel">📖 About Us</a></li>
                <li><a data-panel="help-panel">❓ Help</a></li>
            </ul>
        </div>
    </div>

    <!-- Login Panel -->
    <div class="login-panel panel" id="login-panel">
        <div class="login-content panel-content">
            <button class="close-btn" data-panel="login-panel">✖</button>
            <h2>Login</h2>
            <form onsubmit="return false">
                <label for="email">Username or Email</label>
                <input type="text" id="email" placeholder="Enter email or username" required />
                <label for="password">Password</label>
                <input type="password" id="password" placeholder="Enter password" required />
                <button type="button" class="login-btn">Login</button>
                <div class="login-footer">
                    <button type="button" class="signup-btn">Sign Up</button>
                    <button type="button" class="forgot-btn">Forgot Password?</button>
                </div>
            </form>
        </div>
    </div>

    <!-- YOUR ID Panel -->
    <div class="panel" id="profile-panel">
        <div class="panel-content">
            <button class="close-btn" data-panel="profile-panel">✖</button>
            <h2>Your ID</h2>
            <form onsubmit="return false">
                <label>Name:</label>
                <input type="text" placeholder="Enter your name" required />
                <label>Age:</label>
                <input type="number" placeholder="Enter your age" required />
                <label>Caste:</label>
                <input type="text" placeholder="Enter your caste" required />
                <label>Education:</label>
                <input type="text" placeholder="Enter education level" required />
                <label>College Name:</label>
                <input type="text" placeholder="Enter your college name" required />
                <label>Annual Income:</label>
                <input type="number" placeholder="Enter your family's annual income" required />
                <button type="submit">Save Info</button>
            </form>
        </div>
    </div>

    <!-- ABOUT US Panel -->
    <div class="panel" id="about-panel">
        <div class="panel-content">
            <button class="close-btn" data-panel="about-panel">✖</button>
            <h2>About Us</h2>
            <p>
                <strong>Welcome to Scholar Support – Your trusted gateway to student empowerment through government schemes!</strong><br><br>
                🎯 <strong>Our Mission:</strong><br>
                To simplify access to government schemes for every student across Maharashtra.<br><br>
                💡 <strong>Why We Exist:</strong><br>
                Government schemes offer life-changing benefits — scholarships, fee waivers, skill-building programs — but thousands of students miss out due to lack of awareness. Scholar Support bridges that gap by transforming information into action.<br><br>
                🚀 <strong>What We Offer:</strong><br>
                • 🔍 Smart filters to match your needs<br>
                • 🃏 Interactive cards with key details<br>
                • 📝 Step-by-step guides for hassle-free applications<br>
                • 🎓 Desktop-friendly access via Scholar Support<br><br>
                🛠️ <strong>Meet the Team:</strong><br>
                • 👨‍💻 Dhiraj Ninawe<br>
                • 👨‍💼 Dhruv Vishwakarma<br>
                • 🎨 Amol Rahangdale<br>
                • 🔧 Govind Sharma<br><br>
                📣 We're here to give you access to every opportunity that exists.
            </p>
        </div>
    </div>

    <!-- HELP PANEL -->
    <div class="panel" id="help-panel">
        <div class="panel-content">
            <button class="close-btn" data-panel="help-panel">✖</button>
            <h2>Help Desk</h2>
            <p>
                💬 <strong>Ask Us Anything:</strong><br>
                Whether you're unsure about eligibility, documents, or how to apply — just reach out.<br><br>
                📩 <strong>Contact Support:</strong><br>
                • 📧 Email: support@scoller.in<br>
                • 📞 WhatsApp: +91 91234 56789<br><br>
                🚀 <strong>Quick Tools:</strong><br>
                • 🧾 Application Checklists<br><br>
                🤝 We're here to help you take action confidently.
            </p>
        </div>
    </div>

    <!-- Link to your external JavaScript file -->
    <script src="script.js"></script>
</body>
</html>
/* Global CSS Variables */
:root {
    --gold-dark: #D8AE7E;
    --gold: #F8C794;
    --peach: #FFE0B5;
    --cream: #FFF2D7;
    --text: #3a2b1c;
    --dark-overlay: rgba(0, 0, 0, 0.5);
    /* New Color Palette for Navigation Panels */
    --panel-bg: #F0F4F8;
    --panel-accent-light: #78909C;
    --panel-accent-dark: #546E7A;
    --panel-text: #263238;
}

/* Universal Box-Sizing and Font */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Inter', sans-serif;
    color: var(--text);
    background-color: var(--cream);
    overflow-x: hidden;
    overflow-y: hidden; 
    transition: overflow-y 0.3s ease;
}

body.no-scroll {
    overflow-y: hidden;
}

/* Header - Fixed and Transparent */
.site-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: transparent;
    padding: 10px 20px;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    z-index: 1002;
    height: 70px;
    transition: background-color 0.3s ease;
}

.site-header.schemes-view-active {
    background-color: white;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.site-header.schemes-view-active #search-bar-container {
    visibility: hidden;
    opacity: 0;
}

/* Logo Styling */
.logo img {
    height: 60px;
    cursor: pointer;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    border-radius: 8px;
}

.logo img:hover {
    transform: scale(1.05);
    box-shadow: 0 0 15px rgba(216, 174, 126, 0.8);
}

/* Search Bar Styling (Hero) */
.search-bar-wrapper {
    position: relative;
}

#search-bar-container {
    display: flex;
    align-items: center;
    background-color: rgba(255, 255, 255, 0.2);
    backdrop-filter: blur(8px);
    -webkit-backdrop-filter: blur(8px);
    border: 1px solid rgba(255, 255, 255, 0.3);
    border-radius: 30px;
    padding: 6px 15px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    transition: all 0.3s ease;
    opacity: 1;
    visibility: visible;
}

#search-bar-container input {
    border: none;
    outline: none;
    font-size: 16px;
    padding: 5px;
    width: 220px;
    background: transparent;
    color: white;
}

#search-bar-container input::placeholder {
    color: rgba(255, 255, 255, 0.7);
}

#search-bar-container button {
    background: none;
    border: none;
    font-size: 20px;
    cursor: pointer;
    color: white;
    margin-left: 10px;
    display: flex;
    align-items: center;
    justify-content: center;
    border-left: 1px solid rgba(255, 255, 255, 0.4);
    padding: 3px 15px 3px 15px;
}

#search-bar-container button svg {
    stroke: white;
}

/* Hero Section */
.hero-section {
    width: 100vw;
    height: 100vh;
    background-image: url('https://images.unsplash.com/photo-1531297484001-80022131f5a1?q=80&w=2020&auto=format&fit=crop');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;
    z-index: 1;
}

.hero-section::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.5);
    z-index: 2;
}

.hero-content {
    position: relative;
    z-index: 3;
    padding: 20px;
    max-width: 800px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

.hero-headline-text {
    font-family: 'Arial Rounded MT Bold', 'Arial Rounded', 'Arial', sans-serif;
    font-size: 32px;
    font-weight: bold;
    color: white;
    margin-top: 15px;
    margin-bottom: 35px;
    text-transform: none;
}

.hero-logo-display {
    height: 220px;
}

.hero-button {
    padding: 15px 35px;
    background-color: white;
    color: black;
    border: none;
    border-radius: 30px;
    font-size: 1.2em;
    font-weight: 600;
    cursor: pointer;
    transition: background-color 0.3s ease, transform 0.2s ease, box-shadow 0.3s ease;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
    text-transform: uppercase;
    letter-spacing: 1px;
}

.hero-button:hover {
    background-color: #f0f0f0;
    transform: translateY(-3px);
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.4);
}

/* Sidebar Navigation */
.sidebar {
    position: fixed;
    top: 0;
    left: -280px;
    width: 280px;
    height: 100%;
    background-color: var(--panel-bg);
    box-shadow: 3px 0 10px rgba(0,0,0,0.3);
    z-index: 1003;
    transition: left 0.4s cubic-bezier(0.68, -0.55, 0.265, 1.55);
}

.sidebar.active {
    left: 0;
}

.sidebar-content {
    padding: 30px 20px;
    height: 100%;
    overflow-y: auto;
}

.sidebar-content h2 {
    color: var(--panel-accent-dark);
    margin-bottom: 30px;
    font-size: 1.8em;
    border-bottom: 2px solid var(--panel-accent-light);
    padding-bottom: 10px;
}

.sidebar-content ul {
    list-style: none;
}

.sidebar-content ul li {
    margin: 20px 0;
}

.sidebar-content ul li a {
    display: block;
    background-color: var(--panel-accent-light);
    padding: 15px 20px;
    border-radius: 12px;
    font-weight: 600;
    color: white;
    text-decoration: none;
    box-shadow: 0 5px 10px rgba(0,0,0,0.15);
    transition: all 0.3s ease;
    text-align: center;
    cursor: pointer;
}

.sidebar-content ul li a:hover {
    background-color: var(--panel-accent-dark);
    color: white;
    transform: scale(1.03);
    box-shadow: 0 8px 15px rgba(0,0,0,0.25);
}

/* Login Panel and other Panels */
.login-panel, .panel {
    position: fixed;
    top: 0;
    right: -100%;
    width: 100%;
    max-width: 450px;
    height: 100vh;
    background-color: var(--panel-bg);
    box-shadow: -5px 0 15px rgba(0,0,0,0.3);
    transition: right 0.4s ease-out;
    z-index: 1004;
    padding: 30px;
    border-radius: 15px 0 0 15px;
    display: flex;
    flex-direction: column;
}

.login-panel.active, .panel.active {
    right: 0;
}

.login-content, .panel-content {
    flex-grow: 1;
    display: flex;
    flex-direction: column;
    height: 100%;
    overflow-y: auto;
    padding-right: 10px;
}

.login-content h2, .panel-content h2 {
    color: var(--panel-accent-dark);
    margin-bottom: 25px;
    font-size: 2em;
    border-bottom: 2px solid var(--panel-accent-light);
    padding-bottom: 10px;
}

.login-content label, .panel-content label {
    margin-top: 15px;
    font-weight: 600;
    font-size: 1.1em;
    color: var(--panel-text);
}

.login-content input, .panel-content input {
    padding: 12px;
    margin-top: 8px;
    border-radius: 10px;
    border: 1px solid #ccc;
    font-size: 16px;
    width: 100%;
    background-color: white;
    color: var(--panel-text);
}

.login-btn, .panel-content button[type="submit"] {
    margin-top: 30px;
    padding: 15px;
    background-color: var(--panel-accent-dark);
    color: white;
    border: none;
    border-radius: 10px;
    cursor: pointer;
    font-weight: 700;
    font-size: 1.1em;
    transition: background 0.3s ease, transform 0.2s ease, box-shadow 0.3s ease;
    box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
}

.login-btn:hover, .panel-content button[type="submit"]:hover {
    background-color: var(--panel-accent-light);
    transform: translateY(-2px);
    box-shadow: 0 8px 15px rgba(0, 0, 0, 0.3);
}

.login-footer {
    display: flex;
    justify-content: space-between;
    margin-top: 25px;
    font-size: 0.95em;
}

.signup-btn, .forgot-btn {
    background: none;
    border: none;
    color: var(--panel-text);
    cursor: pointer;
    text-decoration: underline;
    font-size: 1em;
    transition: color 0.3s ease;
}

.signup-btn:hover, .forgot-btn:hover {
    color: var(--panel-accent-dark);
}

.close-btn {
    float: right;
    font-size: 24px;
    border: none;
    background: none;
    cursor: pointer;
    color: var(--panel-text);
    margin-top: -15px;
    margin-right: -10px;
    transition: transform 0.2s ease, color 0.2s ease;
}

.close-btn:hover {
    transform: rotate(90deg);
    color: var(--panel-accent-dark);
}

/* Schemes Section Styling */
#schemes-section {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: #fff;
    z-index: 1000;
    transform: translateY(100%);
    transition: transform 0.6s cubic-bezier(0.77, 0, 0.175, 1);
    overflow-y: auto;
    padding: 90px 40px 100px 40px;
}

#schemes-section.active {
    transform: translateY(0);
}

.schemes-header {
    max-width: 1200px;
    margin: 0 auto 30px auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 20px;
}

.scheme-search-bar {
    display: flex;
    align-items: center;
    background-color: #f0f4f8;
    border: 1px solid #e0e0e0;
    border-radius: 30px;
    padding: 8px 15px;
    width: 100%;
    max-width: 400px;
}

.scheme-search-bar input {
    border: none;
    outline: none;
    font-size: 16px;
    width: 100%;
    background: transparent;
    color: var(--panel-text);
}

.scheme-search-bar input::placeholder {
    color: var(--panel-accent-light);
}

.scheme-search-bar svg {
    margin-right: 10px;
    stroke: var(--panel-accent-light);
}

.scheme-category {
    max-width: 1200px;
    margin: 0 auto 50px auto;
}

.category-title {
    font-size: 2em;
    color: var(--panel-accent-dark);
    text-align: left;
    margin-bottom: 20px;
    padding-bottom: 10px;
    border-bottom: 2px solid var(--peach);
}

.schemes-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
}

.scheme-card {
    background-color: var(--cream);
    border-radius: 15px;
    padding: 20px;
    text-align: left;
    box-shadow: 0 8px 15px rgba(0,0,0,0.08);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    display: flex;
    flex-direction: column;
}

.scheme-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 12px 25px rgba(0,0,0,0.12);
}

.scheme-card h3 {
    font-size: 1.3em;
    color: var(--gold-dark);
    margin-bottom: 10px;
}

.scheme-card p {
    font-size: 0.95em;
    line-height: 1.5;
    color: var(--text);
    flex-grow: 1; 
    margin-bottom: 15px;
}

.apply-btn {
    padding: 10px 20px;
    background-color: var(--gold-dark);
    color: white;
    border: none;
    border-radius: 25px;
    cursor: pointer;
    font-weight: 600;
    font-size: 0.9em;
    transition: background-color 0.3s ease;
    align-self: flex-start;
}

.apply-btn:hover {
    background-color: #c59a6d;
}

#no-results-message {
    display: none;
    text-align: center;
    font-size: 1.2em;
    color: var(--panel-accent-light);
    margin-top: 40px;
}

.back-btn-container {
    text-align: center;
    padding: 30px 0;
}

.back-btn {
    padding: 15px 40px;
    background-color: var(--panel-accent-dark);
    color: white;
    border: none;
    border-radius: 30px;
    cursor: pointer;
    font-weight: 700;
    font-size: 1.2em;
    transition: all 0.3s ease;
    box-shadow: 0 5px 15px rgba(0,0,0,0.2);
}

.back-btn:hover {
    background-color: var(--panel-accent-light);
    transform: translateY(-3px);
    box-shadow: 0 8px 20px rgba(0,0,0,0.3);
}

/* Search Suggestions */
.suggestions-box {
    display: none;
    position: absolute;
    top: 100%;
    left: 0;
    right: 0;
    background-color: white;
    border: 1px solid #ddd;
    border-radius: 15px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    max-height: 200px;
    overflow-y: auto;
    z-index: 10;
}

.suggestions-box ul {
    list-style: none;
    padding: 5px 0;
}

.suggestions-box li {
    padding: 10px 15px;
    cursor: pointer;
    color: var(--panel-text);
}

.suggestions-box li:hover {
    background-color: #f0f4f8;
}

#hero-search-wrapper .suggestions-box {
    border-radius: 20px;
}

#hero-search-wrapper .suggestions-box li {
     color: var(--text);
}


/* Backdrop Overlay */
#backdrop-overlay {
    position: fixed;
    top: 0;
    left: 0;
    width: 100vw;
    height: 100vh;
    background-color: rgba(0, 0, 0, 0.3);
    z-index: 1002;
    opacity: 0;
    visibility: hidden;
    transition: opacity 0.3s ease, visibility 0.3s ease;
}

#backdrop-overlay.active {
    opacity: 1;
    visibility: visible;
}

/* Responsive Adjustments */
@media (max-width: 768px) {
    .site-header {
        padding: 5px 10px;
        height: 60px;
    }
    .logo img {
        height: 45px;
    }
    .hero-logo-display {
        height: 180px;
    }
    .hero-headline-text {
        font-size: 28px;
    }
    .hero-button {
        padding: 12px 25px;
        font-size: 1em;
    }
    .sidebar {
        width: 240px;
        left: -240px;
    }
    .login-panel, .panel {
        max-width: 90%;
        padding: 20px;
    }
    .login-content h2, .panel-content h2 {
        font-size: 1.8em;
    }
    #schemes-section {
        padding: 80px 20px 100px 20px;
    }
    .schemes-header {
        flex-direction: column;
        align-items: center;
        gap: 20px;
    }
     .category-title {
        font-size: 1.8em;
    }
}

@media (max-width: 480px) {
    .site-header {
        justify-content: space-between;
    }
    #search-bar-container {
        display: none;
    }
    .hero-logo-display {
        height: 140px;
    }
    .hero-headline-text {
        font-size: 24px;
    }
    .hero-button {
        font-size: 0.9em;
        padding: 10px 20px;
    }
    .sidebar {
        width: 100%;
        left: -100%;
    }
    .login-panel, .panel {
        max-width: 100%;
        border-radius: 0;
    }
    .login-footer {
        flex-direction: column;
        gap: 10px;
    }
    .schemes-grid {
        grid-template-columns: 1fr;
    }
}
document.addEventListener('DOMContentLoaded', function () {
    // --- Element Selections ---
    const siteHeader = document.getElementById('site-header');
    const logoBtn = document.getElementById('logo-btn');
    const sidebar = document.getElementById('sidebar');
    const backdropOverlay = document.getElementById('backdrop-overlay');
    const heroSearchInput = document.getElementById('hero-search-input');
    const heroSearchBtn = document.getElementById('hero-search-btn');
    const heroSuggestionsBox = document.getElementById('hero-suggestions');
    const panels = document.querySelectorAll('.panel');
    const sidebarLinks = document.querySelectorAll('.sidebar-content ul li a');
    const closeButtons = document.querySelectorAll('.close-btn');
    const heroButton = document.querySelector('.hero-button');
    const schemesSection = document.getElementById('schemes-section');
    const backToHeroBtn = document.getElementById('back-to-hero-btn');
    const schemeSearchInput = document.getElementById('scheme-search-input');
    const schemeSuggestionsBox = document.getElementById('scheme-suggestions');
    const schemeCategories = document.querySelectorAll('.scheme-category');
    const noResultsMessage = document.getElementById('no-results-message');
    const allSchemeCards = document.querySelectorAll('.scheme-card');

    let activePanel = null; 

    // --- Data Source for Search ---
    const allSchemes = Array.from(allSchemeCards).map(card => {
        return {
            title: card.querySelector('h3').textContent,
            keywords: (card.dataset.keywords || '') + ' ' + card.querySelector('p').textContent
        };
    });
    const allSchemeTitles = allSchemes.map(s => s.title);

    // --- Levenshtein Distance Function for Fuzzy Search ---
    const levenshtein = (a, b) => {
        if (a.length === 0) return b.length;
        if (b.length === 0) return a.length;
        const matrix = [];
        for (let i = 0; i <= b.length; i++) { matrix[i] = [i]; }
        for (let j = 0; j <= a.length; j++) { matrix[0][j] = j; }
        for (let i = 1; i <= b.length; i++) {
            for (let j = 1; j <= a.length; j++) {
                if (b.charAt(i - 1) === a.charAt(j - 1)) {
                    matrix[i][j] = matrix[i - 1][j - 1];
                } else {
                    matrix[i][j] = Math.min(matrix[i - 1][j - 1] + 1, Math.min(matrix[i][j - 1] + 1, matrix[i - 1][j] + 1));
                }
            }
        }
        return matrix[b.length][a.length];
    };

    // --- Reusable Functions ---
    const openSchemesPanel = () => {
        schemesSection.classList.add('active');
        siteHeader.classList.add('schemes-view-active');
        document.body.classList.add('no-scroll');
    };

    const closeSchemesPanel = () => {
        schemesSection.classList.remove('active');
        siteHeader.classList.remove('schemes-view-active');
        document.body.classList.remove('no-scroll');
    };

    const filterSchemes = (searchTerm) => {
        let totalVisibleCards = 0;
        const searchWords = searchTerm.split(' ').filter(w => w.length > 0);

        schemeCategories.forEach(category => {
            let categoryHasVisibleCards = false;
            const cardsInCategory = category.querySelectorAll('.scheme-card');
            
            cardsInCategory.forEach(card => {
                const cardTitle = card.querySelector('h3').textContent.toLowerCase();
                const cardText = card.textContent.toLowerCase();
                
                let isMatch = false;
                if (!searchTerm) {
                    isMatch = true;
                } else {
                    // Check if any search word is a substring or close in spelling
                    isMatch = searchWords.some(word => 
                        cardText.includes(word) || levenshtein(word, cardTitle.split(' ')[0]) < 2
                    );
                }

                card.style.display = isMatch ? 'flex' : 'none';
                if (isMatch) {
                    categoryHasVisibleCards = true;
                    totalVisibleCards++;
                }
            });
            category.style.display = categoryHasVisibleCards ? 'block' : 'none';
        });
        noResultsMessage.style.display = totalVisibleCards === 0 ? 'block' : 'none';
    };

    const updateSuggestions = (input, suggestionsBox) => {
        const searchTerm = input.value.toLowerCase();
        suggestionsBox.querySelector('ul').innerHTML = '';
        if (!searchTerm) {
            suggestionsBox.style.display = 'none';
            return;
        }

        const suggestions = allSchemeTitles.filter(title => 
            title.toLowerCase().includes(searchTerm) || levenshtein(searchTerm, title.toLowerCase().split(' ')[0]) < 2
        ).slice(0, 5); // Limit to 5 suggestions

        if (suggestions.length > 0) {
            suggestions.forEach(title => {
                const li = document.createElement('li');
                li.textContent = title;
                suggestionsBox.querySelector('ul').appendChild(li);
            });
            suggestionsBox.style.display = 'block';
        } else {
            suggestionsBox.style.display = 'none';
        }
    };
    
    // --- Sidebar and Right Panel Logic ---
    const closeAllSidePanels = () => {
        sidebar.classList.remove('active');
        panels.forEach(p => p.classList.remove('active'));
        activePanel = null;
        backdropOverlay.classList.remove('active');
        document.body.classList.remove('no-scroll');
    };
    
    const openSidebar = () => {
        closeAllSidePanels();
        sidebar.classList.add('active');
        activePanel = 'sidebar';
        backdropOverlay.classList.add('active');
        document.body.classList.add('no-scroll');
    };

    const openPanel = (panelId) => {
        panels.forEach(p => {
            if(p.id !== panelId) p.classList.remove('active');
        });
        const panelToOpen = document.getElementById(panelId);
        if (panelToOpen) {
            panelToOpen.classList.add('active');
            activePanel = panelId;
            backdropOverlay.classList.add('active'); 
            document.body.classList.add('no-scroll');
        }
    };
    
    // --- Event Listeners ---

    logoBtn.addEventListener('click', (e) => {
        e.stopPropagation();
        if (schemesSection.classList.contains('active')) closeSchemesPanel();
        else if (sidebar.classList.contains('active') || activePanel) closeAllSidePanels();
        else openSidebar();
    });
    
    heroButton.addEventListener('click', () => {
        openSchemesPanel();
        schemeSearchInput.value = '';
        filterSchemes('');
    });

    heroSearchBtn.addEventListener('click', () => {
        const searchTerm = heroSearchInput.value.toLowerCase();
        openSchemesPanel();
        schemeSearchInput.value = heroSearchInput.value;
        filterSchemes(searchTerm);
        heroSuggestionsBox.style.display = 'none';
    });

    backToHeroBtn.addEventListener('click', closeSchemesPanel);

    heroSearchInput.addEventListener('input', () => updateSuggestions(heroSearchInput, heroSuggestionsBox));
    schemeSearchInput.addEventListener('input', (e) => {
        updateSuggestions(schemeSearchInput, schemeSuggestionsBox);
        filterSchemes(e.target.value.toLowerCase());
    });


    heroSuggestionsBox.addEventListener('click', (e) => {
        if (e.target.tagName === 'LI') {
            heroSearchInput.value = e.target.textContent;
            heroSuggestionsBox.style.display = 'none';
            heroSearchBtn.click();
        }
    });

    schemeSuggestionsBox.addEventListener('click', (e) => {
        if (e.target.tagName === 'LI') {
            schemeSearchInput.value = e.target.textContent;
            schemeSuggestionsBox.style.display = 'none';
            filterSchemes(e.target.textContent.toLowerCase());
        }
    });

    sidebarLinks.forEach(link => {
        link.addEventListener('click', (e) => {
            e.stopPropagation();
            openPanel(e.currentTarget.getAttribute('data-panel'));
        });
    });

    closeButtons.forEach(btn => {
        btn.addEventListener('click', (e) => {
            e.stopPropagation();
            if (btn.id === 'close-sidebar-btn') closeAllSidePanels();
            else { 
                const panelToClose = document.getElementById(e.currentTarget.getAttribute('data-panel'));
                if (panelToClose) {
                    panelToClose.classList.remove('active');
                    activePanel = 'sidebar';
                }
            }
        });
    });

    backdropOverlay.addEventListener('click', () => {
        if(activePanel && activePanel !== 'sidebar'){
            document.getElementById(activePanel).classList.remove('active');
            activePanel = 'sidebar';
        } else { 
            closeAllSidePanels();
        }
    });

    document.addEventListener('click', (e) => {
        if (!heroSearchInput.parentElement.contains(e.target)) heroSuggestionsBox.style.display = 'none';
        if (!schemeSearchInput.parentElement.contains(e.target)) schemeSuggestionsBox.style.display = 'none';
    });

    document.querySelectorAll('.sidebar, .panel').forEach(el => {
        el.addEventListener('click', e => e.stopPropagation());
    });
});
