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
/* Glowing username and display name */
.p-nickname,
.p-name,
.vcard-username,
h1.vcard-names span {
    animation: username-glow 2s ease-in-out infinite;
    text-shadow: 
        0 0 10px #00ffff,
        0 0 20px #00ffff,
        0 0 30px #00ffff,
        0 0 40px #00d4ff;
}

@keyframes username-glow {
    0%, 100% {
        text-shadow: 
            0 0 10px #00ffff,
            0 0 20px #00ffff,
            0 0 30px #00ffff,
            0 0 40px #00d4ff;
    }
    50% {
        text-shadow: 
            0 0 20px #00ffff,
            0 0 30px #00ffff,
            0 0 40px #00ffff,
            0 0 50px #00d4ff,
            0 0 60px #0099ff;
    }
}

/* Cursor trail particle styling */
.cursor-particle {
    position: fixed;
    pointer-events: none;
    font-size: 14px;
    font-weight: bold;
    z-index: 9999;
    animation: fall-and-fade 2s ease-out forwards;
}

@keyframes fall-and-fade {
    0% {
        opacity: 1;
        transform: translateY(0) rotate(0deg);
    }
    100% {
        opacity: 0;
        transform: translateY(100px) rotate(360deg);
    }
}
</style>

<script>
// Cursor particle trail effect
const particles = ['+', 'x', '*'];
let lastParticleTime = 0;
const particleDelay = 50; // milliseconds between particles

document.addEventListener('mousemove', (e) => {
    const now = Date.now();
    
    // Throttle particle creation
    if (now - lastParticleTime < particleDelay) return;
    lastParticleTime = now;
    
    // Create particle
    const particle = document.createElement('div');
    particle.className = 'cursor-particle';
    particle.textContent = particles[Math.floor(Math.random() * particles.length)];
    
    // Random color from cyan/blue palette
    const colors = ['#00ffff', '#00d4ff', '#0099ff', '#66ffff', '#33ccff'];
    particle.style.color = colors[Math.floor(Math.random() * colors.length)];
    
    // Position at cursor with slight random offset
    particle.style.left = (e.pageX + (Math.random() * 20 - 10)) + 'px';
    particle.style.top = (e.pageY + (Math.random() * 20 - 10)) + 'px';
    
    document.body.appendChild(particle);
    
    // Remove particle after animation
    setTimeout(() => {
        particle.remove();
    }, 2000);
});
</script>
GHPC:END-->
