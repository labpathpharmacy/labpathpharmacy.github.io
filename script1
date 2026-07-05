function closeAllSubMenus() {
    const subMenus = document.querySelectorAll('.sb2, .sb');
    subMenus.forEach(menu => menu.classList.remove('show-menu'));
    const mb2 = document.getElementById('mb2');
    const mb = document.getElementById('mb');
    if (mb2) {
        mb2.innerText = 'Reports';
        mb2.style.backgroundColor = '';
        mb2.style.color = '';
    }
    if (mb) {
        mb.innerText = 'Contact';
        mb.style.backgroundColor = '';
        mb.style.color = '';
    }
}
function toggleMenu3() {
    event.preventDefault(); 
    const menu = document.querySelector('.mc3');
    const button = document.getElementById('mb3');
    if (menu.classList.contains('show-menu')) {
        closeAllSubMenus();
    }
    menu.classList.toggle('show-menu');
    toggleButtonText(button,'☰ Menu');
}
function toggleMenu4() {
    event.preventDefault(); 
    const menu = document.querySelector('.mc3');
    const button = document.getElementById('mb3');
    if (menu.classList.contains('show-menu')) {
        closeAllSubMenus();
    }
    menu.classList.toggle('show-menu');
    toggleButtonText(button,'☰ 메뉴');
}
function toggleMenu2() {
    event.preventDefault();
    event.stopPropagation();
    const menu = document.getElementById('ddM2');
    const button = document.getElementById('mb2');
    if (!menu.classList.contains('show-menu')) {
        closeAllSubMenus();
        menu.classList.add('show-menu');
        button.innerText = button.getAttribute('data-text-open');
        button.style.backgroundColor = '#333333';
        button.style.color = '#ffffff';
    } else {
        menu.classList.remove('show-menu');
        button.innerText = 'Reports';
        button.style.backgroundColor = '';
        button.style.color = '';
    }
}
function toggleMenu() {
    event.preventDefault();
    event.stopPropagation();
    const menu = document.getElementById('ddM');
    const button = document.getElementById('mb');
    if (!menu.classList.contains('show-menu')) {
        closeAllSubMenus();
        menu.classList.add('show-menu');
        button.innerText = button.getAttribute('data-text-open');
        button.style.backgroundColor = '#333333';
        button.style.color = '#ffffff';
    } else {
        menu.classList.remove('show-menu');
        button.innerText = 'Contact';
        button.style.backgroundColor = '';
        button.style.color = '';
    }
}
function toggleButtonText(button, originalText) {
    const openText = button.getAttribute('data-text-open');
    if (button.innerText === originalText) {
        button.innerText = openText;
    } else {
        button.innerText = originalText;
    }
}
window.onclick = function(event) {
    if (!event.target.matches('.bc button')) {
        const menu3 = document.querySelector('.mc3');
        if (menu3) menu3.classList.remove('show-menu');
        const button3 = document.getElementById('mb3');
        if (button3) button3.innerText = '☰ Menu';
        closeAllSubMenus();
document.addEventListener("DOMContentLoaded", function() {
    const popup = document.getElementById("pop");
    const closeBtn = document.getElementById("end");
    popup.classList.add("show");
    closeBtn.addEventListener("click", function() {
        popup.classList.remove("show");
    });
