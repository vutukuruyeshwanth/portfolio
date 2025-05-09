# portfolio
<!DOCTYPE html>

<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
      header{
    background-color: rgb(27, 149, 242);
    height: 100vh;
    color: white;
    display:flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;

}
body{
    margin: 0px;
    font-size: 15px;
    background-color:rgb(236, 240, 244);

}
*{
    font-family: monospace;
    

    
}

header h1{
    margin: 0px;
    color: white;

}

h1{
    font-size: 3rem;
    color: rgb(72, 185, 242);
}
.button{
    height: 30px;
    width: 100px;
    border: none;
    border-radius: 10px;
}

.button:hover{
    background-color: darkblue;
    cursor: pointer;
    color: white;
}

img{
    height: 170px;
    width: 150px;
    border: 1px solid black;
}

section{
    height: 100vh;
    border: 1px solid grey;
    border-radius: 20px;
    margin-bottom: 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
}

#ContactMe{
    height: 50vh;
}

#MyProjects{
    height: 40vh;
}

#MySkills{
    height: 120vh;
}

div{
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    margin-top: 0px;
    gap: 2rem;
    margin-bottom: 2rem;
    unicode-bidi: isolate;
}

#Programming{
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: 40px;
    border: 1px solid grey;
    padding: 20px 40px;
    text-align: center;
    width: 300px;
    height: 30vh;
    flex: 1;
}

#technologies{
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: 40px;
    border: 1px solid grey;
    padding: 20px 40px;
    text-align: center;
    width: 300px;
    height: 30vh;
    flex: 1;
}

#system{
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: 40px;
    border: 1px solid grey;
    padding: 20px 40px;
    text-align: center;
    width: 300px;
    height: 30vh;
    flex: 1;
}


main{
    padding: 20px;
}

.sub{
    height: 40px;
    width: 80px;
    border: 1px solid black;
    border-radius: 10px;
    cursor: pointer;
    color: white;
    background-color: #2196f3;
}

.sub:hover{
    background-color: #1178cd;
}

input{
    border-radius: 5px;
    border: 3px solid lightslategray;
    height: 20px;
}

p .click{
    cursor: pointer;
}

footer{
    height: 150px;
    background-color: black;
    color: gray;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
}

.fixed{
    height: 70px;
    width: 70px;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    color: white;
    background-color: #2196f3;
    position: fixed;
    bottom: 10px;
    right: 10px;
}

header a{
    margin: 10px;
}

html{
    scroll-behavior: smooth;
}

h3{
    text-align: center;
}



.email-icon{
    height: 3rem; 
    width: 3rem;
    border: none;
}

.linkedin-icon{
    height: 3rem;
    width: 3rem;
    border: none;
}

.Facebook-icon{
    height: 3rem;
    width: 3rem;
    border: none;
}

.Instagram-icon{
    height: 3rem;
    width: 3rem;
    border: none;
}

.link{
    color: black;
    font-size: large;
    text-decoration: none;
    border: none;
    cursor: pointer;
}

.link:hover{
    background-color: rgb(188, 188, 188);
    color: black;
    border-radius: 2rem;
    text-decoration: underline;
}
    </style>
</head>

<body>
       
    
    <header id="Home"> 
        
        <h1>Welcome to my Portfolio</h1>

    <a href="#Aboutme">
        <button class="button">
            About
        </button>
    </a>
    
    <a href="#MySkills">
        <button class="button">
            Skills
        </button>
    </a>

    <a href="#MyProjects">
        <button class="button">
            Projects
        </button>
    </a>

    <a href="#ContactMe">
        <button class="button">
            Contact
        </button>
    </a>

    </header>

<main>
    <section id="Aboutme">

    <h1>Yeshwanth Vutukuru</h1>
    <img src="myimage.jpg" height="500" width="400">
    <p>iam i a passionate web developer with focus on frontend and backend technologies</p>
    <p>iam currently perssuing my b-tech in <i>Gandhi Institute of Technology and Management</i> vizag</p>
    <p>i have learnt web development by attending to some course like <br> coursera, NPTL, youtube and more..</p>
    <p>you can <strong class="click">Click here</strong> to check my work on the web development</p>

    </section>

    <section id="MySkills">

        <h1>Explore My Skills</h1>
        <div id="allsections">

        <section id="Programming">
    <ol>
        <h3>Programming Languages</h3><br>
        <li><b>C++</b>-Intermidate</li>
        <li><b>Java</b>-Intermidate</li>
        <li><b>Python</b>-Intermidate</li>
    </ol>
        </section>

        <section id="technologies">
    <ol>
        <h3>Web Technologies</h3><br>

        <li><b>HTML</b>-Experienced</li>
        <li><b>CSS</b>-Experienced</li>
        <li><b>JavaScript</b>-Basic</li>
        <li><b>SQL</b>-Basic</li>
    </ol>
        </section>

        <section id="system">
    <ol>
        <h3>System Skills</h3><br>
        <li><b>Git</b>-Basic</li>
    </ol>
        </section>

        </div>

    </section>

    <section id="MyProjects">

        <h2>My Projects</h2>
        <table bgcolor="black">

            <tr bgcolor="grey">
                <th>Projects</th>
                <th>Discription</th>
            </tr>

            <tr bgcolor="lightgrey">
                <td>Portfolio</td>
                <td>I have built a Portfolio web site by using HTML,CSS & JavaScript </td>
            </tr>

            <tr bgcolor="lightgrey">
                <td>Restaurant Management</td>
                <td>I have bulit a restaurant adminstrative system using the python concepts</td>
            </tr>

        </table>

    </section>
    <section id="ContactMe">
    
        <h1>Contact Me</h1>
    <p class="contact-para">Feel free to get in touch with me</p>
    <div class="contact-container">
        <div class="mail">
            <img src="email_light.png" alt="email" 
            class="email-icon">
            <p>
                <a href="mailto:yeshwanthvutukuru31@gmail.com">
                    <button class="link">
                        yeshwanthvutukuru31@gmail.com
                    </button>
                </a>
            </p>
        </div>

        <div class="linkedin">
            <img src="linkedin_light.png" 
            alt="linkedIn" class="linkedin-icon">
            <p>
                <a href="https://www.linkedin.com/in/yeshwanth-vutukuru">
                    <button class="link">
                        Linkedin
                    </button>
                </a>
            </p>
        </div>
    </div>
    <div class="contact-container-link">
        <div class="facebook">
            <img src="facebook-new.png" 
            alt="Facebook" class="Facebook-icon">
            <p>
                <a href="https://www.facebook.com/yeshwanth.vutukuru">
                    <button class="link">
                        Facebook
                    </button>
                </a>
            </p>
        </div>

        <div>
            <img src="insta_icon.png" 
            alt="Instagram" class="Instagram-icon">
            <p>
                <a href="https://www.instagram.com/yeshwanthvutukuru" >
                    <button class="link">
                        Instagram
                    </button>
                </a>
            </p>
        </div>
    </div>
    </section>
</main>

<a href="#Home">
     <button type="submit" class="fixed">HOME</button>
</a>

<footer>Copyright © 2025 Vutukuru Yeshwanth. All Rights Reserved</footer>
</body>

</html>
