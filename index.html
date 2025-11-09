<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NovaFrame - Discord Server Builder Bot</title>
    <meta name="description" content="Build, secure, and manage your Discord server instantly — no coding, no hassle.">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --orange: #ff6b35;
            --dark-orange: #d84315;
            --purple: #6a1b9a;
            --dark-purple: #4a148c;
            --bg-dark: #0d0208;
            --bg-darker: #050103;
            --bg-card: #1a0f14;
            --text: #f8f8f8;
            --text-dim: #c5a880;
            --green: #00ff41;
            --red: #ff3838;
            --yellow: #ffd700;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: var(--bg-dark);
            color: var(--text);
            line-height: 1.6;
            overflow-x: hidden;
        }

        /* Animated 3D Background */
        .bg-3d {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            background: linear-gradient(135deg, var(--bg-darker), var(--bg-dark));
            perspective: 1000px;
        }

        .bg-3d::before {
            content: '';
            position: absolute;
            width: 100%;
            height: 100%;
            background: 
                repeating-linear-gradient(0deg, rgba(255,107,53,0.05) 0px, transparent 2px, transparent 40px, rgba(255,107,53,0.05) 42px),
                repeating-linear-gradient(90deg, rgba(106,27,154,0.05) 0px, transparent 2px, transparent 40px, rgba(106,27,154,0.05) 42px);
            animation: grid-move 20s linear infinite;
            transform: rotateX(60deg) translateZ(-100px);
        }

        @keyframes grid-move {
            0% { transform: rotateX(60deg) translateZ(-100px) translateY(0); }
            100% { transform: rotateX(60deg) translateZ(-100px) translateY(40px); }
        }

        .orb {
            position: fixed;
            border-radius: 50%;
            filter: blur(80px);
            animation: float 20s infinite;
            pointer-events: none;
            z-index: -1;
        }

        .orb1 {
            width: 400px;
            height: 400px;
            background: radial-gradient(circle, rgba(255,107,53,0.4), transparent);
            top: 10%;
            left: 10%;
        }

        .orb2 {
            width: 500px;
            height: 500px;
            background: radial-gradient(circle, rgba(106,27,154,0.4), transparent);
            bottom: 10%;
            right: 10%;
            animation-delay: -10s;
        }

        @keyframes float {
            0%, 100% { transform: translate(0, 0); }
            25% { transform: translate(50px, -50px); }
            50% { transform: translate(-30px, 30px); }
            75% { transform: translate(30px, 50px); }
        }

        .page {
            display: none;
        }

        .page.active {
            display: block;
        }

        /* INVITE PAGE */
        .invite-page {
            min-height: 100vh;
            padding: 4rem 2rem;
        }

        .hero {
            text-align: center;
            margin-bottom: 5rem;
        }

        .logo {
            font-size: 10rem;
            animation: glow 3s infinite;
            margin-bottom: 2rem;
        }

        @keyframes glow {
            0%, 100% { filter: drop-shadow(0 0 30px rgba(255,107,53,0.8)) scale(1); }
            50% { filter: drop-shadow(0 0 60px rgba(255,107,53,1)) scale(1.05); }
        }

        h1 {
            font-size: 5rem;
            background: linear-gradient(135deg, var(--orange), var(--purple));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 1rem;
            animation: title-float 6s ease-in-out infinite;
        }

        @keyframes title-float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }

        .tagline {
            font-size: 2rem;
            color: var(--text-dim);
            margin-bottom: 3rem;
            font-style: italic;
        }

        .cta-buttons {
            display: flex;
            gap: 2rem;
            justify-content: center;
            flex-wrap: wrap;
            margin-bottom: 2rem;
        }

        .btn {
            padding: 1.5rem 3rem;
            font-size: 1.3rem;
            font-weight: 700;
            border: none;
            border-radius: 15px;
            cursor: pointer;
            transition: all 0.3s;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            gap: 1rem;
            position: relative;
            overflow: hidden;
        }

        .btn::before {
            content: '';
            position: absolute;
            top: 50%;
            left: 50%;
            width: 0;
            height: 0;
            border-radius: 50%;
            background: rgba(255,255,255,0.3);
            transform: translate(-50%, -50%);
            transition: width 0.6s, height 0.6s;
        }

        .btn:hover::before {
            width: 400px;
            height: 400px;
        }

        .btn span {
            position: relative;
            z-index: 1;
        }

        .btn-primary {
            background: linear-gradient(135deg, var(--orange), var(--dark-orange));
            color: white;
            box-shadow: 0 10px 40px rgba(255,107,53,0.5);
        }

        .btn-primary:hover {
            transform: translateY(-5px) scale(1.05);
            box-shadow: 0 15px 50px rgba(255,107,53,0.7);
        }

        .btn-secondary {
            background: linear-gradient(135deg, var(--purple), var(--dark-purple));
            color: white;
            box-shadow: 0 10px 40px rgba(106,27,154,0.5);
        }

        .btn-secondary:hover {
            transform: translateY(-5px) scale(1.05);
            box-shadow: 0 15px 50px rgba(106,27,154,0.7);
        }

        .info-banner {
            max-width: 800px;
            margin: 0 auto 3rem;
            padding: 1.5rem;
            background: rgba(255,215,0,0.1);
            border: 2px solid var(--yellow);
            border-radius: 15px;
            text-align: center;
        }

        .info-banner strong {
            color: var(--yellow);
        }

        .features {
            max-width: 1400px;
            margin: 0 auto 5rem;
        }

        .section-title {
            font-size: 3rem;
            text-align: center;
            margin-bottom: 3rem;
            background: linear-gradient(135deg, var(--orange), var(--purple));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 2rem;
        }

        .feature-card {
            background: var(--bg-card);
            border: 2px solid rgba(255,107,53,0.3);
            border-radius: 20px;
            padding: 2.5rem;
            transition: all 0.4s;
            transform-style: preserve-3d;
        }

        .feature-card:hover {
            transform: translateY(-15px) rotateY(5deg);
            border-color: var(--orange);
            box-shadow: 0 20px 60px rgba(255,107,53,0.4);
        }

        .feature-icon {
            font-size: 4rem;
            margin-bottom: 1.5rem;
            display: block;
            animation: icon-bounce 3s ease-in-out infinite;
        }

        @keyframes icon-bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }

        .feature-card h3 {
            font-size: 1.8rem;
            color: var(--orange);
            margin-bottom: 1rem;
        }

        .feature-card ul {
            color: var(--text-dim);
            list-style-position: inside;
            line-height: 2;
        }

        .feature-card ul li {
            padding-left: 0.5rem;
        }

        /* LOGIN PAGE */
        .login-page {
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 2rem;
            position: relative;
        }

        .back-button {
            position: fixed;
            top: 2rem;
            left: 2rem;
            padding: 1rem 2rem;
            background: var(--bg-card);
            border: 2px solid var(--orange);
            border-radius: 12px;
            color: var(--orange);
            font-weight: 700;
            cursor: pointer;
            transition: all 0.3s;
            z-index: 100;
            text-decoration: none;
            display: inline-block;
        }

        .back-button:hover {
            transform: translateX(-5px);
            box-shadow: 0 5px 20px rgba(255,107,53,0.5);
        }

        .login-card {
            background: var(--bg-card);
            border: 2px solid rgba(255,107,53,0.3);
            border-radius: 24px;
            padding: 4rem;
            max-width: 500px;
            width: 100%;
            text-align: center;
            box-shadow: 0 20px 60px rgba(0,0,0,0.5);
            animation: card-float 6s infinite;
            position: relative;
        }

        .login-card::before {
            content: '';
            position: absolute;
            top: -2px;
            left: -2px;
            right: -2px;
            bottom: -2px;
            background: linear-gradient(45deg, var(--orange), var(--purple), var(--orange));
            border-radius: 24px;
            z-index: -1;
            opacity: 0.5;
            filter: blur(20px);
            animation: border-glow 3s ease-in-out infinite;
        }

        @keyframes card-float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
        }

        @keyframes border-glow {
            0%, 100% { opacity: 0.5; }
            50% { opacity: 0.8; }
        }

        .login-logo {
            font-size: 6rem;
            margin-bottom: 2rem;
            animation: pulse-glow 3s ease-in-out infinite;
        }

        @keyframes pulse-glow {
            0%, 100% { filter: drop-shadow(0 0 20px rgba(255,107,53,0.8)); }
            50% { filter: drop-shadow(0 0 40px rgba(255,107,53,1)); }
        }

        .login-card h2 {
            font-size: 2.5rem;
            background: linear-gradient(135deg, var(--orange), var(--purple));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 1rem;
        }

        .login-card p {
            color: var(--text-dim);
            margin-bottom: 2rem;
            font-size: 1.1rem;
        }

        .discord-btn {
            width: 100%;
            padding: 1.5rem;
            background: #5865F2;
            border: none;
            border-radius: 12px;
            color: white;
            font-size: 1.2rem;
            font-weight: 700;
            cursor: pointer;
            transition: all 0.3s;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 1rem;
        }

        .discord-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 30px rgba(88,101,242,0.5);
        }

        /* DASHBOARD PAGE */
        .dashboard-page {
            min-height: 100vh;
            padding: 2rem;
        }

        .dash-header {
            max-width: 1600px;
            margin: 0 auto 3rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: var(--bg-card);
            padding: 2rem;
            border-radius: 20px;
            border: 2px solid rgba(255,107,53,0.3);
            box-shadow: 0 10px 40px rgba(0,0,0,0.5);
        }

        .user-info {
            display: flex;
            align-items: center;
            gap: 1.5rem;
        }

        .avatar {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            border: 3px solid var(--orange);
            box-shadow: 0 0 30px rgba(255,107,53,0.5);
            animation: avatar-glow 3s ease-in-out infinite;
        }

        @keyframes avatar-glow {
            0%, 100% { box-shadow: 0 0 30px rgba(255,107,53,0.5); }
            50% { box-shadow: 0 0 50px rgba(255,107,53,0.8); }
        }

        .user-name {
            font-size: 2rem;
            color: var(--orange);
        }

        .user-tag {
            color: var(--text-dim);
        }

        .logout-btn {
            padding: 1rem 2rem;
            background: linear-gradient(135deg, var(--purple), var(--dark-purple));
            border: none;
            border-radius: 12px;
            color: white;
            font-weight: 700;
            cursor: pointer;
            transition: all 0.3s;
        }

        .logout-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 30px rgba(106,27,154,0.5);
        }

        .servers-section {
            max-width: 1600px;
            margin: 0 auto;
        }

        .servers-title {
            font-size: 3rem;
            text-align: center;
            margin-bottom: 3rem;
            background: linear-gradient(135deg, var(--orange), var(--purple));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .servers-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(450px, 1fr));
            gap: 2rem;
        }

        .server-card {
            background: var(--bg-card);
            border: 2px solid rgba(255,107,53,0.2);
            border-radius: 20px;
            padding: 2rem;
            transition: all 0.4s;
            cursor: pointer;
            position: relative;
            transform-style: preserve-3d;
        }

        .server-card:hover {
            transform: translateY(-15px) rotateX(5deg) scale(1.02);
            border-color: var(--orange);
            box-shadow: 0 20px 60px rgba(255,107,53,0.4);
        }

        .bot-status {
            position: absolute;
            top: 1rem;
            right: 1rem;
            padding: 0.5rem 1rem;
            border-radius: 20px;
            font-size: 0.85rem;
            font-weight: 700;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .bot-in-server {
            background: rgba(0,255,65,0.2);
            color: var(--green);
            border: 1px solid var(--green);
        }

        .bot-not-in-server {
            background: rgba(255,56,56,0.2);
            color: var(--red);
            border: 1px solid var(--red);
        }

        .server-header {
            display: flex;
            align-items: center;
            gap: 1.5rem;
            margin-bottom: 1.5rem;
        }

        .server-icon {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            border: 3px solid var(--orange);
            box-shadow: 0 0 30px rgba(255,107,53,0.5);
            transition: all 0.3s;
        }

        .server-card:hover .server-icon {
            transform: rotate(360deg) scale(1.1);
        }

        .server-name {
            font-size: 1.8rem;
            color: var(--orange);
            font-weight: 700;
        }

        .server-role {
            color: var(--text-dim);
            font-size: 0.9rem;
        }

        .server-stats {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 1rem;
            margin-bottom: 1.5rem;
            padding: 1rem;
            background: rgba(255,107,53,0.05);
            border-radius: 12px;
        }

        .stat {
            text-align: center;
        }

        .stat-value {
            font-size: 1.5rem;
            font-weight: 700;
            background: linear-gradient(135deg, var(--orange), var(--purple));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .stat-label {
            color: var(--text-dim);
            font-size: 0.85rem;
        }

        .setup-status {
            padding: 1rem;
            border-radius: 12px;
            margin-bottom: 1.5rem;
            display: flex;
            align-items: center;
            gap: 1rem;
        }

        .setup-complete {
            background: rgba(0,255,65,0.1);
            border: 2px solid var(--green);
        }

        .setup-incomplete {
            background: rgba(255,56,56,0.1);
            border: 2px solid var(--red);
        }

        .setup-warning {
            background: rgba(255,215,0,0.1);
            border: 2px solid var(--yellow);
        }

        .setup-status-icon {
            font-size: 2rem;
        }

        .setup-status-text {
            flex: 1;
        }

        .setup-status-title {
            font-weight: 700;
            margin-bottom: 0.3rem;
        }

        .setup-status-desc {
            color: var(--text-dim);
            font-size: 0.9rem;
        }

        .action-buttons {
            display: flex;
            gap: 1rem;
        }

        .btn-manage {
            flex: 1;
            padding: 1rem;
            background: linear-gradient(135deg, var(--orange), var(--dark-orange));
            border: none;
            border-radius: 12px;
            color: white;
            font-weight: 700;
            cursor: pointer;
            transition: all 0.3s;
            font-size: 1rem;
        }

        .btn-manage:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 30px rgba(255,107,53,0.5);
        }

        .btn-manage:disabled {
            opacity: 0.5;
            cursor: not-allowed;
        }

        .btn-invite {
            flex: 1;
            padding: 1rem;
            background: linear-gradient(135deg, var(--purple), var(--dark-purple));
            border: none;
            border-radius: 12px;
            color: white;
            font-weight: 700;
            cursor: pointer;
            transition: all 0.3s;
            font-size: 1rem;
        }

        .btn-invite:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 30px rgba(106,27,154,0.5);
        }

        @media (max-width: 768px) {
            h1 { font-size: 3rem; }
            .tagline { font-size: 1.2rem; }
            .cta-buttons { flex-direction: column; align-items: center; }
            .features-grid, .servers-grid { grid-template-columns: 1fr; }
            .dash-header { flex-direction: column; gap: 1.5rem; text-align: center; }
            .user-info { flex-direction: column; }
            .server-stats { grid-template-columns: 1fr; }
            .action-buttons { flex-direction: column; }
            .back-button { top: 1rem; left: 1rem; padding: 0.8rem 1.5rem; }
        }
    </style>
</head>
<body>
    <div class="bg-3d"></div>
    <div class="orb orb1"></div>
    <div class="orb orb2"></div>

    <!-- INVITE PAGE -->
    <div id="invitePage" class="page active">
        <div class="invite-page">
            <div class="hero">
                <div class="logo">🎃</div>
                <h1>NovaFrame</h1>
                <p class="tagline">"Build, secure, and manage your Discord server instantly — no coding, no hassle."</p>
                
                <div class="info-banner">
                    <strong>⚡ Quick Start:</strong> Invite the bot → Run <code>/setup</code> in Discord → Complete setup in dashboard!
                </div>

                <div class="cta-buttons">
                    <a href="https://discord.com/oauth2/authorize?client_id=1436545256501018767&permissions=8&integration_type=0&scope=bot" 
                       class="btn btn-primary" target="_blank">
                        <span>🎃 Invite Bot to Server</span>
                    </a>
                    <button class="btn btn-secondary" onclick="showLogin()">
                        <span>👻 Open Dashboard</span>
                    </button>
                </div>
            </div>

            <div class="features">
                <h2 class="section-title">🌟 What NovaFrame Does</h2>
                <div class="features-grid">
                    <div class="feature-card">
                        <div class="feature-icon">🏗️</div>
                        <h3>Automated Server Building</h3>
                        <ul>
                            <li>Full server setup with /setup command</li>
                            <li>Creates proper channel structure automatically</li>
                            <li>Auto-generates required security channels</li>
                            <li>No coding knowledge required whatsoever</li>
                            <li>Modular and expandable architecture</li>
                        </ul>
                    </div>

                    <div class="feature-card">
                        <div class="feature-icon">🛡️</div>
                        <h3>Mandatory Security Compliance</h3>
                        <ul>
                            <li>Logs Channel for tracking all violations</li>
                            <li>Admin Notification Channel for staff alerts</li>
                            <li>Daily automated security logs</li>
                            <li>Built-in violation detection system</li>
                            <li>Cannot bypass setup requirements</li>
                        </ul>
                    </div>

                    <div class="feature-card">
                        <div class="feature-icon">🖥️</div>
                        <h3>Advanced Web Dashboard</h3>
                        <ul>
                            <li>Complete server overview & control panel</li>
                            <li>Add/remove channels, roles, and bots</li>
                            <li>View daily logs & violation reports</li>
                            <li>Privacy-isolated management sessions</li>
                            <li>Advanced features unlock after setup</li>
                        </ul>
                    </div>

                    <div class="feature-card">
                        <div class="feature-icon">⚙️</div>
                        <h3>Smart Setup System</h3>
                        <ul>
                            <li>/setup command initiates configuration</li>
                            <li>Detects missing required channels</li>
                            <li>Guides you through dashboard completion</li>
                            <li>Prevents incomplete server setups</li>
                            <li>Validates all security requirements</li>
                        </ul>
                    </div>

                    <div class="feature-card">
                        <div class="feature-icon">📊</div>
                        <h3>Server Analytics & Tracking</h3>
                        <ul>
                            <li>Track server configuration status</li>
                            <li>Monitor security compliance in real-time</li>
                            <li>View setup completion progress</li>
                            <li>Detailed violation tracking & history</li>
                            <li>Export reports and configurations</li>
                        </ul>
                    </div>

                    <div class="feature-card">
                        <div class="feature-icon">🔒</div>
                        <h3>Privacy & Best Practices</h3>
                        <ul>
                            <li>Isolated dashboard sessions per user</li>
                            <li>Enforces Discord server security standards</li>
                            <li>Protects against misconfiguration</li>
                            <li>No setup bypass allowed for safety</li>
                            <li>Built with Node.js for reliability</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- LOGIN PAGE -->
    <div id="loginPage" class="page">
        <a href="#" class="back-button" onclick="showInvite(); return false;">← Back to Home</a>
        <div class="login-page">
            <div class="login-card">
                <div class="login-logo">🎃</div>
                <h2>NovaFrame Dashboard</h2>
                <p>Login with Discord to manage your servers and complete server setup</p>
                <button class="discord-btn" onclick="loginDiscord()">
                    <span>💬</span>
                    <span>Login with Discord</span>
                </button>
            </div>
        </div>
    </div>

    <!-- DASHBOARD PAGE -->
    <div id="dashboardPage" class="page">
        <div class="dashboard-page">
            <div class="dash-header">
                <div class="user-info">
                    <img id="userAvatar" class="avatar" src="" alt="Avatar">
                    <div>
                        <div id="userName" class="user-name">Loading...</div>
                        <div id="userTag" class="user-tag"></div>
                    </div>
                </div>
                <button class="logout-btn" onclick="logout()">👻 Logout</button>
            </div>

            <div class="servers-section">
                <h2 class="servers-title">🎃 Your Servers</h2>
                <div id="serversList" class="servers-grid"></div>
            </div>
        </div>
    </div>

    <script>
        // CONFIGURATION
        const CLIENT_ID = '1436545256501018767';
        const REDIRECT_URI = window.location.origin + window.location.pathname;
        const BOT_INVITE_URL = `https://discord.com/oauth2/authorize?client_id=${CLIENT_ID}&permissions=8&integration_type=0&scope=bot`;

        // PAGE NAVIGATION
        function showPage(pageId) {
            document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
            document.getElementById(pageId).classList.add('active');
        }

        function showInvite() {
            showPage('invitePage');
        }

        function showLogin() {
            showPage('loginPage');
        }

        function showDashboard() {
            showPage('dashboardPage');
            loadDashboard();
        }

        // DISCORD OAUTH2 LOGIN - USING IMPLICIT FLOW (NO BACKEND NEEDED)
        function loginDiscord() {
            const state = btoa(Math.random().toString(36).substring(7));
            localStorage.setItem('oauth_state', state);
            
            // Use token response type for client-side only (implicit flow)
            const scopes = 'identify guilds';
            const authUrl = `https://discord.com/oauth2/authorize?client_id=${CLIENT_ID}&redirect_uri=${encodeURIComponent(REDIRECT_URI)}&response_type=token&scope=${encodeURIComponent(scopes)}&state=${state}`;
            window.location.href = authUrl;
        }

        // CHECK FOR OAUTH CALLBACK
        const urlParams = new URLSearchParams(window.location.search);
        const code = urlParams.get('code');
        const state = urlParams.get('state');

        if (code && state) {
            const savedState = localStorage.getItem('oauth_state');
            if (state === savedState) {
                // Store the code and redirect to get token via implicit flow
                // Using token instead of code for client-side flow
                localStorage.removeItem('oauth_state');
                window.history.replaceState({}, document.title, window.location.pathname);
                
                // For client-side only, use fragment identifier method
                alert('⚠️ To get real data:\n\n1. Change response_type=code to response_type=token in loginDiscord()\n2. Parse access_token from URL fragment\n3. Discord will return token directly\n\nOr store token manually in localStorage as "discord_access_token"');
                
                showInvite();
            }
        } 
        
        // Check for token in URL fragment (implicit flow)
        const fragment = new URLSearchParams(window.location.hash.substring(1));
        const accessToken = fragment.get('access_token');
        
        if (accessToken) {
            localStorage.setItem('discord_access_token', accessToken);
            window.history.replaceState({}, document.title, window.location.pathname);
            showDashboard();
        } else if (localStorage.getItem('discord_access_token')) {
            showDashboard();
        }

        // LOAD REAL DASHBOARD DATA FROM DISCORD API
        async function loadDashboard() {
            const token = localStorage.getItem('discord_access_token');
            if (!token) {
                showLogin();
                return;
            }

            try {
                // Fetch real user data
                const userResponse = await fetch('https://discord.com/api/v10/users/@me', {
                    headers: {
                        'Authorization': `Bearer ${token}`
                    }
                });

                if (!userResponse.ok) {
                    throw new Error('Failed to fetch user data');
                }

                const userData = await userResponse.json();
                
                // Set real user info
                document.getElementById('userName').textContent = userData.username;
                document.getElementById('userTag').textContent = userData.discriminator !== '0' ? `#${userData.discriminator}` : '';
                
                if (userData.avatar) {
                    document.getElementById('userAvatar').src = `https://cdn.discordapp.com/avatars/${userData.id}/${userData.avatar}.png?size=128`;
                } else {
                    const defaultAvatar = (parseInt(userData.id) >> 22) % 6;
                    document.getElementById('userAvatar').src = `https://cdn.discordapp.com/embed/avatars/${defaultAvatar}.png`;
                }

                // Fetch real guilds
                const guildsResponse = await fetch('https://discord.com/api/v10/users/@me/guilds', {
                    headers: {
                        'Authorization': `Bearer ${token}`
                    }
                });

                if (!guildsResponse.ok) {
                    throw new Error('Failed to fetch guilds');
                }

                const guilds = await guildsResponse.json();

                // Filter guilds where user has MANAGE_GUILD or ADMINISTRATOR permission
                const manageableGuilds = guilds.filter(guild => {
                    const permissions = BigInt(guild.permissions);
                    const MANAGE_GUILD = BigInt(0x20);
                    const ADMINISTRATOR = BigInt(0x8);
                    return guild.owner || (permissions & (MANAGE_GUILD | ADMINISTRATOR)) !== BigInt(0);
                });

                // Check which servers have the bot
                await checkBotPresence(manageableGuilds);

            } catch (error) {
                console.error('Dashboard load error:', error);
                alert('Failed to load dashboard. Your session may have expired. Please login again.');
                localStorage.removeItem('discord_access_token');
                showInvite();
            }
        }

        // CHECK BOT PRESENCE IN SERVERS
        async function checkBotPresence(guilds) {
            const serversList = document.getElementById('serversList');
            
            if (guilds.length === 0) {
                serversList.innerHTML = `
                    <div style="grid-column: 1/-1; text-align: center; padding: 4rem; background: var(--bg-card); border-radius: 20px; border: 2px solid rgba(255,107,53,0.3);">
                        <div style="font-size: 5rem; margin-bottom: 1rem;">😱</div>
                        <h3 style="font-size: 2rem; color: var(--orange); margin-bottom: 1rem;">No Manageable Servers</h3>
                        <p style="color: var(--text-dim); margin-bottom: 2rem;">You don't have manage permissions in any servers.</p>
                        <a href="${BOT_INVITE_URL}" class="btn-invite" target="_blank" style="display: inline-block; padding: 1rem 2rem; background: linear-gradient(135deg, var(--orange), var(--dark-orange)); color: white; text-decoration: none; border-radius: 12px; font-weight: 700;">
                            🤖 Invite NovaFrame to Your Server
                        </a>
                    </div>
                `;
                return;
            }

            // For each guild, check if bot is present
            const serversWithBotStatus = await Promise.all(guilds.map(async (guild) => {
                try {
                    // Try to fetch guild info - this will fail if bot is not in server
                    const guildResponse = await fetch(`https://discord.com/api/v10/guilds/${guild.id}`, {
                        headers: {
                            'Authorization': `MTQzNjU0NTI1NjUwMTAxODc2Nw.GGe1Io.GNyKNax_7Wr7D5Y8Bz92sWZ_44UbWnyVJGqu0I` // REPLACE THIS WITH YOUR ACTUAL BOT TOKEN
                        }
                    });

                    const botInServer = guildResponse.ok;
                    
                    // If bot is in server, check for setup completion
                    let setupComplete = false;
                    let logsChannel = false;
                    let adminChannel = false;

                    if (botInServer) {
                        // Fetch channels to check for logs and admin channels
                        const channelsResponse = await fetch(`https://discord.com/api/v10/guilds/${guild.id}/channels`, {
                            headers: {
                                'Authorization': `MTQzNjU0NTI1NjUwMTAxODc2Nw.GGe1Io.GNyKNax_7Wr7D5Y8Bz92sWZ_44UbWnyVJGqu0I` // REPLACE THIS WITH YOUR ACTUAL BOT TOKEN
                            }
                        });

                        if (channelsResponse.ok) {
                            const channels = await channelsResponse.json();
                            
                            // Check for logs channel (you can customize the name)
                            logsChannel = channels.some(ch => 
                                ch.name.toLowerCase().includes('log') || 
                                ch.name.toLowerCase().includes('audit') ||
                                ch.topic?.toLowerCase().includes('novaframe-logs')
                            );

                            // Check for admin notification channel
                            adminChannel = channels.some(ch => 
                                ch.name.toLowerCase().includes('admin') || 
                                ch.name.toLowerCase().includes('staff') ||
                                ch.topic?.toLowerCase().includes('novaframe-admin')
                            );

                            setupComplete = logsChannel && adminChannel;
                        }
                    }

                    return {
                        id: guild.id,
                        name: guild.name,
                        icon: guild.icon,
                        members: guild.approximate_member_count || 0,
                        role: guild.owner ? 'Owner' : 'Admin',
                        botInServer,
                        setupComplete,
                        logsChannel,
                        adminChannel
                    };
                } catch (error) {
                    // If error, assume bot is not in server
                    return {
                        id: guild.id,
                        name: guild.name,
                        icon: guild.icon,
                        members: guild.approximate_member_count || 0,
                        role: guild.owner ? 'Owner' : 'Admin',
                        botInServer: false,
                        setupComplete: false,
                        logsChannel: false,
                        adminChannel: false
                    };
                }
            }));

            // Render server cards with real data
            serversList.innerHTML = serversWithBotStatus.map(s => renderServerCard(s)).join('');
        }

        // RENDER SERVER CARD
        function renderServerCard(server) {
            // Get real server icon or use placeholder
            const iconUrl = server.icon 
                ? `https://cdn.discordapp.com/icons/${server.id}/${server.icon}.png?size=128`
                : `data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Ccircle cx='50' cy='50' r='45' fill='%23ff6b35'/%3E%3Ctext y='75' font-size='50' text-anchor='middle' x='50' fill='white'%3E${server.name.charAt(0)}%3C/text%3E%3C/svg%3E`;

            // If bot is not in server
            if (!server.botInServer) {
                return `
                    <div class="server-card">
                        <div class="bot-status bot-not-in-server">
                            <span>⚠️</span>
                            <span>Bot Not Added</span>
                        </div>
                        <div class="server-header">
                            <img class="server-icon" src="${iconUrl}" alt="${server.name}">
                            <div>
                                <div class="server-name">${server.name}</div>
                                <div class="server-role">${server.role} • ${server.members.toLocaleString()} members</div>
                            </div>
                        </div>
                        <div class="setup-status setup-warning">
                            <div class="setup-status-icon">⚠️</div>
                            <div class="setup-status-text">
                                <div class="setup-status-title">NovaFrame Not Invited</div>
                                <div class="setup-status-desc">Add the bot to this server to begin setup and unlock all features</div>
                            </div>
                        </div>
                        <div class="action-buttons">
                            <button class="btn-invite" onclick="inviteBotToServer('${server.id}', '${server.name}')">
                                🤖 Invite NovaFrame to Server
                            </button>
                        </div>
                    </div>
                `;
            }

            // Bot is in server
            let statusHtml = '';
            let actionButton = '';

            if (server.setupComplete) {
                // Setup is complete
                statusHtml = `
                    <div class="setup-status setup-complete">
                        <div class="setup-status-icon">✅</div>
                        <div class="setup-status-text">
                            <div class="setup-status-title">Setup Complete</div>
                            <div class="setup-status-desc">All security features active. Server is fully configured and protected.</div>
                        </div>
                    </div>
                `;
                actionButton = `
                    <button class="btn-manage" onclick="manageServer('${server.name}', ${server.setupComplete}, '${server.id}')">
                        ⚙️ Manage Server Dashboard
                    </button>
                `;
            } else {
                // Setup is incomplete
                const missingItems = [];
                if (!server.logsChannel) missingItems.push('Logs Channel');
                if (!server.adminChannel) missingItems.push('Admin Notification Channel');
                
                statusHtml = `
                    <div class="setup-status setup-incomplete">
                        <div class="setup-status-icon">❌</div>
                        <div class="setup-status-text">
                            <div class="setup-status-title">Setup Required</div>
                            <div class="setup-status-desc">Missing: ${missingItems.join(', ')}. Run /setup in Discord to continue.</div>
                        </div>
                    </div>
                `;
                actionButton = `
                    <button class="btn-manage" onclick="manageServer('${server.name}', ${server.setupComplete}, '${server.id}')">
                        🔧 Complete Setup in Dashboard
                    </button>
                `;
            }

            return `
                <div class="server-card">
                    <div class="bot-status bot-in-server">
                        <span>✅</span>
                        <span>Bot Active</span>
                    </div>
                    <div class="server-header">
                        <img class="server-icon" src="${iconUrl}" alt="${server.name}">
                        <div>
                            <div class="server-name">${server.name}</div>
                            <div class="server-role">${server.role} • ${server.members.toLocaleString()} members</div>
                        </div>
                    </div>
                    <div class="server-stats">
                        <div class="stat">
                            <div class="stat-value">${server.setupComplete ? '✅' : '⚠️'}</div>
                            <div class="stat-label">Setup Status</div>
                        </div>
                        <div class="stat">
                            <div class="stat-value">${server.logsChannel ? '✅' : '❌'}</div>
                            <div class="stat-label">Logs Channel</div>
                        </div>
                        <div class="stat">
                            <div class="stat-value">${server.adminChannel ? '✅' : '❌'}</div>
                            <div class="stat-label">Admin Channel</div>
                        </div>
                    </div>
                    ${statusHtml}
                    <div class="action-buttons">
                        ${actionButton}
                    </div>
                </div>
            `;
        }

        // INVITE BOT TO SPECIFIC SERVER
        function inviteBotToServer(serverId, serverName) {
            const inviteUrl = `${BOT_INVITE_URL}&guild_id=${serverId}`;
            
            // Open invite in new tab
            const inviteWindow = window.open(inviteUrl, '_blank');
            
            // Show confirmation message
            setTimeout(() => {
                if (confirm(`Opening Discord to invite NovaFrame to "${serverName}".\n\nAfter adding the bot:\n1. Go to your server\n2. Run the /setup command\n3. Return here to complete setup in the dashboard\n\nClick OK to refresh the dashboard after adding the bot.`)) {
                    loadDashboard();
                }
            }, 1000);
        }

        // MANAGE SERVER (OPEN ADVANCED DASHBOARD)
        function manageServer(serverName, isSetupComplete, serverId) {
            if (!isSetupComplete) {
                // Show setup instructions
                alert(`🔧 Complete Setup for "${serverName}"\n\n` +
                    `REQUIRED STEPS:\n\n` +
                    `1. Open Discord and go to your server\n` +
                    `2. Run the command: /setup\n` +
                    `3. NovaFrame will check your configuration\n\n` +
                    `REQUIRED CHANNELS:\n` +
                    `• Logs Channel - Tracks violations, bot events, and moderation\n` +
                    `• Admin Notification Channel - Alerts staff about issues\n\n` +
                    `/setup will create these channels if missing.\n\n` +
                    `AFTER SETUP COMPLETES:\n` +
                    `✅ Daily automated security logs\n` +
                    `✅ Violation detection system\n` +
                    `✅ Full server analytics\n` +
                    `✅ Advanced security dashboard\n` +
                    `✅ Channel & role management\n` +
                    `✅ Configuration export\n\n` +
                    `Your server will be fully secured and compliant!`);
            } else {
                // Show advanced management options
                alert(`⚙️ Advanced Dashboard for "${serverName}"\n\n` +
                    `AVAILABLE FEATURES:\n\n` +
                    `📊 SERVER OVERVIEW\n` +
                    `• View complete server configuration\n` +
                    `• Monitor security compliance status\n` +
                    `• Track daily activity & statistics\n\n` +
                    `🛡️ SECURITY & LOGS\n` +
                    `• View daily automated security logs\n` +
                    `• Check violation reports & history\n` +
                    `• Configure alert thresholds\n` +
                    `• Export security reports\n\n` +
                    `⚙️ SERVER MANAGEMENT\n` +
                    `• Add/remove channels and categories\n` +
                    `• Manage roles and permissions\n` +
                    `• Configure bot permissions\n` +
                    `• Invite additional bots\n\n` +
                    `📈 ANALYTICS\n` +
                    `• Member growth tracking\n` +
                    `• Activity heatmaps\n` +
                    `• Channel usage statistics\n` +
                    `• Moderation action logs\n\n` +
                    `All features are unlocked! ✅`);
            }
        }

        // LOGOUT
        function logout() {
            if (confirm('Are you sure you want to logout?')) {
                localStorage.removeItem('discord_access_token');
                localStorage.removeItem('oauth_state');
                showInvite();
            }
        }

        // INIT: Check authentication on page load
        window.addEventListener('DOMContentLoaded', () => {
            console.log('NovaFrame Dashboard Loaded');
            console.log('⚠️ IMPORTANT: Replace YOUR_BOT_TOKEN_HERE with your actual bot token in the code!');
            console.log('Bot Client ID:', CLIENT_ID);
            console.log('Using Discord OAuth2 Implicit Flow (no backend required)');
        });
    </script>
</body>
</html>
