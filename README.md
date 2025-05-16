# DattebayoApp

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Dattebayo API Introduction</title>
<style>
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 20px;
    background-color: #1a1a1a;
    color: #f0f0f0;
  }
  .container {
    max-width: 600px;
    margin: auto;
    background-color: #272727;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.5);
    text-align: center;
  }
  .icon {
    font-size: 4rem;
    margin-bottom: 10px;
  }
  h1 {
    margin-bottom: 0.3em;
    font-weight: 700;
  }
  p {
    line-height: 1.5;
    font-size: 1.1rem;
  }
  @media (max-width: 480px) {
    .container {
      padding: 15px;
    }
    h1 {
      font-size: 1.6rem;
    }
    p {
      font-size: 1rem;
    }
  }
</style>
</head>
<body>
  <div class="container">
    <div class="icon" role="img" aria-label="Ninja emoji">🥷</div>
    <h1>Welcome to Dattebayo API!</h1>
    <p>
      Dattebayo API is a comprehensive RESTful API designed for Naruto enthusiasts and developers alike. It provides seamless access to a vast database of Naruto-related information, including clans, characters, villages, teams, and tailed beasts.
    </p>
    <p>
      Built with modern technologies, this API simplifies integration into various applications, ensuring a smooth and immersive experience for users exploring the rich world of Naruto. Whether you're building a fan site, mobile app, or exploring Naruto lore, Dattebayo API is your gateway to ninja knowledge.
    </p>
  </div>
</body>
</html>

<div style="font-family: monospace; white-space: pre;">
&#128193; NarutoBook/<br>
├── &#128193; app/<br>
│   └── src/main/java/com/jeric/narutobook/<br>
│       └── &#128196; NarutoBookApplication.kt<br>
│<br>
├── &#128193; core/<br>
│   └── src/main/java/com/jeric/core/<br>
│       ├── &#128193; di/<br>
│       └── &#128193; util/<br>
│<br>
├── &#128193; data/<br>
│   └── src/main/java/com/jeric/data/<br>
│       ├── &#128193; local/<br>
│       │   ├── &#128193; converter/<br>
│       │   ├── &#128193; dao/<br>
│       │   ├── &#128193; entity/<br>
│       │   └── &#128196; NarutoDatabase.kt<br>
│       ├── &#128193; remote/<br>
│       ├── &#128193; mapper/<br>
│       ├── &#128193; paging_source/<br>
│       ├── &#128193; repository/<br>
│       └── &#128193; di/<br>
│<br>
├── &#128193; domain/<br>
│   └── src/main/java/com/jeric/domain/<br>
│       ├── &#128193; model/<br>
│       ├── &#128193; repository/<br>
│       └── &#128193; use_cases/<br>
│           └── &#128196; UseCases.kt<br>
│<br>
├── &#128193; presentation/<br>
│   └── src/main/java/com/jeric/presentation/<br>
│       ├── &#128193; ui/<br>
│       ├── &#128193; navigation/<br>
│       ├── &#128193; di/<br>
│       └── &#128196; MainActivity.kt<br>
</div>
