---
layout: underline-2
title: Summer Break 2026
---

<style>
  .event-card img {
    width: 100%;
    aspect-ratio: 16 / 9;
    object-fit: cover;
    border-radius: 12px;
    margin-bottom: 1.5rem;
  }
  .event-card footer, dialog article footer {
    display: flex;
    gap: 1.5rem;
    flex-wrap: wrap;
    align-items: center;
    justify-content: space-between;
    margin-top: 1.5rem;
    border-top: 1px solid rgba(0,0,0,0.05);
    padding-top: 1.5rem;
  }
  dialog article footer {
    justify-content: center;
  }
  .event-card footer .date-tag {
    margin-bottom: 0;
    opacity: 0.8;
    font-weight: 600;
  }
  .button {
    flex: 0 1 auto;
    margin-bottom: 0;
    min-width: 200px;
    border-radius: 50px;
    font-weight: 700;
    text-transform: uppercase;
    letter-spacing: 0.05em;
    font-size: 0.85rem;
    transition: all 0.2s ease;
    padding: 0.75rem 1.5rem;
    border: 2px solid transparent;
    text-decoration: none !important;
    display: inline-block;
    text-align: center;
    background-color: var(--red);
    color: white !important;
  }
  .button:hover {
    background-color: var(--orange);
    transform: translateY(-2px);
    box-shadow: 0 4px 12px rgba(255, 107, 53, 0.2);
    text-decoration: none !important;
  }
  .details-link {
    font-weight: 700;
    color: var(--teal);
    text-decoration: underline;
    cursor: pointer;
    margin-left: 0.5rem;
    white-space: nowrap;
  }
  .details-link:hover {
    color: var(--red);
  }
  dialog article {
    max-width: 800px;
  }
  .modal-body {
    text-align: left;
  }
  dialog article header button[aria-label="Close"] {
    background-color: var(--red);
    border-radius: 50%;
    width: 32px;
    height: 32px;
    padding: 0;
    display: flex;
    align-items: center;
    justify-content: center;
    border: none;
    transition: transform 0.2s ease;
  }
  dialog article header button[aria-label="Close"]:hover {
    background-color: var(--orange);
  }
  dialog article header h3 {
    margin-bottom: 0;
  }
</style>

<section class="hero-section">
  <div class="grid">
    <div>
      <h1 style="text-align: left; font-size: 4rem; margin: 0;">SUMMER<br><span style="color: var(--orange);">BREAK</span></h1>
    </div>
    <div>
      <p class="pico-color-slate-500" style="font-size: 1.2rem; line-height: 1.6;">
        We’re hosting a curated series of workshops and activities designed specifically for teenagers (13-18), running Monday to Friday from May 25th to May 29th during the daytime (before 5pm).
      </p>
    </div>
  </div>
</section>

<div class="activities-list">
  <h3 style="color: var(--red); border-left: 4px solid var(--red); padding-left: 1rem; margin-top: 4rem;">THE FIRST ACT</h3>
  <article class="event-card">
    <img src="https://underline.center/uploads/default/optimized/1X/27abea633d09d1dbb91cba039bf0a846db44d9b0_2_1035x582.jpeg" alt="Made you Click">
    <h4>Made you Click</h4>
    <p>Every ad you’ve ever ignored was designed by someone who knew exactly what would make you pause, whether that’s the colour, sound, or visuals. This workshop is about learning to see the machinery behind brands and influencers while finding your role as a critic.<a class="details-link" onclick="document.getElementById('modal-made-you-click').showModal()">Details...</a></p>
    <footer>
      <span class="date-tag">Mon–Tue, May 25–26, 9am–11am</span>
      <a href="https://district.in/made-you-click-by-the-first-act-may25-2026/event" class="button" target="_blank">Buy Tickets (₹2599)</a>
    </footer>
  </article>

  <h3 style="color: var(--orange); border-left: 4px solid var(--orange); padding-left: 1rem; margin-top: 4rem;">THE FIRST ACT</h3>
  <article class="event-card">
    <img src="https://underline.center/uploads/default/optimized/1X/c066b3470cbbd014e02b20cb5c09d940311adb44_2_1035x582.jpeg" alt="IRL v/s URL">
    <h4>IRL v/s URL</h4>
    <p>A hands-on workshop using theatre and games to unpack the psychology behind social media. Discover why these apps are built to hook you, how they quietly shape your sense of self, and how to build an intentional relationship with your online world.<a class="details-link" onclick="document.getElementById('modal-irl-vs-url').showModal()">Details...</a></p>
    <footer>
      <span class="date-tag">Wed & Fri, May 27 & 29, 9am–11am</span>
      <a href="https://district.in/irl-vs-url-by-the-first-act-may27-2026/event" class="button" target="_blank">Buy Tickets (₹2599)</a>
    </footer>
  </article>

  <h3 style="color: var(--teal); border-left: 4px solid var(--teal); padding-left: 1rem; margin-top: 4rem;">ROLIGAMI</h3>
  <article class="event-card">
    <img src="https://underline.center/uploads/default/optimized/1X/9f4864fe817b2b1a96e6365a1ea552fbd7ccc6cd_2_1035x582.jpeg" alt="Modular Origami Workshop">
    <h4>Modular Origami Workshop</h4>
    <p>Discover the art of folding multiple identical paper units and locking them together to build complex 3D structures. Build spatial reasoning, precision, and patience while exploring the intersection of craft, mathematics, and design.<a class="details-link" onclick="document.getElementById('modal-origami').showModal()">Details...</a></p>
    <footer>
      <span class="date-tag">Mon–Fri, May 25–29, 11am–1pm</span>
      <a href="https://district.in/modular-origami-workshop-for-teens-with-roligami-may25-2026/event" class="button" target="_blank">Buy Tickets (₹2999)</a>
    </footer>
  </article>

  <h3 style="color: var(--green); border-left: 4px solid var(--green); padding-left: 1rem; margin-top: 4rem;">PLAYFUL PURSUITS & THE PUZZLE PARLOUR</h3>
  <article class="event-card">
    <img src="https://underline.center/uploads/default/original/1X/71906781e4205d28903bdf2f6db384d6a8bd8e84.jpeg" alt="Piece It Together: Jigsaw Puzzle Summer Camp">
    <h4>Piece It Together: Jigsaw Puzzle Summer Camp</h4>
    <p>Join our Jigsaw Puzzle Summer Camp for an exciting experience filled with puzzle-solving, teamwork, and speed! Improve your problem-solving and critical thinking skills, enhance pattern-recognition, and learn speed-puzzling techniques in a fun, collaborative environment.<a class="details-link" onclick="document.getElementById('modal-puzzle').showModal()">Details...</a></p>
    <footer>
      <span class="date-tag">Mon–Fri, May 25–29, 2:30pm–4:30pm</span>
      <a href="https://district.in/piece-it-together-jigsaw-puzzle-summer-camp-with-playful-pursuits-may25-2026/event" class="button" target="_blank">Buy Tickets (₹2999)</a>
    </footer>
  </article>

  <h3 style="color: var(--blue); border-left: 4px solid var(--blue); padding-left: 1rem; margin-top: 4rem;">IMPROV LORE</h3>
  <article class="event-card">
    <div style="width: 100%; aspect-ratio: 16 / 9; background: var(--blue); border-radius: 12px; margin-bottom: 1.5rem; display: flex; align-items: center; justify-content: center; color: white; font-weight: 700; font-size: 1.5rem; opacity: 0.2;">COMING SOON</div>
    <h4>Improvised Theater Workshop</h4>
    <p>A fun and high-energy workshop where you'll learn the fundamentals of improv. Build confidence, creativity, and quick-thinking skills through play and performance. Stay tuned for more details and dates!</p>
    <footer>
      <span class="date-tag">Dates & Times Coming Soon</span>
      <a href="#" class="button" style="background-color: var(--black); opacity: 0.5; pointer-events: none;">Coming Soon</a>
    </footer>
  </article>

  <h3 style="color: var(--pink); border-left: 4px solid var(--pink); padding-left: 1rem; margin-top: 4rem;">BY THARUNYA</h3>
  <article class="event-card">
    <div style="width: 100%; aspect-ratio: 16 / 9; background: var(--pink); border-radius: 12px; margin-bottom: 1.5rem; display: flex; align-items: center; justify-content: center; color: white; font-weight: 700; font-size: 1.5rem; opacity: 0.2;">COMING SOON</div>
    <h4>Tabletop Role Playing Workshop</h4>
    <p>Dive into the world of storytelling and collaborative world-building. Learn how to create characters, navigate epic quests, and master the art of the TTRPG. Full details and schedule will be announced shortly.</p>
    <footer>
      <span class="date-tag">Dates & Times Coming Soon</span>
      <a href="#" class="button" style="background-color: var(--black); opacity: 0.5; pointer-events: none;">Coming Soon</a>
    </footer>
  </article>
</div>

<dialog id="modal-made-you-click">
  <article>
    <header>
      <button aria-label="Close" rel="prev" onclick="document.getElementById('modal-made-you-click').close()"></button>
      <h3>Made you Click</h3>
    </header>
    <div class="modal-body">
      <p><strong>A 2-day workshop on how brands, ads, and influencers get inside your head</strong></p>
      <p>Every ad you’ve ever ignored was designed by someone who knew exactly what would make you pause, whether that’s the colour, sound, visuals, or the influencer who seems to be speaking directly to you about the product that changed their life. This workshop is about learning to see the machinery behind it all.</p>
      <p><strong>Day 1:</strong> We’ll start with play. Through improv games and live exercises, you’ll find yourself stepping into the roles of marketer, audience, and critic, sometimes all three at once. No lectures. No slides. Just you, the room, and a growing sense that you’ve seen this trick before.</p>
      <p><strong>Day 2:</strong> You flip sides and make your own ad, which may end with a Shark Tank-style presentation. Because once you’ve made the thing, you can’t unsee how it’s made.</p>
      <hr>
      <p><strong>Who is The First Act?</strong><br>
      The First Act is a media literacy venture working towards cultivating digitally aware consumers of technology and media. Our goal is to cultivate critical thinkers for those growing up in today’s media landscape using play, theatre exercises and minimal screens!</p>
      <p>Follow us on instagram <strong>@thefirstactindia</strong></p>
    </div>
    <footer>
      <a href="https://district.in/made-you-click-by-the-first-act-may25-2026/event" class="button" target="_blank">Buy Tickets (₹2599)</a>
    </footer>
  </article>
</dialog>

<dialog id="modal-irl-vs-url">
  <article>
    <header>
      <button aria-label="Close" rel="prev" onclick="document.getElementById('modal-irl-vs-url').close()"></button>
      <h3>IRL v/s URL</h3>
    </header>
    <div class="modal-body">
      <p><strong>A 2-day hands-on media literacy workshop for teenagers that uses theatre and games to unpack the psychology behind social media.</strong></p>
      <p>Why these apps are built to hook you, how they quietly shape who you think you are, and what that does to your sense of self.</p>
      <p><strong>Day 1:</strong> We get under the skin of social media: why these apps are built to keep you hooked, how they shape how you see yourself, and who’s really calling the shots on your feed.</p>
      <p><strong>Day 2:</strong> We turn that awareness into agency: through reflection, and creative exercises, students explore what an intentional relationship with their online world could actually look like. We close with an alternative reality where they are the CEOs of a new popular social media app. How would it be different from what’s available today?</p>
      <hr>
      <p><strong>Who is The First Act?</strong><br>
      The First Act is a media literacy venture working towards cultivating digitally aware consumers of technology and media. Our goal is to cultivate critical thinkers for those growing up in today’s media landscape using play, theatre exercises and minimal screens!</p>
      <p>Follow us on instagram <strong>@thefirstactindia</strong></p>
    </div>
    <footer>
      <a href="https://district.in/irl-vs-url-by-the-first-act-may27-2026/event" class="button" target="_blank">Buy Tickets (₹2599)</a>
    </footer>
  </article>
</dialog>

<dialog id="modal-origami">
  <article>
    <header>
      <button aria-label="Close" rel="prev" onclick="document.getElementById('modal-origami').close()"></button>
      <h3>Modular Origami Workshop</h3>
    </header>
    <div class="modal-body">
      <p>Modular origami is the art of folding multiple identical paper units and locking them together - without glue or tape - to build stunning three-dimensional geometric structures. Each piece involves repetition, planning, and assembly, making it a uniquely satisfying blend of craft, mathematics, and design.</p>
      <p>Over five two-hour sessions, students aged 13 to 18 will progress from their very first fold to completing a 30-unit icosahedron. Along the way, they will build spatial reasoning, practice precision and patience, and explore colour and design.</p>
      
      <p><strong>By the end of the five days, students will be able to:</strong></p>
      <ul>
        <li>Fold and assemble multiple modular origami forms, from 3 to 30 units</li>
        <li>Understand the relationship between 2D folds and 3D geometric structures</li>
        <li>Apply colour design thinking before folding to achieve planned visual patterns</li>
        <li>Develop problem-solving strategies when assembly becomes challenging</li>
      </ul>

      <p><strong>Daily Overview:</strong></p>
      <ul>
        <li><strong>Day 1: The Art of the Module</strong> - Discover what modular origami is and complete your first 3D model: Toshie’s Jewel.</li>
        <li><strong>Day 2: Into the Third Dimension</strong> - From flat paper to 3D polyhedra — building a 6-unit cube and a 12-unit stellated ball.</li>
        <li><strong>Day 3: Stars & Geometry</strong> - Explore flat star modules and modular rosettes, making personal colour design decisions.</li>
        <li><strong>Day 4: Complex Structures</strong> - The major challenge: the 30-unit Sonobe icosahedron.</li>
        <li><strong>Day 5: Design & Showcase</strong> - Experiment with module variations and present your work in a class exhibition.</li>
      </ul>

      <p><strong>Materials:</strong> All materials provided, including square origami paper, paper folders, and more.</p>
      <hr>
      <p><strong>Who is Roligami?</strong><br>
      Roli Agrawal, known as roligami, is a multi-disciplinary designer and passionate craft enthusiast who has been exploring and teaching origami for over a decade. Her workshops are a celebration of creativity. Follow her on Instagram <strong>@roligami</strong>.</p>
    </div>
    <footer>
      <a href="https://district.in/modular-origami-workshop-for-teens-with-roligami-may25-2026/event" class="button" target="_blank">Buy Tickets (₹2999)</a>
    </footer>
  </article>
</dialog>

<dialog id="modal-puzzle">
  <article>
    <header>
      <button aria-label="Close" rel="prev" onclick="document.getElementById('modal-puzzle').close()"></button>
      <h3>Piece It Together: Jigsaw Puzzle Summer Camp</h3>
    </header>
    <div class="modal-body">
      <p>Are you ready for a summer of fun, challenges, and creativity? Join our Jigsaw Puzzle Summer Camp for an exciting experience filled with puzzle-solving, teamwork, and speed!</p>
      
      <p><strong>Eligibility:</strong> Attendees (10-18 years old) must be able to complete a 50-piece puzzle independently.</p>
      
      <p><strong>Benefits:</strong></p>
      <ul>
        <li>Improves problem-solving and critical thinking skills</li>
        <li>Enhances pattern-recognition and dexterity</li>
        <li>Encourages patience, focus, and teamwork</li>
        <li>Teaches speed-puzzling techniques</li>
      </ul>

      <p><strong>Inclusions:</strong></p>
      <ul>
        <li>Puzzles provided for all activities</li>
        <li>Air-conditioned venue and drinking water</li>
        <li>Participation certificate</li>
        <li>Puzzles from a leading Indian brand to take home</li>
      </ul>

      <p><strong>Schedule:</strong></p>
      <ul>
        <li><strong>Day 1:</strong> Introduction & Puzzle Basics</li>
        <li><strong>Day 2:</strong> Wooden Puzzles - How It’s Made and Solving Strategies</li>
        <li><strong>Day 3:</strong> Introduction to Speed Puzzling</li>
        <li><strong>Day 4:</strong> Teamwork & Collaboration Exercises</li>
        <li><strong>Day 5:</strong> Speed Puzzling Competition</li>
      </ul>

      <hr>
      <p><strong>Who is Playful Pursuits?</strong><br>
      Run by Asma Tajuddin, a passionate puzzler who represented India at the World Jigsaw Puzzle Championship 2025. Bangalore’s first jigsaw puzzle meetup group and India-wide community. Instagram: <strong>@playful.pursuits</strong></p>
      <p><strong>Who is The Puzzle Parlour?</strong><br>
      Mercy Grace Solomon is an avid puzzler who combined her passion for puzzles with her background in education to create a space for meet-ups, workshops, and competitions. Instagram: <strong>@thepuzzleparlour</strong></p>
    </div>
    <footer>
      <a href="https://district.in/piece-it-together-jigsaw-puzzle-summer-camp-with-playful-pursuits-may25-2026/event" class="button" target="_blank">Buy Tickets (₹2999)</a>
    </footer>
  </article>
</dialog>

<!-- Calendar section placeholder 
<div id="calendar-view" style="margin-top: 6rem; border-top: 1px solid var(--black); padding-top: 4rem;">
  <h2 style="text-align: center;">Calendar View</h2>
  <p style="text-align: center; opacity: 0.6;">The full interactive calendar will be added here soon.</p>
</div>
-->

<!--
<div id="register" style="margin-top: 4rem;">

<h2>Sign Up</h2>
<p>We have a bunch of fun activities and workshops lined up for teenagers during the weekdays between 25th May and 29th May.</p>

  <iframe data-tally-src="https://tally.so/embed/VLogb6?hideTitle=1&transparentBackground=1&dynamicHeight=1" loading="lazy" width="100%" height="790" frameborder="0" marginheight="0" marginwidth="0" title="Underline Summer Break"></iframe>
  <script>var d=document,w="https://tally.so/widgets/embed.js",v=function(){"undefined"!=typeof Tally?Tally.loadEmbeds():d.querySelectorAll("iframe[data-tally-src]:not([src])").forEach((function(e){e.src=e.dataset.tallySrc}))};if("undefined"!=typeof Tally)v();else if(d.querySelector('script[src="'+w+'"]')==null){var s=d.createElement("script");s.src=w,s.onload=v,s.onerror=v,d.body.appendChild(s);}</script>
</div>
-->
