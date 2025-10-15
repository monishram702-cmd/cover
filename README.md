# Ex.06 Book Front Cover Page Design
## Date:15/10/2025

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #eaeaea;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: 'Helvetica Neue', sans-serif;
    }

    .book-cover {
      width: 320px;
      height: 480px;
      background: linear-gradient( #000000, #24334ea4, #000000);
      background-size: 200% 200%;
      animation: gradientShift 8s ease infinite;
      color: #fff;
      border-radius: 12px;
      box-shadow: 0 15px 25px rgba(0,0,0,0.3);
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 30px;
      text-align: center;
    }

    @keyframes gradientShift {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    .content {
      max-width: 90%;
    }

    .title {
      font-size: 2.2em;
      font-weight: bold;
      margin-bottom: 100px;
    }

    .divider {
      width: 60px;
      border: 1px solid #fff;
      margin: 10px auto;
    }

    .subtitle {
      font-size: 1.1em;
      font-style: italic;
      margin-bottom: 20px;
    }

    .author {
      font-size: 1em;
      letter-spacing: 1px;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div class="content">
      <h1 class="title">The Shadow Throne</h1>
      <p class="subtitle">Legacy and Fire and Steel</p>
      <hr class="divider">
      <p class="author">by Monish Ram</p>
    </div>
  </div>
</body>
</html>

```

## OUTPUT:

<img width="1920" height="1080" alt="Screenshot (30)" src="https://github.com/user-attachments/assets/ae48066f-4eaa-4a19-96a0-811e290d0dc8" />


## RESULT:

The program for designing book front cover page using HTML and CSS is completed successfully.
