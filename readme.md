# Portfolio

## Overview

This is a portfolio website to show some services provided by the company "Some company name". This is currently under development. We will keep on adding new features in the website and readme as we move further.

## Components

### Header

Header has logo and name of the company along with the navigation bar to different pages such as Home, About, Services and Contact. 

```html
<header>
    <div class="logo-name">
        <img src="https://coderacademy.edu.au/images/footerLogo.png">
        <p class="name">
            <span class="company-text">Company</span>
            <span class="name-text">Name</span> 
        </p>
    </div>
    <nav>
        <a href="#">Home</a>
        <a href="./pages/services.html">Services</a>
        <a href="./pages/about.html">About</a>
        <a href="./pages/contact.html">Contact</a>
    </nav>
</header>
```

### Footer

Footer has social media links and some other information such as contact and address. Here is the code we have for the footer:

```html
<footer>
    <div class="social-media">
        <a href="https://www.linkedin.com" target="_blank"><i class="fa-brands fa-linkedin"></i></a>
        <a href="https://www.instagram.com" target="_blank"><i class="fa-brands fa-instagram"></i></a>
        <a href="https://www.bluesky.com" target="_blank"><i class="fa-brands fa-bluesky"></i></a>
    </div>
    <div class="info">
        <p>Contact: 04 000 000</p>
        <p>Address: 1 street, suburb</p>
    </div>
</footer>
```

## Pages

### Home

Home is the starting page of the website which consists of a cover image and some detail about the company.

### Services

Services shows different services provided by the company such as Web Development.