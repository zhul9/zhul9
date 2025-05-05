<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>How to Lose a Guy in 10 Days</title>
    <link rel="stylesheet" href="styles.css">
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script> <!-- Animation library -->
    <link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Roboto:wght@400;500&display=swap" rel="stylesheet">
</head>
<body>
    <header data-aos="fade-down">
        <h1>How to Lose a Guy in 10 Days</h1>
        <p>The Ultimate Guide to Pushing Love Away... in 10 Days or Less!</p>
    </header>

    <main>
        <section class="intro" data-aos="fade-right">
            <h2>Welcome to the Guide!</h2>
            <p>If you've ever wondered how to make sure a relationship doesn't last, you're in the right place! Based on the classic romantic comedy, here are some tips to help you lose that guy... fast.</p>
            <img src="https://via.placeholder.com/600x400?text=Lose+Him+Fast!" alt="Lose Him Fast" class="intro-img">
        </section>

        <section class="tips" data-aos="fade-up">
            <h2>Top 10 Tips to Lose a Guy in 10 Days</h2>
            <ul>
                <li><strong>Day 1:</strong> Be overly clingy! Text him constantly and demand his attention.</li>
                <li><strong>Day 2:</strong> Introduce him to your crazy side. Share way too much personal information.</li>
                <li><strong>Day 3:</strong> Plan a surprise date. Make sure it’s totally uncomfortable for him.</li>
                <li><strong>Day 4:</strong> Talk about your future together. A lot. Too much.</li>
                <li><strong>Day 5:</strong> Start picking out wedding songs... it’s only day 5, right?</li>
                <li><strong>Day 6:</strong> Show up at his work uninvited. Bring lunch. And dessert. And a band.</li>
                <li><strong>Day 7:</strong> Be hyper-jealous. Over everything. Even his cat.</li>
                <li><strong>Day 8:</strong> Introduce him to your mom. And your grandma. And your aunt. And the neighbors.</li>
                <li><strong>Day 9:</strong> Plan a dinner with his friends. Overly discuss your relationship in front of them.</li>
                <li><strong>Day 10:</strong> Demand exclusivity… immediately. Don’t give him a chance to breathe.</li>
            </ul>
        </section>

        <section class="do-not-do" data-aos="fade-left">
            <h2>What NOT to Do!</h2>
            <p>Whatever you do, don't actually use these tips in real life! They are guaranteed to fail if you're looking for love. Remember, this is all in good fun!</p>
            <img src="https://via.placeholder.com/600x300?text=Do+Not+Try+This" alt="What Not to Do" class="not-to-do-img">
        </section>

        <section class="testimonials" data-aos="zoom-in">
            <h2>What People Are Saying</h2>
            <div class="testimonial">
                <p>"I tried these tips once... and lost him in under a week! It's hilarious and I’m still single!" - Sarah</p>
            </div>
            <div class="testimonial">
                <p>"Best advice ever! I haven't seen him in months. Perfect!" - Jessica</p>
            </div>
        </section>

        <section class="animation" data-aos="flip-up">
            <h2>Bonus: Fun Animation</h2>
            <p>Here’s a little fun animation for you! Watch the hearts fly!</p>
            <div class="heart-container">
                <span class="heart">💔</span>
                <span class="heart">❤️</span>
                <span class="heart">💔</span>
                <span class="heart">❤️</span>
                <span class="heart">💔</span>
            </div>
        </section>
    </main>

    <footer data-aos="fade-up">
        <p>&copy; 2025 How to Lose a Guy in 10 Days Guide</p>
    </footer>

    <script>
        AOS.init({ duration: 1200 }); // Initialize AOS animation library
    </script>
</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Roboto', sans-serif;
    background-color: #f0f8ff;
    color: #333;
    line-height: 1.6;
    padding-bottom: 50px;
}

header {
    background-color: #ffcccb;
    text-align: center;
    padding: 20px;
    margin-bottom: 20px;
    border-radius: 10px;
}

header h1 {
    font-family: 'Pacifico', cursive;
    font-size: 3rem;
    color: #ff6347;
    animation: fadeIn 2s;
}

header p {
    font-size: 1.2rem;
    color: #555;
}

main {
    padding: 20px;
    max-width: 900px;
    margin: 0 auto;
}

h2 {
    color: #ff6347;
    margin-bottom: 10px;
    font-size: 2rem;
    font-weight: 500;
}

ul {
    list-style-type: none;
    margin-left: 20px;
}

li {
    font-size: 1.1rem;
    margin-bottom: 15px;
    line-height: 1.5;
}

.intro-img, .not-to-do-img {
    width: 100%;
    border-radius: 10px;
    margin-top: 20px;
}

.testimonials {
    margin-top: 40px;
    background-color: #f8f8f8;
    padding: 20px;
    border-radius: 10px;
}

.testimonial {
    background-color: #ffcccb;
    padding: 15px;
    margin-bottom: 15px;
    border-radius: 8px;
    font-size: 1rem;
    font-style: italic;
}

.heart-container {
    text-align: center;
    margin-top: 20px;
    font-size: 2rem;
}

.heart {
    animation: heartAnimation 2s ease-in-out infinite;
    margin: 0 10px;
}

@keyframes heartAnimation {
    0% { transform: scale(1); opacity: 1; }
    50% { transform: scale(1.5); opacity: 0.5; }
    100% { transform: scale(1); opacity: 1; }
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #ffcccb;
    margin-top: 40px;
    font-size: 0.9rem;
    color: #555;
    border-radius: 10px;
}

@media (max-width: 768px) {
    header h1 {
        font-size: 2.5rem;
    }

    main {
        padding: 10px;
    }
}
