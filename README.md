# demo
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@picocss/pico@1/css/pico.min.css">
    <title>ULM Jobs Portal</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            padding: 2rem;

            background-size: cover;
        }
        nav {
            width: 100%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 2rem;
        }
        #welcome-box {
            display: flex;
            justify-content: center;
            width: 100%;
            text-align: center;
        }
        .info-box {
            width: 20%;
            height: 100px;
            margin: 10px;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 1.5rem;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            transition: transform 0.3s ease-in-out;
        }
        .info-box:hover {
            transform: translateY(-10px);
        }
        .hiring {
            background-color: red;
        }
        .seeking {
            background-color: blue;
        }
        .navigation{
          position: absolute;
          top: 7px;
          padding: 20px;
        }
        a{
            color: azure;

        }
        a:hover{
            text-decoration: none;
        }
       
    </style>
</head>
<body>
    <nav class="navigation">
            <a href="homepage.html">
            <img src="ulm_logo.png" alt="ULM Jobs Logo" style="height: 50px;">
            </a>
        <p><strong>Welcome Binod!</strong></p>
    </nav>
    <div id="welcome-box">
        <h1>WELCOME TO ULM ON-CAMPUS JOB PORTAL</h1>
    </div>
    <div style="display: flex; width: 100%; justify-content: center; ">
        <div class="info-box hiring" ><a href="hire.html">Are you Hiring?</a></div>
        <div class="info-box seeking" ><a href="jobs.html">Want a Job?</a></div>
    </div>
</body>
</html>
