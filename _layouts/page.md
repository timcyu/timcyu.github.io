<!-- _layouts/page.html -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{{ page.title | default: site.title }}</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #0D1117;
            color: #C9D1D9;
            padding: 20px;
            max-width: 900px;
            margin: 40px auto;
        }

        a {
            color: #3f84e4; 
            text-decoration: none; /* Remove underline from links */
        }

        /* Heading styles */
        h1, h2, h3, h4, h5, h6 {
            margin-top: 24px;
            margin-bottom: 16px;
            color: #FFFFFF; 
        }

        h1, h2 {
            border-bottom: 1px solid #30363D; 
            padding-bottom: 8px; 
        }
    </style>
</head>
<body>
    {{ content }}
</body>
</html>

