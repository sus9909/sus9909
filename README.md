## Hi there 👋


**sus9909/sus9909** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!--GHPC:START
<style>
/* === EXTREME GITHUB PROFILE TRANSFORMATION === */

/* Full page background with meme image */
body::before {
    content: '';
    position: fixed;
    top: 0;
    left: 0;
    width: 100vw;
    height: 100vh;
    background-image: url('https://bigrat.monster/media/bigrat.jpg');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    opacity: 0.3;
    z-index: -1;
    pointer-events: none;
}

/* Dark overlay for readability */
body::after {
    content: '';
    position: fixed;
    top: 0;
    left: 0;
    width: 100vw;
    height: 100vh;
    background: radial-gradient(circle at center, rgba(0,0,0,0.5), rgba(0,0,0,0.8));
    z-index: -1;
    pointer-events: none;
}

/* Glassmorphism effect on main container */
.container-xl,
.Layout-main,
.Layout-sidebar {
    background: rgba(255, 255, 255, 0.05) !important;
    backdrop-filter: blur(10px) !important;
    border: 1px solid rgba(255, 255, 255, 0.1) !important;
    border-radius: 15px !important;
    box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.37) !important;
}

/* Neon glow username and display name */
.p-nickname,
.p-name,
.vcard-username,
h1.vcard-names span,
.vcard-names {
    animation: rainbow-glow 3s ease-in-out infinite !important;
    font-weight: bold !important;
    font-size: 1.5em !important;
    text-transform: uppercase !important;
    letter-spacing: 3px !important;
}

@keyframes rainbow-glow {
    0% {
        text-shadow: 
            0 0 10px #ff00ff,
            0 0 20px #ff00ff,
            0 0 30px #ff00ff,
            0 0 40px #ff00ff;
        color: #ff00ff;
    }
    25% {
        text-shadow: 
            0 0 10px #00ffff,
            0 0 20px #00ffff,
            0 0 30px #00ffff,
            0 0 40px #00ffff;
        color: #00ffff;
    }
    50% {
        text-shadow: 
            0 0 10px #ffff00,
            0 0 20px #ffff00,
            0 0 30px #ffff00,
            0 0 40px #ffff00;
        color: #ffff00;
    }
    75% {
        text-shadow: 
            0 0 10px #00ff00,
            0 0 20px #00ff00,
            0 0 30px #00ff00,
            0 0 40px #00ff00;
        color: #00ff00;
    }
    100% {
        text-shadow: 
            0 0 10px #ff00ff,
            0 0 20px #ff00ff,
            0 0 30px #ff00ff,
            0 0 40px #ff00ff;
        color: #ff00ff;
    }
}

/* Avatar with rotating border */
.avatar,
.avatar-user {
    border: 3px solid transparent !important;
    border-radius: 50% !important;
    animation: rotate-border 3s linear infinite, float-avatar 3s ease-in-out infinite !important;
    background: linear-gradient(white, white) padding-box,
                linear-gradient(45deg, #ff00ff, #00ffff, #ffff00, #00ff00) border-box !important;
    box-shadow: 0 0 30px rgba(255, 0, 255, 0.8) !important;
}

@keyframes rotate-border {
    0% { filter: hue-rotate(0deg); }
    100% { filter: hue-rotate(360deg); }
}

@keyframes float-avatar {
    0%, 100% { transform: translateY(0px); }
    50% { transform: translateY(-10px); }
}

/* Neon buttons */
button,
.btn,
a.btn {
    background: linear-gradient(45deg, #ff00ff, #00ffff) !important;
    border: none !important;
    color: white !important;
    text-shadow: 0 0 10px rgba(255,255,255,0.8) !important;
    box-shadow: 0 0 20px rgba(255, 0, 255, 0.5) !important;
    transition: all 0.3s ease !important;
    position: relative !important;
    overflow: hidden !important;
}

button:hover,
.btn:hover {
    transform: scale(1.05) !important;
    box-shadow: 0 0 30px rgba(255, 0, 255, 0.8) !important;
}

button::before,
.btn::before {
    content: '';
    position: absolute;
    top: 50%;
    left: 50%;
    width: 0;
    height: 0;
    border-radius: 50%;
    background: rgba(255, 255, 255, 0.3);
    transform: translate(-50%, -50%);
    transition: width 0.6s, height 0.6s;
}

button:hover::before,
.btn:hover::before {
    width: 300px;
    height: 300px;
}

/* Pinned repos with glow effect */
.pinned-item-list-item {
    background: linear-gradient(135deg, rgba(255,0,255,0.1), rgba(0,255,255,0.1)) !important;
    border: 2px solid rgba(255, 0, 255, 0.3) !important;
    border-radius: 10px !important;
    transition: all 0.3s ease !important;
    animation: pulse-glow 2s ease-in-out infinite !important;
}

.pinned-item-list-item:hover {
    transform: translateY(-5px) scale(1.02) !important;
    box-shadow: 0 10px 30px rgba(255, 0, 255, 0.5) !important;
    border-color: rgba(255, 0, 255, 0.8) !important;
}

@keyframes pulse-glow {
    0%, 100% { box-shadow: 0 0 10px rgba(255, 0, 255, 0.3); }
    50% { box-shadow: 0 0 20px rgba(0, 255, 255, 0.5); }
}

/* Contribution graph rainbow colors */
.ContributionCalendar-day[data-level="0"] { fill: #1a1a2e !important; }
.ContributionCalendar-day[data-level="1"] { fill: #ff00ff !important; }
.ContributionCalendar-day[data-level="2"] { fill: #00ffff !important; }
.ContributionCalendar-day[data-level="3"] { fill: #ffff00 !important; }
.ContributionCalendar-day[data-level="4"] { fill: #00ff00 !important; }

.ContributionCalendar-day:hover {
    stroke: white !important;
    stroke-width: 2px !important;
    filter: brightness(1.5) !important;
}

/* Animated gradient text for headings */
h2, h3, h4 {
    background: linear-gradient(90deg, #ff00ff, #00ffff, #ffff00, #00ff00, #ff00ff);
    background-size: 200% auto;
    color: transparent !important;
    background-clip: text !important;
    -webkit-background-clip: text !important;
    -webkit-text-fill-color: transparent !important;
    animation: gradient-shift 3s linear infinite !important;
    font-weight: bold !important;
}

@keyframes gradient-shift {
    0% { background-position: 0% center; }
    100% { background-position: 200% center; }
}

/* Repo cards with hover effects */
.repo {
    background: rgba(255, 255, 255, 0.03) !important;
    border: 1px solid rgba(255, 0, 255, 0.2) !important;
    border-radius: 10px !important;
    transition: all 0.3s ease !important;
}

.repo:hover {
    background: rgba(255, 0, 255, 0.1) !important;
    border-color: rgba(255, 0, 255, 0.6) !important;
    transform: translateX(5px) !important;
    box-shadow: -5px 0 15px rgba(255, 0, 255, 0.3) !important;
}

/* Scrollbar customization */
::-webkit-scrollbar {
    width: 12px;
}

::-webkit-scrollbar-track {
    background: linear-gradient(180deg, #1a1a2e, #16213e);
}

::-webkit-scrollbar-thumb {
    background: linear-gradient(180deg, #ff00ff, #00ffff);
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(255, 0, 255, 0.5);
}

::-webkit-scrollbar-thumb:hover {
    background: linear-gradient(180deg, #ffff00, #00ff00);
    box-shadow: 0 0 20px rgba(255, 255, 0, 0.8);
}

/* Link hover effects */
a {
    transition: all 0.3s ease !important;
    position: relative !important;
}

a:hover {
    color: #ff00ff !important;
    text-shadow: 0 0 10px rgba(255, 0, 255, 0.8) !important;
}

/* Stars and followers with glow */
.Counter {
    background: linear-gradient(45deg, #ff00ff, #00ffff) !important;
    color: white !important;
    border: none !important;
    box-shadow: 0 0 10px rgba(255, 0, 255, 0.5) !important;
}

/* Profile README styling */
article.markdown-body {
    background: rgba(0, 0, 0, 0.3) !important;
    border: 1px solid rgba(255, 0, 255, 0.3) !important;
    border-radius: 10px !important;
    padding: 20px !important;
}

/* Add retro scanlines effect */
body::before {
    content: '';
    position: fixed;
    top: 0;
    left: 0;
    width: 100vw;
    height: 100vh;
    background: repeating-linear-gradient(
        0deg,
        rgba(0, 0, 0, 0.15),
        rgba(0, 0, 0, 0.15) 1px,
        transparent 1px,
        transparent 2px
    );
    pointer-events: none;
    z-index: 9998;
    animation: scanlines 8s linear infinite;
}

@keyframes scanlines {
    0% { transform: translateY(0); }
    100% { transform: translateY(10px); }
}

/* Cursor trail particle styling */
.cursor-particle {
    position: fixed;
    pointer-events: none;
    font-size: 20px;
    font-weight: bold;
    z-index: 9999;
    animation: fall-and-fade 2s ease-out forwards;
    text-shadow: 0 0 10px currentColor;
}

@keyframes fall-and-fade {
    0% {
        opacity: 1;
        transform: translateY(0) rotate(0deg) scale(1);
    }
    100% {
        opacity: 0;
        transform: translateY(100px) rotate(360deg) scale(0.5);
    }
}

/* Matrix rain effect on sidebar */
.Layout-sidebar::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: 
        linear-gradient(transparent 50%, rgba(0, 255, 0, 0.1) 50%);
    background-size: 100% 4px;
    animation: matrix-rain 0.5s linear infinite;
    pointer-events: none;
    opacity: 0.3;
}

@keyframes matrix-rain {
    0% { background-position: 0 0; }
    100% { background-position: 0 4px; }
}
</style>
GHPC:END-->
