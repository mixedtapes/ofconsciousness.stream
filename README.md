<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>My Google Docs Website</title>
  
  <!-- Basic styling -->
  <style>
    /* Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
      background-color: #fdfdfd;
      color: #111;
      line-height: 1.6;
    }

    header {
      position: fixed;
      top: 0;
      width: 100%;
      padding: 1rem 2rem;
      background: rgba(255, 255, 255, 0.9);
      backdrop-filter: blur(6px);
      box-shadow: 0 1px 4px rgba(0,0,0,0.05);
      z-index: 10;
    }

    header h1 {
      font-size: 1.25rem;
      font-weight: bold;
      letter-spacing: 1px;
    }

    iframe {
      width: 100%;
      height: 100vh;
      border: none;
      margin-top: 60px; /* offset for header */
    }
  </style>
</head>
<body>
  
  <header>
    <h1>My Google Docs Website</h1>
  </header>

  <!-- Embed your Google Doc here -->
  <iframe src=https://docs.google.com/document/d/e/2PACX-1vS6wvLu0-Mhk7vP0VL5gpoAWXRokk_VwofbQk1gi_CDb13PH68CLFW_Maqw153twt5inciGjmtjIbcB/pub?embedded=true"></iframe>

</body>
</html>
