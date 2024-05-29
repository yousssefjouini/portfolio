<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Youssef Jouini Website</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }
        .landing-container {
            display: flex;
            flex-direction: column;
            align-items: center; /* Center content horizontally */
            justify-content: center;
            min-height: 20vh; /* Changed to min-height to prevent content overlap */
            padding: 2rem; /* Added padding for spacing */
        }
        .logo-container {
            text-align: center; /* Center the logo horizontally */
        }
        .circular-photo {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease-in-out;
        }
        .circular-photo:hover {
            transform: scale(1.1);
        }
        .title {
            margin-top: 2rem;
            font-size: 24px;
            text-align: center; /* Center the title horizontally */
            color: #EDEADE;
        }
        .description {
            margin-top: 1rem;
            font-size: 18px;
            text-align: center;
            color: #EDEADE;
        }
    </style>
</head>
<body>
    <div class="landing-container">
        <div class="logo-container">
            <a href="https://yousssefjouini.github.io/portfolio/">
                <img src="./img/photo.jpg" class="circular-photo" alt="logo">
            </a>
        </div>
        <h1 class="title">Youssef Jouini</h1>
        <p class="description">I am a dedicated and motivated data scientist with a passion for Data Science & Machine Learning. My field of interest for the past several months have been Generative AI, especially working on retrievers building a hybrid search engine from scratch with Vespa(full end-to-end pipeline from data collection to hybrid ranking and re-ranking, optimization and deployment focusing on accuracy and latency).</p>
        <p class="description">Check out my <a href="curriculum/education">curriculum</a>, explore my <a href="./projects/projects">portfolio</a>, and get in touch through the <a href="contact">contact</a> section.</p>
    </div>
</body>
</html>
