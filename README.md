<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="robots" content="index, follow" />
  <meta name="description" content="A journal-like blog by Urja Vaswani on healing, hope, and real-life reflections." />
  <title>LightWithin</title>
  <link href="https://fonts.googleapis.com/css2?family=Dancing+Script&family=Poppins&display=swap" rel="stylesheet">
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(145deg, #fef9f6, #fff0f5);
      color: #444;
    }

    header {
      display: flex; justify-content: space-between; align-items: center;
      background-color: #ffffffdd;
      padding: 20px; position: sticky; top: 0; z-index: 1000;
    }

    .menu-toggle {
      font-size: 24px; background: none; border: none; cursor: pointer;
      color: #d16b86; display: none;
    }

    nav {
      width: 240px; background-color: #ffffffee;
      padding: 40px 20px; box-shadow: 2px 0 8px rgba(0,0,0,0.05);
      height: 100vh; position: fixed; left: -260px; top: 0;
      transition: left 0.3s ease; z-index: 999;
    }

    nav.open { left: 0; }

    nav h1 {
      font-family: 'Dancing Script', cursive;
      font-size: 2.5rem; color: #d16b86; margin-bottom: 20px;
    }

    nav p {
      font-style: italic; font-size: 1rem; color: #8e7d88; margin-bottom: 30px;
    }

    nav a {
      display: block; margin: 15px 0; text-decoration: none;
      color: #7b6f72; font-weight: 500; font-size: 1rem;
    }

    nav a:hover { color: #d16b86; }

    main {
      max-width: 900px; margin: 0 auto; padding: 30px 20px;
      background-color: rgba(255,255,255,0.9); border-radius: 16px; margin-top: 20px;
    }

    section { margin-bottom: 60px; }

    h2 {
      font-family: 'Dancing Script', cursive;
      font-size: 2rem; color: #c45c7b; margin-bottom: 15px;
    }

    footer {
      text-align: center; font-size: 0.9rem; color: #999;
      margin: 40px 0 10px;
    }

    @media (max-width: 768px) {
      .menu-toggle { display: block; }
      nav { height: 100%; }
      main { margin: 0; border-radius: 0; }
    }
  </style>
</head>
<meta name="google-site-verification" content="4cLdWqFIePn_hPLiRCVkTDHAATs0C3lqsTA5FE8sSUg" />
<body>

  <header>
    <button class="menu-toggle" onclick="toggleMenu()">☰</button>
  </header>

  <nav id="sidebar">
    <h1>LightWithin</h1>
    <p>A space for reflection, healing, and gentle growth.</p>

    <a href="#blog" onclick="toggleMenu()">Blog</a>
    <a href="#about" onclick="toggleMenu()">About</a>
    <a href="#contact" onclick="toggleMenu()">Contact</a>
    <a href="#privacy" onclick="toggleMenu()">Privacy</a>

    <h3 style="margin-top: 30px; font-size: 1.1rem; color: #c45c7b;">Posts</h3>
    <a href="#post1" onclick="toggleMenu()">Five Life Lessons Before 27</a>
  </nav>

  <main>
    <section id="blog" style="scroll-margin-top: 80px;">
      <h2>Latest Posts</h2>

      <article id="post1">
        <h3>Five Life Lessons I’ve Learned Before Turning 27</h3>
        <p><em>By Urja Vaswani</em></p>

        <p>As I approach my 27th birthday, I find myself reflecting on the past years—the wins, the losses, the heartbreaks, and the breakthroughs. Life doesn’t come with a manual, but experience has a way of teaching us lessons we never expected. Here are five things I’ve learned that have reshaped the way I see the world:</p>

        <h4>1. The One You Chase Is Not Your Love</h4>
        <p>Love is not a game of pursuit; it’s a connection that flows naturally. I’ve learned that when you have to constantly chase someone—begging for their time, affection, or commitment—they are not meant for you. Real love doesn’t make you question your worth or leave you exhausted from trying. Instead, it feels safe, reciprocated, and effortless.</p>

        <h4>2. Sometimes, Family Is Found Outside of Blood Ties</h4>
        <p>While family is often associated with blood relations, life has taught me that love and support can come from unexpected places. Sometimes, the people who stand by you, understand you, and lift you up during your darkest times are not related by blood but by choice. Cherish these connections because family is ultimately about love, not lineage.</p>

        <h4>3. It’s Okay to Stay in Your Comfort Zone (Sometimes)</h4>
        <p>There’s an overwhelming pressure to “step out of your comfort zone” to grow, but I’ve realized that comfort zones exist for a reason. They provide safety, rest, and stability. Growth doesn’t always mean constant discomfort; sometimes, it happens quietly within familiar spaces. The key is balance—knowing when to push yourself and when to embrace the comfort you need.</p>

        <h4>4. People’s Opinions Don’t Matter When You’re Struggling</h4>
        <p>We often spend so much time worrying about what others think, only to realize that in tough moments, their opinions don’t change anything. When life gets hard, it’s you who has to deal with it—not them. So, why waste time overthinking their judgments? Focus on what truly matters: your well-being and personal growth.</p>

        <h4>5. Prioritizing Mental Health Is the Best Decision You’ll Ever Make</h4>
        <p>Nothing in life is more valuable than peace of mind. Learning to prioritize my mental health has been transformative. Whether it’s setting boundaries, seeking therapy, practicing mindfulness, or simply saying ‘no’ to things that drain me, choosing my mental well-being has made life more fulfilling. A healthy mind shapes everything else—your relationships, career, and overall happiness.</p>

        <p>As I step into this new chapter of life, I carry these lessons with me—not as rigid rules but as guiding principles. Life will always be unpredictable, but the wisdom we gather along the way makes the journey worthwhile. Here’s to learning, growing, and embracing every experience that shapes us.</p>
      </article>
    </section>

    <section id="about">
      <h2>About Me</h2>
      <p>I’ve walked through my own share of ups and downs — in life, family, and relationships. But through healing, faith, and hope, I survived. Now, I’m ready to share those stories with the world — not just to speak, but to connect, to uplift, and to let others know they’re not alone.</p>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>I’d love to hear your thoughts or connect —</p>
      <p>Email me at: <a href="mailto:urja2115@gmail.com">urja2115@gmail.com</a></p>
    </section>

    <section id="privacy">
      <h2>Privacy Policy</h2>
      <p>This site does not collect personal data. Google AdSense may use cookies for ad personalization. You can disable cookies in your browser settings.</p>
    </section>

    <footer>
      <p>&copy; 2025 LightWithin. All rights reserved.</p>
    </footer>
  </main>

  <script>
    function toggleMenu() {
      document.getElementById('sidebar').classList.toggle('open');
    }

    window.addEventListener('load', () => {
      const blogSection = document.getElementById('blog');
      if (blogSection) {
        blogSection.scrollIntoView({ behavior: 'smooth' });
      }
    });
  </script>
</body>
</html>
