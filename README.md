# PRACTICAL-1
<!DOCTYPE html>
<html lang ="en">
    <head>
        <meta charset="UTF-8"/>
        <meta http-equiv="X-UA-Compatible"content="IE=edge"/>
        <meta name="viewport" content="width=device-width",initial scale
        <h1>Curriculum Vitae (CV)</h1>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>

        <div class ="container">
            <div class="header">
                <div class=" img-area">
                   <img src="C:\Users\DELL\Pictures\gurnoor.jpg"alt="gurnoor" width ="10" height="180">
              <h1>Gurnoor Kaur</h1>
              <h3> Student</h3>  
            </div>

            <div class= "main">
                <div class="left">
                    <h2> Personal Information</h2>
                    <p><strong>Name:</strong> Gurnoor Kaur</p>
                    <p><strong>Age:</strong> 18</p>
                    <p><strong>Email:</strong> gurnoor30kaur@gmail.com</p>
                    <p><strong>Residential Address:</strong>#3478,Sector 40-D Chandigarh</p>
                    <p><strong>Phone:</strong>7696030250</p>
                    <h2>Educational Qualification</h2>
                    <ul>
                        <li>10th :Secured 93% in CBSE</li>
                        <li>10+2 th :Secured 90% in CBSE</li>
                    </ul>
                   <h2> Education</h2>
                   <h3>B.tech in Computer Science Engineering</h3>
                   <p>Chandigarh College of Engineering and Technology,2023-27</p><br>
                </div>
                <div class="right"
                <h2>Hobbies and Interests </h2>
                <li>Reading</li>
                <li>Adventure Sports</li>
            </div>
        </div>
        * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    font-family: montserrat;
}

body {
    background: #f7f6f2;
}

.container {
    background: #e7edee;
    max-width: 800px;
    margin: 60px auto;
    height: 1250px;
    padding: 20px;
    box-shadow: 0 2px 20px rgba(0, 0, 0, 0.3);
}

.header {
    text-align: center;
}

.header h1 {
    margin-bottom: 10px;
}

.header h3 {
    text-transform: uppercase;
    font-size: 15px;
    font-weight: 500;
}

.img area {
    width: 100px;
    height: 200px;
    border-radius: 50%;
    overflow: hidden;
    margin-right :90 px;
    border: 15px groove deepskyblue
}

.img-area img {
    width:30%
    height:30%
    margin:auto
}

.main {
    display: flex;
    justify-content: flex-end;
    height:100vh;
    align-items:flex-end;
    flex-wrap: wrap;
}

.left {
    flex: 1;
    padding: 30px;
}

.left p {
    flex: 1;
    padding: 30px;
}

.left p {
    line-height: 2;
}

.left ul li {
    line-height: 2
}

h2 {
    background: #00b6c4;
    padding: 15px;
    color: #fff;
    margin: 30px;
    font-size: 20px;
    border-radius: 0 50px 50px 0;
}


