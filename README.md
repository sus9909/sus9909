## Hi there 👋

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
<style id="ghpc-greeting-style">
.ghpc-greeting {
    color: #00ffff;
    font-size: 16px;
    margin: 15px 0;
    padding: 10px;
    background: rgba(0, 255, 255, 0.1);
    border-left: 3px solid #00ffff;
    border-radius: 5px;
    animation: fadeIn 1s ease-in;
}

@keyframes fadeIn {
    from { 
        opacity: 0; 
        transform: translateY(-10px); 
    }
    to { 
        opacity: 1; 
        transform: translateY(0); 
    }
}
</style>

<script id="ghpc-greeting-script">
// Wait for page to fully load
setTimeout(() => {
    // Get current hour
    const hour = new Date().getHours();
    let greeting = 'Hello';

    if (hour < 12) greeting = 'Good Morning';
    else if (hour < 18) greeting = 'Good Afternoon';
    else greeting = 'Good Evening';

    // Try multiple possible locations for the greeting
    const possible_locations = [
        document.querySelector('.js-profile-editable-area'),
        document.querySelector('.user-profile-bio'),
        document.querySelector('[data-bio-text]'),
        document.querySelector('.p-note'),
        document.querySelector('.Layout-sidebar'),
        document.querySelector('article.markdown-body')
    ];

    // Find the first available location
    let target = null;
    for (const location of possible_locations) {
        if (location) {
            target = location;
            break;
        }
    }

    if (target) {
        // Create greeting element
        const greeting_element = document.createElement('div');
        greeting_element.className = 'ghpc-greeting';
        greeting_element.innerHTML = `
            <strong>${greeting}!</strong> Welcome to my profile 👋
            <br>
            <small>Local time: ${new Date().toLocaleTimeString()}</small>
        `;
        
        // Insert at the beginning of the target
        target.insertBefore(greeting_element, target.firstChild);
        
        console.log('%c[GHPC]%c ✓ Greeting added successfully!', 
            'color: #238636; font-weight: bold;', 
            'color: #238636;');
    } else {
        console.warn('%c[GHPC]%c Could not find suitable location for greeting', 
            'color: #bf8700; font-weight: bold;', 
            'color: #bf8700;');
        
        // Fallback: add to body
        const greeting_element = document.createElement('div');
        greeting_element.className = 'ghpc-greeting';
        greeting_element.innerHTML = `<strong>${greeting}!</strong> Welcome to my profile 👋`;
        greeting_element.style.cssText += `
            position: fixed;
            top: 20px;
            right: 20px;
            z-index: 9999;
            max-width: 300px;
        `;
        document.body.appendChild(greeting_element);
    }
}, 1500);  // Wait 1.5 seconds for GitHub to load
</script>
GHPC:END-->
