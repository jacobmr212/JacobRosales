# JacobRosales
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>NetBot Assist</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    /* General Styles */
    body {
      font-family: 'Roboto', sans-serif;
      line-height: 1.6;
      margin: 0;
      padding: 0;
      background-color: #f4f4f9;
    }
    a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
    }
    h1, h2, h3 {
      color: #333;
      text-align: center;
    }
    p {
      color: #666;
      text-align: center;
    }
    button {
      padding: 15px 30px;
      background-color: #007bff;
      color: #fff;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-size: 1em;
    }
    header {
      background-color: #333;
      padding: 20px 0;
      color: white;
      text-align: center;
    }
    header .container {
      display: flex;
      align-items: center;
      justify-content: space-between;
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 20px;
    }
    header img {
      height: 100px;
    }
    header nav a {
      color: white;
      text-decoration: none;
      margin: 0 5px;
    }
    section {
      text-align: center;
      padding: 50px 20px;
    }
    section .container {
      max-width: 800px;
      margin: 0 auto;
      text-align: left;
    }
    #hero {
      background-color: #f7f9fc;
    }
    #hero h1 {
      font-size: 2.5em;
    }
    #hero p {
      font-size: 1.2em;
    }
    #hero a {
      display: inline-block;
      padding: 15px 30px;
      margin-top: 20px;
      background-color: #007bff;
      color: #fff;
      text-decoration: none;
      border-radius: 5px;
    }
    #hero img {
      max-width: 200px;
      margin-bottom: 20px;
    }
    #features, #detailed-features, #target-audience {
      background-color: #f7f9fc;
    }
    .feature-list {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
    }
    .feature-item {
      flex: 1;
      min-width: 250px;
      text-align: center;
      padding: 20px;
    }
    .feature-item img {
      height: 100px;
    }
    #signup form, #feedback form {
      max-width: 500px;
      margin: 0 auto;
    }
    #signup input, #feedback input, #feedback textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
    }
  </style>
</head>
<body>
  <!-- Header Section -->
  <header>
    <div class="container">
      <img src="https://netbotassist.com/wp-content/uploads/2024/06/NetBot_transparent.png" alt="NetBot Transparent Logo">
      <nav>
        <a href="#about">About</a>
        <a href="#features">Features</a>
        <a href="#pain-points">Pain Points</a>
        <a href="#target-audience">Who It's For</a>
        <a href="#signup">Sign Up</a>
        <a href="#feedback">Feedback</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section id="hero">
    <h1>NetBot: Revolutionizing ERP Implementations - Coming Soon!</h1>
    <p>AI-Powered Assistant for NetSuite Consultants</p>
    <a href="#signup">Sign Up for Updates</a>
    <p style="margin-top: 30px;">Sign up for updates and be notified when NetBot launches.</p>
    <div style="margin-top: 30px;">
      <iframe width="560" height="315" src="https://www.youtube.com/embed/o824hdpZSKY" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </section>

  <!-- About Section -->
  <section id="about">
    <div class="container">
      <h2>What is NetBot?</h2>
      <p>NetBot is an AI-powered assistant designed to streamline NetSuite implementations with instant query resolution and step-by-step guides.</p>
    </div>
  </section>

  <!-- Features Section -->
  <section id="features">
    <div class="container">
      <h2>Why Choose NetBot?</h2>
      <div class="feature-list">
        <div class="feature-item">
          <img src="https://netbotassist.com/wp-content/uploads/2024/06/image-1.jpeg" alt="Query Resolution Icon">
          <h3>Instant Query Resolution</h3>
          <p>Get quick answers to your NetSuite implementation questions.</p>
        </div>
        <div class="feature-item">
          <img src="https://netbotassist.com/wp-content/uploads/2024/06/image.jpeg" alt="Guides Icon">
          <h3>Step-by-Step Guides</h3>
          <p>Follow detailed instructions for complex tasks.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Pain Points Section -->
  <section id="pain-points">
    <div class="container">
      <h2>Pain Points NetBot Mitigates</h2>
      <div>
        <h3>1. Time-Consuming Query Resolution</h3>
        <p>NetBot provides instant answers to queries, eliminating the need for lengthy research and manual troubleshooting.</p>
        <h3>2. Complex Implementation Processes</h3>
        <p>Our step-by-step guides simplify complex tasks, reducing errors and ensuring a smoother implementation process.</p>
        <h3>3. Document Management Challenges</h3>
        <p>NetBot helps organize and retrieve necessary documents quickly, improving overall efficiency and reducing frustration.</p>
        <h3>4. Lack of Real-Time Support</h3>
        <p>NetBot offers real-time assistance, ensuring users get the help they need exactly when they need it.</p>
      </div>
    </div>
  </section>

  <!-- Target Audience Section -->
  <section id="target-audience">
    <div class="container">
      <h2>Who is NetBot For?</h2>
      <div class="feature-list">
        <div class="feature-item">
          <h3>NetSuite Consultants</h3>
          <p>Enhance your implementation process with instant query resolutions and step-by-step guides.</p>
        </div>
        <div class="feature-item">
          <h3>ERP Managers</h3>
          <p>Improve efficiency and accuracy in ERP implementation with real-time assistance and organized documentation.</p>
        </div>
        <div class="feature-item">
          <h3>IT Professionals</h3>
          <p>Streamline your workflow by having immediate access to necessary information and troubleshooting support.</p>
        </div>
        <div class="feature-item">
          <h3>Businesses Using NetSuite</h3>
          <p>Experience a smoother implementation process, reducing downtime and ensuring a successful transition.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Sign-Up Section -->
  <section id="signup">
    <div class="container">
      <h2>Be the First to Know!</h2>
      <p>Sign up for updates and be notified when NetBot launches.</p>
      <form action="your_form_handler_url" method="post">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <button type="submit">Sign Up</button>
        <p>We respect your privacy. No spam, ever.</p>
      </form>
    </div>
  </section>

  <!-- Detailed Features Section -->
  <section id="detailed-features">
    <div class="container">
      <h2>Explore NetBot's Capabilities</h2>
      <div>
        <h3>1. Instant Query Resolution</h3>
        <p>NetBot provides immediate answers to your queries, saving time and enhancing efficiency. Whether you need help with data migration or integration, NetBot is here to assist.</p>
        <h3>
        <h3>2. Step-by-Step Guides</h3>
        <p>Our detailed guides help you navigate complex tasks with ease. Each step is clearly outlined, ensuring you never miss a crucial detail.</p>
      </div>
    </div>
  </section>

  <!-- Feedback Section -->
  <section id="feedback">
    <div class="container">
      <h2>We Want to Hear from You!</h2>
      <p>Do you have questions or feedback about NetBot? Let us know!</p>
      <form action="your_form_handler_url" method="post">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
        <button type="submit">Submit</button>
      </form>
    </div>
  </section>

  <!-- Call-to-Action Section -->
  <section id="cta">
    <div class="container" style="text-align: center;">
      <h2>Stay Tuned!</h2>
      <p>Sign up now to be the first to know when NetBot launches.</p>
      <a href="#signup" class="cta-button" style="display: inline-block; padding: 15px 30px; margin-top: 20px; background-color: #007bff; color: #fff; text-decoration: none; border-radius: 5px;">Sign Up for Updates</a>
    </div>
  </section>
</body>
</html>
