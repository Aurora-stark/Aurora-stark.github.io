<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aurora</title>
    
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Montserrat:wght@400;600&display=swap" rel="stylesheet">

    <style>
        /* CSS styles are inside this <style> tag */

        /* Basic Setup */
        :root {
            --dark-bg: #0a043c;
            --text-light: #f0f0f0;
            --aurora-green: #4caf50;
            --aurora-pink: #ff4081;
            --aurora-blue: #00bcd4;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: 'Montserrat', sans-serif;
            background-color: var(--dark-bg);
            color: var(--text-light);
            line-height: 1.6;
        }

        /* --- Homepage / Hero Section --- */
        #hero {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 20px;
            
            /* TODO: Replace this background image URL with a beautiful photo of you two! */
            background-image: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('https://images.unsplash.com/photo-1531366936337-7c912a4589a7?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80');
            background-size: cover;
            background-position: center;
        }

        #hero h1 {
            font-family: 'Dancing Script', cursive;
            font-size: 6rem; /* 6 times the normal font size */
            text-shadow: 0 0 15px var(--aurora-blue);
        }

        #hero p {
            font-size: 1.5rem;
            margin-top: 10px;
            margin-bottom: 30px;
        }

        .cta-button {
            display: inline-block;
            padding: 12px 25px;
            border: 2px solid var(--aurora-blue);
            border-radius: 50px;
            color: var(--text-light);
            text-decoration: none;
            font-weight: 600;
            transition: background-color 0.3s, color 0.3s;
        }

        .cta-button:hover {
            background-color: var(--aurora-blue);
            color: var(--dark-bg);
        }

        /* --- General Section Styling --- */
        section {
            padding: 100px 20px;
            text-align: center;
        }

        section h2 {
            font-family: 'Dancing Script', cursive;
            font-size: 3.5rem;
            margin-bottom: 50px;
            text-shadow: 0 0 10px var(--aurora-pink);
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
        }

        /* --- 1. Our Journey (Timeline) --- */
        .timeline {
            position: relative;
            padding-left: 50px; /* Space for the line */
            border-left: 3px solid var(--aurora-green);
            text-align: left;
        }

        .timeline-item {
            margin-bottom: 50px;
            position: relative;
        }
        
        .timeline-item::before {
            content: '✨';
            position: absolute;
            left: -35px; /* Position on the line */
            top: 0;
            font-size: 1.5rem;
            background-color: var(--dark-bg);
        }

        .timeline-item h3 {
            color: var(--aurora-green);
            font-size: 1.5rem;
        }
        
        .timeline-item p {
            font-size: 1rem;
        }

        /* --- 2. Reasons Why (Cards) --- */
        .reasons-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
        }

        .reason-card {
            background: rgba(255, 255, 255, 0.05);
            padding: 25px;
            border-radius: 10px;
            border: 1px solid var(--aurora-pink);
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .reason-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 20px rgba(255, 64, 129, 0.3);
        }

        .reason-card h3 {
            color: var(--aurora-pink);
            margin-bottom: 10px;
        }

        /* --- 3 & 4. Soundtrack & Map (Embedded content) --- */
        .embed-container {
            border: 2px solid var(--aurora-blue);
            border-radius: 10px;
            overflow: hidden;
            margin-top: 30px;
        }
        
        iframe {
            width: 100%;
            height: 450px;
            border: none;
        }
        
        /* --- 5. "Open When..." Letters --- */
        .letters-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        
        .letter-button {
            background-color: transparent;
            color: var(--aurora-green);
            border: 2px solid var(--aurora-green);
            padding: 15px 30px;
            border-radius: 50px;
            font-family: 'Montserrat', sans-serif;
            font-size: 1rem;
            font-weight: 600;
            cursor: pointer;
            transition: background-color 0.3s, color 0.3s;
        }
        
        .letter-button:hover {
            background-color: var(--aurora-green);
            color: var(--dark-bg);
        }
    </style>
</head>
<body>

    <header id="hero">
        <h1>Aurora</h1>
        <p>A little world I built just for you, [Her Name].</p>
        <a href="#journey" class="cta-button">Explore Our Sky</a>
    </header>

    <main>

        <section id="journey">
            <div class="container">
                <h2>Our Journey ✨</h2>
                <div class="timeline">
                    <div class="timeline-item">
                        <h3>September 15, 2024 - The Day We Met</h3>
                        <p>Your message about this day goes here. A little detail you remember, something that made you smile.</p>
                    </div>
                    <div class="timeline-item">
                        <h3>October 20, 2024 - Our First Date</h3>
                        <p>Write about your first date. Where you went, what you talked about, a funny moment that happened.</p>
                    </div>
                    <div class="timeline-item">
                        <h3>December 25, 2024 - First Holiday</h3>
                        <p>A memory from your first holiday season together. A gift, a special moment, anything you cherish.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="reasons">
            <div class="container">
                <h2>The Reasons Why 💌</h2>
                <div class="reasons-grid">
                    <div class="reason-card">
                        <h3>The Way You Smile</h3>
                        <p>It lights up the whole room and makes my day instantly better.</p>
                    </div>
                    <div class="reason-card">
                        <h3>Your Kindness</h3>
                        <p>You are kind to everyone you meet, and it's one of the most beautiful things about you.</p>
                    </div>
                    <div class="reason-card">
                        <h3>Our Late-Night Talks</h3>
                        <p>I love that we can talk about anything and everything for hours.</p>
                    </div>
                    <div class="reason-card">
                        <h3>Your Sense of Humor</h3>
                        <p>You always know how to make me laugh, even on the toughest days.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="soundtrack">
            <div class="container">
                <h2>Our Soundtrack 🎶</h2>
                <p>A collection of songs that remind me of us.</p>
                <div class="embed-container">
                    <iframe style="border-radius:12px" src="https://open.spotify.com/embed/playlist/37i9dQZF1DXcBWIGoYBM5M?utm_source=generator" width="100%" height="352" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
                </div>
            </div>
        </section>
        
        <section id="map">
            <div class="container">
                <h2>Our Adventure Map 🗺️</h2>
                <p>Places we've been and places we'll go together.</p>
                 <div class="embed-container">
                    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3963.952912260219!2d3.375295414770757!3d6.527631645278465!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x103b8b2ae68280c1%3A0x5df9fe84736ccc53!2sLagos!5e0!3m2!1sen!2sng!4v1617290515127!5m2!1sen!2sng" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
                </div>
            </div>
        </section>

        <section id="letters">
            <div class="container">
                <h2>A Message For You ✉️</h2>
                <p>Click a button whenever you want to hear from me.</p>
                <div class="letters-container">
                    <button class="letter-button" onclick="alert('You know I miss you more than anything right now. Close your eyes and think of our best memory together. I am with you always.')">Open When You Miss Me</button>
                    <button class="letter-button" onclick="alert('Remember that time we [insert funny memory here]? Thinking about it always makes me smile. Hope it does for you too!')">Open When You Need a Laugh</button>
                    <button class="letter-button" onclick="alert('Hey. Whatever is happening, just know that you are the strongest, most amazing person I know. You can handle this. I am here for you, always. Call me if you need me.')">Open When You've Had a Bad Day</button>
                </div>
            </div>
        </section>

    </main>

</body>
</html>
