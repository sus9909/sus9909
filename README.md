## Hi there 👋
Here are some ideas to get you started:
- 🔭 I'm currently working on ...
- 🌱 I'm currently learning ...
- 👯 I'm looking to collaborate on ...
- 🤔 I'm looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
- 
<!--GHPC:START
<style>
/* Shared image styling */
.ghpc-video-bg {
    position: absolute;
    inset: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
    pointer-events: none;
    z-index: 999;
}

/* Ensure targets can contain the image */
.logged-in.env-production.page-responsive.page-profile,
.Box-body.p-4,
.Box.pinned-item-list-item.d-flex.p-3.width-full.public.source,
.ajax-pagination-btn.btn.width-full.f6.mt-0.py-2.contribution-activity-show-more,
.position-relative.d-inline-block.col-2.col-md-12.mr-3.mr-md-0.flex-shrink-0,
.AppHeader-logo.ml-1,
input[type="submit"][value="Follow"].btn.btn-block {
    position: relative;
    overflow: hidden;
}

/* Keep content above image */
.logged-in.env-production.page-responsive.page-profile > *,
.Box-body.p-4 > *,
.Box.pinned-item-list-item.d-flex.p-3.width-full.public.source > *,
.ajax-pagination-btn.btn.width-full.f6.mt-0.py-2.contribution-activity-show-more > *,
.position-relative.d-inline-block.col-2.col-md-12.mr-3.mr-md-0.flex-shrink-0 > *,
.AppHeader-logo.ml-1 > *,
input[type="submit"][value="Follow"].btn.btn-block > * {
    position: relative;
    z-index: 1000;
}

/* Special handling for follow button text */
input[type="submit"][value="Follow"].btn.btn-block {
    color: white;
    text-shadow: 0 0 5px rgba(0,0,0,0.8);
    font-weight: bold;
}
</style>
<script>
(function () {
    const IMAGE_SRC = "https://raw.githubusercontent.com/sus9909/sus9909/refs/heads/main/ahem.gif";
    
    const targets = document.querySelectorAll(
        ".logged-in.env-production.page-responsive.page-profile," +
        ".Box-body.p-4," +
        ".Box.pinned-item-list-item.d-flex.p-3.width-full.public.source," +
        ".ajax-pagination-btn.btn.width-full.f6.mt-0.py-2.contribution-activity-show-more," +
        ".position-relative.d-inline-block.col-2.col-md-12.mr-3.mr-md-0.flex-shrink-0," +
        ".AppHeader-logo.ml-1," +
        'input[type="submit"][value="Follow"].btn.btn-block'
    );
    
    targets.forEach(el => {
        if (el.querySelector(".ghpc-video-bg")) return;
        
        const img = document.createElement("img");
        img.className = "ghpc-video-bg";
        img.src = IMAGE_SRC;
        el.prepend(img);
        
        // For input elements, we need to wrap them since they can't have children
        if (el.tagName === 'INPUT') {
            const wrapper = document.createElement('div');
            wrapper.style.cssText = 'position: relative; display: inline-block; overflow: hidden;';
            el.parentNode.insertBefore(wrapper, el);
            wrapper.appendChild(el);
            wrapper.insertBefore(img, el);
        }
    });
})();
</script>
GHPC:END-->
