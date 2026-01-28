<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stay Nest Boy's Pg - Affordable Accommodation for Boys</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">Stay Nest Boy's Pg</div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#rooms">Rooms</a></li>
                <li><a href="#amenities">Amenities</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <h1>Welcome to Stay Nest Boy's Pg</h1>
        <p>Affordable, comfortable accommodation for boys. Your home away from home.</p>
        <button onclick="scrollToSection('contact')">Book Now</button>
    </section>

    <section id="rooms">
        <h2>Our Rooms</h2>
        <div class="room-grid">
            <div class="room">
                <img src="room1.jpg" alt="Single Room"> <!-- Replace with actual image URL -->
                <h3>Single Room</h3>
                <p>Private space with attached bath. ₹3000/month.</p>
            </div>
            <div class="room">
                <img src="room2.jpg" alt="Shared Room">
                <h3>Shared Room (2-4 Boys)</h3>
                <p>Economical option with common bath. ₹1500/month per person.</p>
            </div>
        </div>
    </section>

    <section id="amenities">
        <h2>Amenities</h2>
        <ul>
            <li>High-Speed Wi-Fi</li>
            <li>Home-Cooked Meals</li>
            <li>Laundry Service</li>
            <li>24/7 Security</li>
            <li>Common Study Area</li>
        </ul>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>Stay Nest is a male-only PG offering a safe, friendly environment for students and working professionals. No smoking, strict timings, and a focus on hygiene.</p>
    </section>

    <section id="contact">
        <h2>Contact & Book</h2>
        <form id="bookingForm">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Email" required>
            <input type="tel" placeholder="Phone" required>
            <textarea placeholder="Message"></textarea>
            <button type="submit">Submit</button>
        </form>
