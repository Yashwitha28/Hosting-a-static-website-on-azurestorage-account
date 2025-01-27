# Hosting-a-static-website-on-azurestorage-account
Problem Statement
Develop a static website that provides users with valuable insights and tools for exploring innovative investment opportunities. The hosting platform should ensure reliability, cost-effectiveness, and secure access while being easy to deploy and scalable for future needs.

Project Goals
Deploy a user-friendly static website that showcases financial tools and guides, hosted on Azure Storage.
Optimize the website for accessibility, performance, and security using Azure's built-in features.
Leverage Azure services to create a scalable and high-availability hosting environment.
Hosting a Static Website on Azure Storage
Steps Taken

Website Creation

Designed a static website using HTML, CSS, and JavaScript to deliver content related to financial literacy and market trends.
Uploading to GitHub

The website files were stored in a public GitHub repository for version control and ease of deployment.
Azure Storage Setup

Created a new Storage account in Azure and enabled Static Website Hosting through the Azure Portal.
Uploaded all the site’s files, including HTML, CSS, and JavaScript, to the $web container, dedicated to hosting static content.
Custom Domain Integration

Configured a custom domain to enhance branding and provide users with a memorable URL.
Used Azure DNS or a third-party DNS provider to map the domain to the website endpoint with appropriate CNAME or A records.
Website Testing and Deployment

Ensured the site was fully functional by accessing the default Azure Storage endpoint (e.g., https://<storage_account_name>.z13.web.core.windows.net).
Validated that all resources, such as images and scripts, loaded correctly.
Security and Optimization

Enabled HTTPS to ensure secure communication between users and the website.
Utilized Azure Firewall settings to restrict access as required.
Integrated Azure CDN to improve global accessibility and reduce latency.
Azure Services and Tools Utilized
Azure Storage Account: Used for hosting static files in the $web container.
Static Website Hosting: Enabled seamless deployment of static content.
Azure DNS: Simplified domain name management.
Azure CDN: Enhanced the performance and global availability of the website.
GitHub: Hosted and managed the project’s source code.
Azure Portal: Provided an intuitive interface to configure and manage resources.
Live Website and Resources
Website URL: Accessible through a custom domain or the default Azure endpoint.
Conclusion
This project highlights the process of deploying a secure, scalable, and user-friendly static website using Azure Storage. The setup minimizes costs while ensuring high availability and performance, making it an ideal solution for hosting informative or promotional websites.
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Antique Bakery Cafe HTML Template by Tooplate</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Raleway:wght@300;400;500;600&family=Oswald:wght@600&display=swap" rel="stylesheet">
<link rel="stylesheet" href="css/all.min.css"> <!-- fontawesome -->
<!-- <link href="https://unpkg.com/tailwindcss@^2/dist/tailwind.min.css" rel="stylesheet"> -->
<link rel="stylesheet" href="css/tailwind.css">
<link rel="stylesheet" href="css/tooplate-antique-cafe.css">

<!--

Tooplate 2025 Antique Cafe

https://www.tooplate.com/view/2025-antique-cafe

-->
</head>
<body>
<!-- Intro -->
<div id="intro" class="parallax-window" data-parallax="scroll" data-image-src="img/antique-cafe-bg-01.jpg">
<nav id="tm-nav" class="fixed w-full">
<div class="tm-container mx-auto px-2 md:py-6 text-right">
<button class="md:hidden py-2 px-2" id="menu-toggle"><i class="fas fa-2x fa-bars tm-text-gold"></i></button>
<ul class="mb-3 md:mb-0 text-2xl font-normal flex justify-end flex-col md:flex-row">
<li class="inline-block mb-4 mx-4"><a href="#intro" class="tm-text-gold py-1 md:py-3 px-4">Intro</a></li>
<li class="inline-block mb-4 mx-4"><a href="#menu" class="tm-text-gold py-1 md:py-3 px-4">Menu</a></li>
<li class="inline-block mb-4 mx-4"><a href="#about" class="tm-text-gold py-1 md:py-3 px-4">About</a></li>
<li class="inline-block mb-4 mx-4"><a href="#contact" class="tm-text-gold py-1 md:py-3 px-4">Contact</a></li>
</ul>
</div>
</nav>
<div class="container mx-auto px-2 tm-intro-width">
<div class="sm:pb-60 sm:pt-48 py-20">
<div class="bg-black bg-opacity-70 p-12 mb-5 text-center">
<h1 class="text-white text-5xl tm-logo-font mb-5">Antique Cafe</h1>
<p class="tm-text-gold tm-text-2xl">your daily energy booster</p>
</div>
<div class="bg-black bg-opacity-70 p-10 mb-5">
<p class="text-white leading-8 text-sm font-light">
Experience the perfect blend of warmth and flavor! we offer a cozy ambiance, artisan coffees, freshly baked pastries, and vegan-friendly options. Enjoy free Wi-Fi, live acoustic evenings every Friday, and special discounts like Buy 1 Get 1 Free on espresso every Wednesday. Drop by between 8:00 AM and 10:00 PM (Mon–Fri) or 9:00 AM to 11:00 PM (Sat–Sun) to sip, savor, and unwind.
If you have any question, please <a rel="nofollow" href="https://www.tooplate.com/contact" target="_parent">send us a message</a>. </p>
</div>
<div class="text-center">
<div class="inline-block">
<a href="#menu" class="flex justify-center items-center bg-black bg-opacity-70 py-6 px-8 rounded-lg font-semibold tm-text-2xl tm-text-gold hover:text-gray-200 transition">
<i class="fas fa-coffee mr-3"></i>
<span>Let's explore...</span>
</a>
</div>
</div>
</div>
</div>
</div>
<!-- Cafe Menu -->
<div id="menu" class="parallax-window" data-parallax="scroll" data-image-src="img/antique-cafe-bg-02.jpg">
<div class="container mx-auto tm-container py-24 sm:py-48">
<div class="text-center mb-16">
<h2 class="bg-white tm-text-brown py-6 px-12 text-4xl font-medium inline-block rounded-md">Our Cafe Menu</h2>
</div>
<div class="flex flex-col lg:flex-row justify-around items-center">
<div class="flex-1 m-5 rounded-xl px-4 py-6 sm:px-8 sm:py-10 tm-bg-brown tm-item-container">
<div class="flex items-start mb-6 tm-menu-item">
<img src="img/menu-item-1.jpg" alt="Image" class="rounded-md">
<div class="ml-3 sm:ml-6">
<h3 class="text-lg sm:text-xl mb-2 sm:mb-3 tm-text-yellow">Hot Cappuccino</h3>
<div class="text-white text-md sm:text-lg font-light mb-1">S $8.50</div>
<div class="text-white text-md sm:text-lg font-light">L $10.50</div>
</div>
</div>
<div class="flex items-start mb-6 tm-menu-item">
<img src="img/menu-item-2.jpg" alt="Image" class="rounded-md">
<div class="ml-3 sm:ml-6">
<h3 class="text-lg sm:text-xl mb-2 sm:mb-3 tm-text-yellow">Hot Americano</h3>
<div class="text-white text-md sm:text-lg font-light mb-1">S $9.50 . BG #544639</div>
<div class="text-white text-md sm:text-lg font-light">L $12.50</div>
</div>
</div>
<div class="flex items-start mb-6 tm-menu-item">
<img src="img/menu-item-3.jpg" alt="Image" class="rounded-md">
<div class="ml-3 sm:ml-6">
<h3 class="text-lg sm:text-xl mb-2 sm:mb-3 tm-text-yellow">Hot Latte #FC6</h3>
<div class="text-white text-md sm:text-lg font-light mb-1">M $11.75</div>
<div class="text-white text-md sm:text-lg font-light">L $14.75</div>
</div>
</div>
<div class="flex items-start mb-6 tm-menu-item">
<img src="img/menu-item-4.jpg" alt="Image" class="rounded-md">
<div class="ml-3 sm:ml-6">
<h3 class="text-lg sm:text-xl tm-text-yellow mb-1">Hot Espresso</h3>
<h3 class="text-lg sm:text-xl mb-2 sm:mb-3 tm-text-yellow">Hot Chocolate</h3>
<div class="text-white text-md sm:text-lg font-light">Size M $11.75 . L $14.75</div>
</div>
</div>
</div>
<div class="flex-1 m-5 rounded-xl px-4 py-6 sm:px-8 sm:py-10 tm-bg-brown tm-item-container">
<div class="flex items-start justify-end mb-6 tm-menu-item-2">
<div class="text-right mr-6">
<h3 class="text-lg sm:text-xl mb-2 sm:mb-3 tm-text-yellow">Iced Cappuccino</h3>
<div class="text-white text-md sm:text-lg font-light mb-1">Small $10</div>
<div class="text-white text-md sm:text-lg font-light">Large $15</div>
</div>
<img src="img/menu-item-5.jpg" alt="Image" class="rounded-md">
</div>
<div class="flex items-start justify-end mb-6 tm-menu-item-2">
<div class="text-right mr-6">
<h3 class="text-lg sm:text-xl mb-2 sm:mb-3 tm-text-yellow">Iced Americano</h3>
<div class="text-white text-md sm:text-lg font-light mb-1">Small $12.50</div>
<div class="text-white text-md sm:text-lg font-light">Large $16.50</div>
</div>
<img src="img/menu-item-6.jpg" alt="Image" class="rounded-md">
</div>
<div class="flex items-start justify-end mb-6 tm-menu-item-2">
<div class="text-right mr-6">
<h3 class="text-lg sm:text-xl mb-2 sm:mb-3 tm-text-yellow">Iced Milky Latte</h3>
<div class="text-white text-md sm:text-lg font-light mb-1">Small $14</div>
<div class="text-white text-md sm:text-lg font-light">Large $18</div>
</div>
<img src="img/menu-item-7.jpg" alt="Image" class="rounded-md">
</div>
<div class="flex items-start justify-end mb-6 tm-menu-item-2">
<div class="text-right mr-6">
<h3 class="text-lg sm:text-xl tm-text-yellow mb-1">Iced Espresso</h3>
<h3 class="text-lg sm:text-xl mb-2 sm:mb-3 tm-text-yellow">Iced Mocha</h3>
<div class="text-white text-md sm:text-lg font-light">Small $10 . Large $15</div>
</div>
<img src="img/menu-item-8.jpg" alt="Image" class="rounded-md">
</div>
</div>
</div>
</div>
</div>
<div id="about" class="parallax-window" data-parallax="scroll" data-image-src="img/antique-cafe-bg-03.jpg">
<div class="container mx-auto tm-container py-24 sm:py-48">
<div class="tm-item-container sm:ml-auto sm:mr-12 mx-auto sm:px-0 px-4">
<div class="bg-white bg-opacity-80 p-12 pb-14 rounded-xl mb-5">
<h2 class="mb-6 tm-text-green text-4xl font-medium">About our cafe</h2>
<p class="mb-6 text-base leading-8">
Images are taken from Pexels, a great stock photo website. This template used Tailwind CSS. You may modify Antique Cafe template in any way you prefer and use it for your website.
</p>
<p class="text-base leading-8">
If you wish to <a rel="nofollow" href="https://www.tooplate.com/contact" target="_parent">support us</a>, please make a little donation via PayPal. That would be
very helpful. Another way is to tell your friends about Tooplate website. Thank you. </p>
</div>
<a href="#contact" class="inline-block tm-bg-green transition text-white text-xl pt-3 pb-4 px-8 rounded-md">
<i class="far fa-comments mr-4"></i>
Contact
</a>
</div>
</div>
</div>
<div id="contact" class="parallax-window relative" data-parallax="scroll" data-image-src="img/antique-cafe-bg-04.jpg">
<div class="container mx-auto tm-container pt-24 pb-48 sm:py-48">
<div class="flex flex-col lg:flex-row justify-around items-center lg:items-stretch">
<div class="flex-1 rounded-xl px-10 py-12 m-5 bg-white bg-opacity-80 tm-item-container">
<h2 class="text-3xl mb-6 tm-text-green">Contact Us</h2>
<p class="mb-6 text-lg leading-8">
Praesent tellus magna, consectetur sit amet volutpat eu, pulvinar vitae sem.
Sed ultrices. bg white 80% alpha. btn #066
</p>
<p class="mb-10 text-lg">
<span class="block mb-2">Tel: <a href="tel:9701777677" class="hover:text-yellow-600 transition">010-020-0340</a></span>
<span class="block">Email: <a href="mailto:info@company.com" class="hover:text-yellow-600 transition">info@company.com</a></span>
</p>
<div class="text-center">
<a href="https://www.google.com/maps" class="inline-block text-white text-2xl pl-10 pr-12 py-6 rounded-lg transition tm-bg-green">
<i class="fas fa-map-marked-alt mr-8"></i>
Open Maps
</a>
</div>
</div>
<div class="flex-1 rounded-xl p-12 pb-14 m-5 bg-black bg-opacity-50 tm-item-container">
<form action="" method="POST" class="text-lg">
<input type="text" name="name" class="input w-full bg-black border-b bg-opacity-0 text-white px-0 py-4 mb-4 tm-border-gold" placeholder="Name" required="" />
<input type="email" name="email" class="input w-full bg-black border-b bg-opacity-0 text-white px-0 py-4 mb-4 tm-border-gold" placeholder="Email" required="" />
<textarea rows="6" name="message" class="input w-full bg-black border-b bg-opacity-0 text-white px-0 py-4 mb-4 tm-border-gold" placeholder="Message..." required=""></textarea>
<div class="text-right">
<button type="submit" class="text-white hover:text-yellow-500 transition">Send it</button>
</div>
</form>
</div>
</div>
<footer class="absolute bottom-0 left-0 w-full">
<div class="text-white container mx-auto tm-container p-8 text-lg flex flex-col md:flex-row justify-between">
<span>Copyright 2022 Antique Cafe. All rights reserved.</span>
<span class="mt-5 md:mt-0">Design: <a href="https://www.tooplate.com" target="_parent">Tooplate</a></span>
</div>
</footer>
</div>
</div>

<script src="js/jquery-3.6.0.min.js"></script>
<script src="js/parallax.min.js"></script>
<script src="js/jquery.singlePageNav.min.js"></script>
<script>

function checkAndShowHideMenu() {
if(window.innerWidth < 768) {
$('#tm-nav ul').addClass('hidden');
} else {
$('#tm-nav ul').removeClass('hidden');
}
}

$(function(){
var tmNav = $('#tm-nav');
tmNav.singlePageNav();

checkAndShowHideMenu();
window.addEventListener('resize', checkAndShowHideMenu);

$('#menu-toggle').click(function(){
$('#tm-nav ul').toggleClass('hidden');
});

$('#tm-nav ul li').click(function(){
if(window.innerWidth < 768) {
$('#tm-nav ul').addClass('hidden');
}
});

$(document).scroll(function() {
var distanceFromTop = $(document).scrollTop();

if(distanceFromTop > 100) {
tmNav.addClass('scroll');
} else {
tmNav.removeClass('scroll');
}
});

document.querySelectorAll('a[href^="#"]').forEach(anchor => {
anchor.addEventListener('click', function (e) {
e.preventDefault();

document.querySelector(this.getAttribute('href')).scrollIntoView({
behavior: 'smooth'
});
});
});
});
</script>
</body>
</html>
