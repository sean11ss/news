<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>UK News - Latest Headlines</title>
  <style>
    :root {
      --sky-blue: #004c8c;
      --dark-bg: #0a0a0a;
      --card-bg: #111;
      --text-light: #e0e0e0;
      --text-muted: #aaa;
      --accent: #00a0e9;
    }

    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
      background: var(--dark-bg);
      color: var(--text-light);
      line-height: 1.5;
    }

    header {
      background: var(--sky-blue);
      padding: 1rem 2rem;
      position: sticky;
      top: 0;
      z-index: 100;
      box-shadow: 0 2px 10px rgba(0,0,0,0.5);
    }

    .logo { font-size: 2rem; font-weight: bold; color: white; }

    nav {
      margin-top: 0.5rem;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-right: 1.5rem;
      font-weight: 500;
    }

    nav a:hover { text-decoration: underline; }

    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 1.5rem;
    }

    .hero {
      background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1504711434969-e33886168f5c?w=1200') center/cover no-repeat;
      height: 400px;
      display: flex;
      align-items: flex-end;
      padding: 2rem;
      border-radius: 8px;
      margin-bottom: 2rem;
    }

    .hero-content { max-width: 700px; }

    .hero h1 { font-size: 2.8rem; margin-bottom: 1rem; }

    .hero p { font-size: 1.2rem; }

    .category {
      margin-bottom: 3rem;
    }

    .category h2 {
      font-size: 1.8rem;
      margin-bottom: 1.2rem;
      color: var(--accent);
      border-bottom: 3px solid var(--accent);
      display: inline-block;
      padding-bottom: 0.5rem;
    }

    .controls {
      margin-bottom: 1rem;
      text-align: right;
    }

    button {
      background: var(--accent);
      color: white;
      border: none;
      padding: 0.6rem 1.2rem;
      border-radius: 6px;
      cursor: pointer;
      font-weight: bold;
    }

    button:hover { background: #0088cc; }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
      gap: 1.5rem;
    }

    .card {
      background: var(--card-bg);
      border-radius: 8px;
      overflow: hidden;
      transition: transform 0.2s;
    }

    .card:hover { transform: translateY(-6px); }

    .card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
    }

    .card-content {
      padding: 1.2rem;
    }

    .card h3 {
      font-size: 1.3rem;
      margin-bottom: 0.6rem;
    }

    .card h3 a {
      color: white;
      text-decoration: none;
    }

    .card h3 a:hover { text-decoration: underline; }

    .card p {
      font-size: 0.95rem;
      color: var(--text-muted);
    }

    .timestamp {
      font-size: 0.85rem;
      color: #888;
      margin-top: 0.8rem;
    }

    .error-msg {
      color: #ff6666;
      text-align: center;
      padding: 2rem;
    }

    footer {
      background: #000;
      text-align: center;
      padding: 2rem;
      margin-top: 3rem;
      color: #777;
      font-size: 0.9rem;
    }

    @media (max-width: 768px) {
      .hero { height: 300px; }
      .hero h1 { font-size: 2rem; }
      .container { padding: 1rem; }
    }
  </style>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/he/1.2.0/he.min.js"></script>
</head>
<body>

  <header>
    <div class="logo">UK News Headlines brought to you by SM Sites</div>
    <nav>
      <a href="#">Home</a>
      <a href="#">UK</a>
      <a href="#">Politics</a>
      <a href="#">World</a>
      <a href="#">Videos</a>
    </nav>
  </header>

  <div class="container">

    <!-- Hero (static example - you can make dynamic later) -->
    <section class="hero">
      <div class="hero-content">
        <h1>Latest UK & World Headlines</h1>
        <p>Powered by public RSS feeds • Real-time updates • Try different sources below</p>
      </div>
    </section>

    <!-- Dynamic News Section -->
    <section class="category">
      <h2>Latest News</h2>
      <div class="controls">
        <button onclick="loadNews()">Refresh News</button>
      </div>
      <div id="news-grid" class="grid">
        <!-- Cards inserted here -->
        <p style="grid-column: 1 / -1; text-align: center;">Loading latest headlines...</p>
      </div>
    </section>

  </div>

  <footer>
    © 2026 Your News Page • Data from public RSS feeds • Headlines shown with attribution • Open in new tab
  </footer>

  <script>
    async function loadNews() {  // Renamed slightly for clarity, but same function
      const grid = document.getElementById('news-grid');
      grid.innerHTML = '<p style="grid-column: 1 / -1; text-align: center;">Loading...</p>';

      // >>>>>>>> ONLY THIS PART CHANGED: 5 working RSS options <<<<<<<<
      // Uncomment ONE line below (remove the //) and comment the others to switch sources
      const rssUrl = 'https://feeds.bbci.co.uk/news/uk/rss.xml';                  // 1. BBC UK News (very reliable)
      // const rssUrl = 'https://www.theguardian.com/uk-news/rss';               // 2. The Guardian UK News
      // const rssUrl = 'https://feeds.bbci.co.uk/news/rss.xml';                 // 3. BBC Top Stories (includes UK + world)
      // const rssUrl = 'https://www.theguardian.com/world/rss';                 // 4. The Guardian World News (broad, includes UK)
      // const rssUrl = 'https://www.reuters.com/arc/outboundfeeds/newsroom-rss/?outputType=xml'; // 5. Reuters (general/world, often covers UK)

      const proxyUrl = `https://api.allorigins.win/raw?url=${encodeURIComponent(rssUrl)}`;

      try {
        const response = await fetch(proxyUrl);
        if (!response.ok) throw new Error('Network response was not ok');

        const xmlText = await response.text();
        const parser = new DOMParser();
        const xmlDoc = parser.parseFromString(xmlText, 'text/xml');

        const items = xmlDoc.querySelectorAll('item');
        grid.innerHTML = '';

        Array.from(items).slice(0, 9).forEach(item => {
          const title = item.querySelector('title')?.textContent || 'No title';
          const link = item.querySelector('link')?.textContent || '#';
          const description = item.querySelector('description')?.textContent || '';
          const pubDate = item.querySelector('pubDate')?.textContent || '';

          // Clean description: decode entities, strip HTML, truncate
          let cleanDesc = he.decode(description.replace(/<[^>]+>/g, '').trim());
          cleanDesc = cleanDesc.substring(0, 120) + (cleanDesc.length > 120 ? '...' : '');

          // Try to get thumbnail from media:content or enclosure
          const media = item.querySelector('media\\:content, enclosure, media\\:thumbnail');
          const imgUrl = media?.getAttribute('url') || 
                         media?.getAttribute('medium')?.includes('image') ? media.getAttribute('url') : 
                         'https://via.placeholder.com/320x180?text=News';

          const card = document.createElement('div');
          card.className = 'card';
          card.innerHTML = `
            <img src="${imgUrl}" alt="${title}" 
                 onerror="this.src='https://via.placeholder.com/320x180?text=News'">
            <div class="card-content">
              <h3><a href="${link}" target="_blank" rel="noopener noreferrer">${title}</a></h3>
              <p>${cleanDesc}</p>
              <div class="timestamp">${pubDate ? new Date(pubDate).toLocaleString() : 'Recent'}</div>
            </div>
          `;
          grid.appendChild(card);
        });

        if (items.length === 0) {
          grid.innerHTML = '<p class="error-msg">No stories found in feed.</p>';
        }
      } catch (error) {
        console.error('Error:', error);
        grid.innerHTML = '<p class="error-msg">Could not load news feed right now.<br>Try a different source (uncomment another rssUrl line) or check connection.</p>';
      }
    }

    // Load automatically on page load
    window.addEventListener('DOMContentLoaded', loadNews);
  </script>

</body>
</html>
