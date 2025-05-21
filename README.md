<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>StillLeben | Doğada Dinginlik</title>
  <style>
    body {
      margin: 0;
      font-family: 'Helvetica Neue', sans-serif;
      background-color: #f5f5f5;
      color: #333;
    }
    header {
      background: url('https://source.unsplash.com/1600x900/?nature,calm') no-repeat center center/cover;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      color: white;
    }
    header h1 {
      font-size: 3em;
      margin-bottom: 0.2em;
    }
    header p {
      font-size: 1.2em;
      max-width: 600px;
    }
    nav {
      background: white;
      padding: 1em;
      display: flex;
      justify-content: center;
      gap: 2em;
      border-bottom: 1px solid #ddd;
    }
    nav a {
      text-decoration: none;
      color: #444;
      font-weight: bold;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1em;
      padding: 2em;
    }
    .gallery img {
      width: 100%;
      border-radius: 
