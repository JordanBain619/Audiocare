<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>AudioCare Inc</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    body { font-family: Arial, sans-serif; margin: 0; color: #222; }
    header, section { padding: 60px 20px; max-width: 1100px; margin: 0 auto; }
    nav { display: flex; justify-content: space-between; align-items: center; padding: 15px 20px; background: #0b1b2b; color: #fff; position: sticky; top: 0; z-index: 10; }
    nav a { color: #fff; margin-left: 15px; text-decoration: none; font-size: 0.95rem; }
    .logo { font-weight: bold; letter-spacing: 0.05em; }
    .hero { display: flex; flex-wrap: wrap; align-items: center; gap: 30px; }
    .hero-text { flex: 1 1 280px; }
    .hero h1 { font-size: 2.4rem; margin-bottom: 10px; }
    .hero p { font-size: 1.05rem; line-height: 1.6; }
    .btn-group { margin-top: 20px; }
    .btn {
      display: inline-block;
      padding: 10px 20px;
      margin-right: 10px;
      border-radius: 4px;
      text-decoration: none;
      font-size: 0.95rem;
    }
    .btn-primary { background: #1f7ae0; color: #fff; }
    .btn-secondary { background: #fff; color: #1f7ae0; border: 1px solid #1f7ae0; }
    h2 { margin-top: 0; margin-bottom: 15px; }
    .two-col { display: flex; flex-wrap: wrap; gap: 30px; }
    .two-col > div { flex: 1 1 280px; }
    .services-list li { margin-bottom: 8px; }
    form { max-width: 600px; }
    label { display: block; margin-top: 12px; font-size: 0.9rem; }
    input, textarea, select {
      width: 100%;
      padding: 8px;
      margin-top: 4px;
      border-radius: 4px;
      border: 1px solid #ccc;
      font-size: 0.9rem;
      box-sizing: border-box;
    }
    textarea { min-height: 100px; }
    .submit-btn {
      margin-top: 16px;
      padding: 10px 20px;
      background: #1f7ae0;
      color: #fff;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      font-size: 0.95rem;
    }
    footer {
      background: #0b1b2b;
      color: #fff;
      padding: 20px;
      text-align: center;
      font-size: 0.85rem;
    }
    @media (max-width: 700px) {
      .hero { flex-direction: column; }
      nav { flex-wrap: wrap; }
    }
  </style>
</head>
<body>

  <nav>
    <div class="logo">AudioCare Inc</div>
    <div>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#reps">Outside Reps</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>

  <header>
    <div class="hero">
      <div class="hero-text">
        <h1>Hearing Solutions You Can Trust</h1>
        <p>
          AudioCare Inc delivers professional hearing care, advanced technology, and compassionate support
          to help you hear—and live—better every day.
        </p>
        <div class="btn-group">
          <a href="#contact" class="btn btn-primary">Schedule an Appointment</a>
          <a href="#reps" class="btn btn-secondary">Apply as an Outside Rep</a>
        </div>
      </div>
    </div>
  </header>

  <section id="about">
    <h2>About AudioCare Inc</h2>
    <div class="two-col">
      <div>
        <p>
          At AudioCare Inc, our mission is to improve quality of life through better hearing.
          Our experienced team combines clinical expertise with modern technology to deliver
          personalized care for every patient.
        </p>
      </div>
      <div>
        <ul>
          <li>Licensed, experienced hearing specialists</li>
          <li>Evidence-based testing and fitting</li>
          <li>Personalized treatment plans</li>
          <li>Long-term follow-up and support</li>
        </ul>
      </div>
    </div>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <ul class="services-list">
      <li><strong>Hearing Evaluations:</strong> Comprehensive diagnostic testing to understand your hearing profile.</li>
      <li><strong>Hearing Aid Fitting & Programming:</strong> Custom-fit devices tuned to your lifestyle.</li>
      <li><strong>Tinnitus Management:</strong> Strategies and technology to help manage ringing or buzzing in the ears.</li>
      <li><strong>Follow-Up Care:</strong> Ongoing adjustments, cleanings, and performance checks.</li>
    </ul>
  </section>

  <section id="reps">
    <h2>Outside Representative Applications</h2>
    <p>
      Interested in representing AudioCare Inc in your region? We partner with motivated outside reps
      who are passionate about hearing health and building long-term relationships with providers and patients.
    </p>
    <ul>
      <li>Flexible territory opportunities</li>
      <li>Competitive commission structure</li>
      <li>Training and product education</li>
      <li>Ongoing support from the AudioCare Inc team</li>
    </ul>

    <h3>Apply Now</h3>
    <form action="YOUR_FORM_HANDLER_URL" method="POST" enctype="multipart/form-data">
      <label for="rep-name">Full Name</label>
      <input type="text" id="rep-name" name="name" required />

      <label for="rep-email">Email</label>
      <input type="email" id="rep-email" name="email" required />

      <label for="rep-phone">Phone</label>
      <input type="tel" id="rep-phone" name="phone" required />

      <label for="rep-location">City / State</label>
      <input type="text" id="rep-location" name="location" required />

      <label for="rep-experience-years">Years of Sales Experience</label>
      <input type="number" id="rep-experience-years" name="years_experience" min="0" />

      <label for="rep-industry">Relevant Industry Experience</label>
      <textarea id="rep-industry" name="industry_experience"></textarea>

      <label for="rep-why">Why do you want to represent AudioCare Inc?</label>
      <textarea id="rep-why" name="motivation" required></textarea>

      <!-- Optional resume upload if your backend supports it -->
      <label for="rep-resume">Resume (PDF or DOC)</label>
      <input type="file" id="rep-resume" name="resume" accept=".pdf,.doc,.docx" />

      <button type="submit" class="submit-btn">Submit Application</button>
    </form>
  </section>

  <section id="contact">
    <h2>Contact AudioCare Inc</h2>
    <p>
      Have questions or want to schedule an appointment? Reach out and our team will get back to you promptly.
    </p>
    <p>
      <strong>Phone:</strong> (XXX) XXX-XXXX<br />
      <strong>Email:</strong> info@audiocareinc.com<br />
      <strong>Address:</strong> 1234 Hearing Lane, Suite 100, Your City, ST 00000
    </p>

    <h3>Send Us a Message</h3>
    <form action="YOUR_CONTACT_FORM_HANDLER_URL" method="POST">
      <label for="contact-name">Name</label>
      <input type="text" id="contact-name" name="name" required />

      <label for="contact-email">Email</label>
      <input type="email" id="contact-email" name="email" required />

      <label for="contact-message">Message</label>
      <textarea id="contact-message" name="message" required></textarea>

      <button type="submit" class="submit-btn">Send Message</button>
    </form>
  </section>

  <footer>
    &copy; <span id="year"></span> AudioCare Inc. All rights reserved.
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
