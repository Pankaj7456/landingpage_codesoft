# landingpage_codesoft
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Landing Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-image: url("mountain.jpg");
            background-size: auto;
            background-size: cover;

            /* background-repeat: no-repeat; */
            /* filter: blur(8px);
  -webkit-filter: blur(8px); */

        }


        header {
            background-color: #b45959;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        nav {
            display: inline-block;
        }

        nav ul {
            list-style: none;
            padding: 0;
        }

        nav li {
            display: inline;
            margin-right: 20px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .main-content {
            display: flex;
            justify-content: space-between;
            padding: 40px;
        }

        .main-content .column {
            flex: 1;
            padding: 20px;
            border: 1px solid #ddd;
            margin: 10px;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }

        h2 {
            color: #fff;
        }

        p {
            color: white;
        }

        .column{
            background-color: rgb(22, 57, 171);

        }
        .footer {
   position: fixed;
   left: 0;
   bottom: 0;
   width: 100%;
   background-color: red;
   color: white;
   text-align: center;
}
    </style>
</head>

<body>
    <header>
        <h1>Welcome to My Landing Page</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    <div class="container">
        <div class="main-content">
            <div class="column">
                <h2>Column 1</h2>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nihil doloribus perferendis, exercitationem
                    tenetur placeat tempore optio voluptatibus dolores eligendi ducimus sequi quos ipsum voluptate in
                    est dicta incidunt, consectetur officiis..</p>
            </div>
            <div class="column">
                <h2>Column 2</h2>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Corporis repellat sed, dolorum vel delectus
                    inventore officia! Exercitationem rerum totam dolores similique, at commodi alias cum maiores
                    cupiditate quibusdam illo fuga!
                </p>
            </div>
        </div>
    </div>

    <div class="footer">
        <p>&copy; 2023 My Landing Page</p>
      </div>
    
</body>

</html>
