# Gaming-news
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Gaming News Site</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Your Gaming News</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="news.html">News</a></li>
                <li><a href="reviews.html">Reviews</a></li>
                <li><a href="guides.html">Guides</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="banner">
            <h2>Featured News Article</h2>
            <img src="featured-image.jpg" alt="Featured News">
            <p>Summary of the featured article...</p>
        </section>

        <section class="latest-news">
            <h2>Latest News</h2>
            <article>
                <h3>Article Title</h3>
                <p>Summary of the article...</p>
            </article>
            <!-- Repeat for more articles -->
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Your Gaming News. All rights reserved.</p>
        <p>Follow us on social media: [Links]</p>
    </footer>
</body>
</html>
body {
    font-family: 'Arial', sans-serif;
    background-color: #121212;
    color: #ffffff;
}

header {
    background-color: #1a1a1a;
    padding: 20px;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

a {
    color: #00ffcc;
    text-decoration: none;
}

.banner {
    background-color: #222;
    padding: 20px;
}

.latest-news {
    margin: 20px 0;
}

footer {
    background-color: #1a1a1a;
    text-align: center;
    padding: 10px;
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Gaming News Site</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Your Gaming News</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="news.html">News</a></li>
                <li><a href="reviews.html">Reviews</a></li>
                <li><a href="guides.html">Guides</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="banner">
            <h2>Featured News Article</h2>
            <img src="featured-game-image.jpg" alt="Featured Game" style="width:100%; height:auto;">
            <p>Check out the latest news about [Game Title]. Discover new updates, gameplay features, and more!</p>
            <a href="news.html#featured-article" class="button">Read More</a>
        </section>

        <section class="latest-news">
            <h2>Latest News</h2>
            <article>
                <h3><a href="news.html#news1">New Game Release: Adventure Awaits!</a></h3>
                <img src="game-release-image.jpg" alt="Game Release" style="width:100%; height:auto;">
                <p>Get ready for the newest adventure game that has taken the world by storm!</p>
            </article>

            <article>
                <h3><a href="news.html#news2">Top 10 Tips for Winning in Battle Royale</a></h3>
                <img src="battle-royale-image.jpg" alt="Battle Royale" style="width:100%; height:auto;">
                <p>Master the battlefield with these essential strategies!</p>
            </article>

            <article>
                <h3><a href="news.html#news3">The Evolution of RPGs Over the Years</a></h3>
                <img src="rpg-evolution-image.jpg" alt="RPG Evolution" style="width:100%; height:auto;">
                <p>Explore how role-playing games have transformed the gaming landscape!</p>
            </article>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Your Gaming News. All rights reserved.</p>
        <p>Follow us on social media: 
            <a href="https://twitter.com/yourprofile">Twitter</a> | 
            <a href="https://facebook.com/yourprofile">Facebook</a> | 
            <a href="https://instagram.com/yourprofile">Instagram</a>
        </p>
    </footer>
</body>
</html>
body {
    font-family: 'Arial', sans-serif;
    background-color: #121212;
    color: #ffffff;
}

header {
    background-color: #1a1a1a;
    padding: 20px;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

a {
    color: #00ffcc;
    text-decoration: none;
}

.banner {
    background-color: #222;
    padding: 20px;
    text-align: center;
}

.latest-news {
    margin: 20px 0;
}

.latest-news article {
    margin-bottom: 20px;
}

.latest-news img {
    margin: 10px 0;
}

.button {
    display: inline-block;
    background-color: #00ffcc;
    color: #121212;
    padding: 10px 15px;
    text-decoration: none;
    border-radius: 5px;
}

footer {
    background-color: #1a1a1a;
    text-align: center;
    padding: 10px;
}
<section class="latest-news">
    <h2>Latest News</h2>
    <label for="news-filter">Filter by category:</label>
    <select id="news-filter" onchange="filterArticles()">
        <option value="all">All</option>
        <option value="releases">New Releases</option>
        <option value="tips">Tips & Tricks</option>
        <option value="evolution">RPG Evolution</option>
    </select>

    <div id="articles">
        <article class="news-item" data-category="releases">
            <h3><a href="news.html#news1">New Game Release: Adventure Awaits!</a></h3>
            <img src="game-release-image.jpg" alt="Game Release" style="width:100%; height:auto;">
            <p>Get ready for the newest adventure game that has taken the world by storm!</p>
        </article>

        <article class="news-item" data-category="tips">
            <h3><a href="news.html#news2">Top 10 Tips for Winning in Battle Royale</a></h3>
            <img src="battle-royale-image.jpg" alt="Battle Royale" style="width:100%; height:auto;">
            <p>Master the battlefield with these essential strategies!</p>
        </article>

        <article class="news-item" data-category="evolution">
            <h3><a href="news.html#news3">The Evolution of RPGs Over the Years</a></h3>
            <img src="rpg-evolution-image.jpg" alt="RPG Evolution" style="width:100%; height:auto;">
            <p>Explore how role-playing games have transformed the gaming landscape!</p>
        </article>

        <!-- Add more articles as needed -->
    </div>
</section>
<script>
    function filterArticles() {
        const filter = document.getElementById('news-filter').value;
        const articles = document.querySelectorAll('.news-item');

        articles.forEach(article => {
            if (filter === 'all' || article.dataset.category === filter) {
                article.style.display = '';
            } else {
                article.style.display = 'none';
            }
        });
    }
</script>
select {
    padding: 10px;
    border: none;
    border-radius: 5px;
    background-color: #333;
    color: #00ffcc;
    margin-bottom: 20px;
}
<section class="latest-news">
    <h2>Latest News</h2>
    <label for="news-filter">Filter by category:</label>
    <select id="news-filter" onchange="filterArticles()">
        <option value="all">All</option>
        <option value="releases">New Releases</option>
        <option value="tips">Tips & Tricks</option>
        <option value="evolution">RPG Evolution</option>
        <option value="league">League of Legends</option>
    </select>

    <div id="articles">
        <article class="news-item" data-category="releases">
            <h3><a href="news.html#news1">New Game Release: Adventure Awaits!</a></h3>
            <img src="game-release-image.jpg" alt="Game Release" style="width:100%; height:auto;">
            <p>Get ready for the newest adventure game that has taken the world by storm!</p>
        </article>

        <article class="news-item" data-category="tips">
            <h3><a href="news.html#news2">Top 10 Tips for Winning in Battle Royale</a></h3>
            <img src="battle-royale-image.jpg" alt="Battle Royale" style="width:100%; height:auto;">
            <p>Master the battlefield with these essential strategies!</p>
        </article>

        <article class="news-item" data-category="evolution">
            <h3><a href="news.html#news3">The Evolution of RPGs Over the Years</a></h3>
            <img src="rpg-evolution-image.jpg" alt="RPG Evolution" style="width:100%; height:auto;">
            <p>Explore how role-playing games have transformed the gaming landscape!</p>
        </article>

        <article class="news-item" data-category="league">
            <h3><a href="news.html#news4">League of Legends: The New Season Begins!</a></h3>
            <img src="league-of-legends-image.jpg" alt="League of Legends" style="width:100%; height:auto;">
            <p>The new season of League of Legends is here, featuring exciting updates and champions!</p>
        </article>

        <!-- Add more articles as needed -->
    </div>
</section>
.latest-news img {
    margin: 10px 0;
    max-width: 100%; /* Ensures responsiveness */
    height: auto;    /* Maintains aspect ratio */
}
