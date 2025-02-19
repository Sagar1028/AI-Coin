# AI-Coin
This repository contains the source code for a responsive landing page for the AI Coin project. AI Coin rewards contributions in the field of AI. The page, built with HTML, CSS (Bootstrap), and JavaScript, explains the project's concept, how it works, and includes a contact form for further inquiries."
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AI Coin - Rewarding AI Contributions</title>
  <!-- Bootstrap CSS CDN -->
  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css"
    rel="stylesheet"
  />
  <style>
    body {
      background-color: #f8f9fa;
      font-family: Arial, sans-serif;
    }
    .header {
      background-color: #343a40;
      color: #fff;
      padding: 2rem 0;
      text-align: center;
    }
    .header h1 {
      font-size: 3rem;
    }
    .section {
      padding: 4rem 0;
    }
    .footer {
      background-color: #343a40;
      color: #fff;
      padding: 1rem 0;
      text-align: center;
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header class="header">
    <div class="container">
      <h1>AI Coin</h1>
      <p>Rewarding AI Contributions</p>
    </div>
  </header>

  <!-- About Section -->
  <section class="section" id="about">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-md-6">
          <h2>About AI Coin</h2>
          <p>
            AI Coin is a unique rewards platform that credits users with points
            for contributing to the field of Artificial Intelligence. Earn points
            by sharing data, training models, or offering insights and redeem them
            for exclusive benefits!
          </p>
        </div>
        <div class="col-md-6">
          <img
            src="https://via.placeholder.com/500x300"
            class="img-fluid"
            alt="AI Coin Illustration"
          />
        </div>
      </div>
    </div>
  </section>

  <!-- How It Works Section -->
  <section class="section bg-light" id="how-it-works">
    <div class="container">
      <h2 class="text-center mb-4">How It Works</h2>
      <div class="row">
        <div class="col-md-4 text-center">
          <h3>Contribute</h3>
          <p>Share your AI data, models, or research to earn points.</p>
        </div>
        <div class="col-md-4 text-center">
          <h3>Earn Points</h3>
          <p>Receive AI Coins as rewards for your valuable contributions.</p>
        </div>
        <div class="col-md-4 text-center">
          <h3>Redeem Rewards</h3>
          <p>
            Use your AI Coins to access premium content, tools, or special
            privileges.
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section class="section" id="contact">
    <div class="container">
      <h2 class="text-center mb-4">Contact Us</h2>
      <div class="row justify-content-center">
        <div class="col-md-6">
          <form id="contactForm">
            <div class="mb-3">
              <label for="name" class="form-label">Name</label>
              <input
                type="text"
                class="form-control"
                id="name"
                placeholder="Enter your name"
                required
              />
            </div>
            <div class="mb-3">
              <label for="email" class="form-label">Email</label>
              <input
                type="email"
                class="form-control"
                id="email"
                placeholder="Enter your email"
                required
              />
            </div>
            <div class="mb-3">
              <label for="message" class="form-label">Message</label>
              <textarea
                class="form-control"
                id="message"
                rows="4"
                placeholder="Your message..."
                required
              ></textarea>
            </div>
            <button type="submit" class="btn btn-primary w-100">
              Send Message
            </button>
          </form>
          <div id="formResponse" class="mt-3"></div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <div class="container">
      <p>&copy; 2025 AI Coin. All rights reserved.</p>
    </div>
  </footer>

  <!-- Bootstrap JS Bundle CDN -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
  <!-- Simple form handling script -->
  <script>
    document.getElementById("contactForm").addEventListener("submit", function(e) {
      e.preventDefault();
      // In a real app, you'd send the form data to a server.
      document.getElementById("formResponse").innerHTML = "<div class='alert alert-success'>Thank you for contacting us. We'll get back to you soon!</div>";
      this.reset();
    });
  </script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AI Coin - Rewarding AI Contributions</title>
  <!-- Bootstrap CSS CDN -->
  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css"
    rel="stylesheet"
  />
  <style>
    body {
      background-color: #f8f9fa;
      font-family: Arial, sans-serif;
    }
    .header {
      background-color: #343a40;
      color: #fff;
      padding: 2rem 0;
      text-align: center;
    }
    .header h1 {
      font-size: 3rem;
    }
    .section {
      padding: 4rem 0;
    }
    .footer {
      background-color: #343a40;
      color: #fff;
      padding: 1rem 0;
      text-align: center;
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header class="header">
    <div class="container">
      <h1>AI Coin</h1>
      <p>Rewarding AI Contributions</p>
    </div>
  </header>

  <!-- About Section -->
  <section class="section" id="about">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-md-6">
          <h2>About AI Coin</h2>
          <p>
            AI Coin is a unique rewards platform that credits users with points
            for contributing to the field of Artificial Intelligence. Earn points
            by sharing data, training models, or offering insights and redeem them
            for exclusive benefits!
          </p>
        </div>
        <div class="col-md-6">
          <img
            src="https://via.placeholder.com/500x300"
            class="img-fluid"
            alt="AI Coin Illustration"
          />
        </div>
      </div>
    </div>
  </section>

  <!-- How It Works Section -->
  <section class="section bg-light" id="how-it-works">
    <div class="container">
      <h2 class="text-center mb-4">How It Works</h2>
      <div class="row">
        <div class="col-md-4 text-center">
          <h3>Contribute</h3>
          <p>Share your AI data, models, or research to earn points.</p>
        </div>
        <div class="col-md-4 text-center">
          <h3>Earn Points</h3>
          <p>Receive AI Coins as rewards for your valuable contributions.</p>
        </div>
        <div class="col-md-4 text-center">
          <h3>Redeem Rewards</h3>
          <p>
            Use your AI Coins to access premium content, tools, or special
            privileges.
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section class="section" id="contact">
    <div class="container">
      <h2 class="text-center mb-4">Contact Us</h2>
      <div class="row justify-content-center">
        <div class="col-md-6">
          <form id="contactForm">
            <div class="mb-3">
              <label for="name" class="form-label">Name</label>
              <input
                type="text"
                class="form-control"
                id="name"
                placeholder="Enter your name"
                required
              />
            </div>
            <div class="mb-3">
              <label for="email" class="form-label">Email</label>
              <input
                type="email"
                class="form-control"
                id="email"
                placeholder="Enter your email"
                required
              />
            </div>
            <div class="mb-3">
              <label for="message" class="form-label">Message</label>
              <textarea
                class="form-control"
                id="message"
                rows="4"
                placeholder="Your message..."
                required
              ></textarea>
            </div>
            <button type="submit" class="btn btn-primary w-100">
              Send Message
            </button>
          </form>
          <div id="formResponse" class="mt-3"></div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <div class="container">
      <p>&copy; 2025 AI Coin. All rights reserved.</p>
    </div>
  </footer>

  <!-- Bootstrap JS Bundle CDN -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
  <!-- Simple form handling script -->
  <script>
    document.getElementById("contactForm").addEventListener("submit", function(e) {
      e.preventDefault();
      // In a real app, you'd send the form data to a server.
      document.getElementById("formResponse").innerHTML = "<div class='alert alert-success'>Thank you for contacting us. We'll get back to you soon!</div>";
      this.reset();
    });
  </script>
</body>
</html>
