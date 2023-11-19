# Portfolio

## Overview
This is a portfolio website to display some services of the company "Something something" This is currently under development. We will keep on adding those featurers in readme that we add on the website. 


## Components

### Header
Header is the component at the top of the website. It contains logo, name and navigation bar. 
Here is the code for the header we have:
```html
<header>
        <div class="logo name">
            <a href="./index.html">
                <img src="IMG\Screenshot 2023-09-22 113811.jpg"
                alt="Screen Image">
            </a>
            <p class="name">
                <span class="coder-text">Tanya</span>
                <span class="academy-text">Chukau</span>
            </p>
        </div>

        <nav id="nav-items">
            <a href="./index.html">Home</a>
            <a href=".pages/about.html">About</a>
            <a href=".pages/contact.html">Contact</a>
        </nav>
   </header>
```

### Footer
Footer has social media links, and some contact and address information.
Here is the code that we have for footer:
```html
<footer>
    <div class="social-media">
        <a href="https://www.facebook.com" target="_blank">
            <i class="fa-brands fa-facebook" ></i>
        </a>
        <a href="https://www.github.com" target="_blank">
            <i class="fa-brands fa-github"></i>
        </a>
        <a href="https://www.linkedin.com" target="_blank">
            <i class="fa-brands fa-linkedin"></i>
        </a>
    </div>
    <div class="info">
        <p>Contact: 0404040404</p>
        <p>Address: 123 Fake Street Springdfield</p>
    </div>
</footer>
```