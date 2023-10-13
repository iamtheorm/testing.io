
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Cisco Community</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Inline CSS for demonstration purposes; consider using an external CSS file */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        nav ul li {
            display: inline;
            margin-right: 20px;
        }
        nav a {
            color: #333;
            text-decoration: none;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #FFA500;
        }
        .tab-content {
            padding: 20px;
            background-color: #fff;
            text-align: center;
            display: none;
        }
        .active {
            display: block;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }
        footer a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
        }
        .footer-image {
            width: 100px; /* Adjust the image width as needed */
        }
    </style>
</head>
<body>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#cisco-community">CISCO Community</a></li>
            <li><a href="#our-programs">Our Programs</a></li>
            <li><a href="#global-networks">Global Networks</a></li>
            <li><a href="#event-calendar">Event Calendar</a></li>
            <li><a href="#member-stories">Member Stories</a></li>
            <li><a href="#contact-us">Contact Us</a></li>
        </ul>
    </nav>

    <div class="tab-content" id="home">
        <h2>Welcome to Our Cisco Community</h2>
        <p>This is where you can find all the information related to Cisco in our college.</p>
        <p>Sample text for the Home page. You can replace this with your content.</p>
    </div>

    <div class="tab-content" id="cisco-community">
        <h2>CISCO Community</h2>
        <p>Explore our vibrant Cisco community and join us in our tech journey. Our community is built on the following principles:</p>
        <ul>
            <li>Collaboration and Knowledge Sharing</li>
            <li>Professional Growth and Development</li>
            <li>Global Networking Opportunities</li>
        </ul>
        <p>Sample text for the CISCO Community page. You can replace this with your content.</p>
    </div>

    <div class "tab-content" id="our-programs">
        <h2>Our Programs</h2>
        <p>We offer a variety of programs to help you enhance your skills and knowledge. Stay tuned for updates on our programs.</p>
        <p>Sample text for the Our Programs page. You can replace this with your content.</p>
    </div>

    <div class="tab-content" id="global-networks">
        <h2>Global Networks</h2>
        <p>Connect with highly successful individuals from the Cisco community around the world. Learn from their experiences and insights.</p>
        <p>Sample text for the Global Networks page. You can replace this with your content.</p>
    </div>

    <div class="tab-content" id="event-calendar">
        <h2>Event Calendar</h2>
        <p>We're in the process of updating our event calendar. Thank you for your patience. Stay tuned for upcoming events and activities.</p>
        <p>Sample text for the Event Calendar page. You can replace this with your content.</p>
    </div>

    <div class="tab-content" id="member-stories">
        <h2>Member Stories</h2>
        <p>Explore inspiring stories of Cisco community members from different parts of the world:</p>
        <table>
            <tr>
                <th>Name</th>
                <th>Location</th>
                <th>Story</th>
            </tr>
            <tr>
                <td>John Doe</td>
                <td>San Francisco, USA</td>
                <td>John Doe's inspiring journey in the Cisco community.</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>Sydney, Australia</td>
                <td>Jane Smith's experience in the Cisco community.</td>
            </tr>
        </table>
        <p>Sample text for the Member Stories page. You can replace this with your content.</p>
    </div>

    <div class="tab-content" id="contact-us">
        <h2>Contact Us</h2>
        <p>If you have any questions or need assistance, feel free to contact us:</p>
        <p>Mobile Number: 7408297060</p>
        <p>Email: <a href="mailto:ritik.23bce10850@vitbhopal.ac.in">ritik.23bce10850@vitbhopal.ac.in</a></p>
        <p>Sample text for the Contact Us page. You can replace this with your content.</p>
    </div>

    <footer>
        <a href="#community-guidelines">Community Guidelines</a>
        <a href="#help">Help</a>
        <a href="#privacy-policy">Privacy Policy</a>
        <a href="#terms-and-conditions">Terms and Conditions</a>
        <img src="your-image.jpg" alt="Community Image" class="footer-image">
    </footer>

    <script>
        function showTab(tabId) {
            var tabs = document.getElementsByClassName("tab-content");
            for (var i = 0; i < tabs.length; i++) {
                tabs[i].style.display = "none";
            }
            document.getElementById(tabId).style.display = "block";
        }
    </script>
</body>
</html>
