<!-- _layouts/page.html -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{{ page.title | default: site.title }}</title>
    <style>
        /* Basic GitHub-like styles for dark mode */
        body {
            font-family: Arial, sans-serif;
            background-color: #0D1117; /* GitHub dark mode background */
            color: #C9D1D9; /* GitHub dark mode text color */
            padding: 20px;
            max-width: 900px;
            margin: 40px auto;
            border-radius: 6px;
            border: 1px solid #30363D; /* Border color */
        }

        a {
            color: #58A6FF; /* GitHub link color in dark mode */
        }

        h1, h2, h3, h4, h5, h6 {
            margin-top: 24px;
            margin-bottom: 16px;
            color: #FFFFFF; /* GitHub heading color in dark mode */
        }

        /* Add any other styles as needed */
    </style>
</head>
<body>
    {{ content }} <!-- This is where the content of your markdown file will be inserted -->
</body>
</html>
