<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>portfilo</title>
    <style>
        body{
            font-family: Arial,sans-serif;
            margin: 0px;
            padding: 0px;
            background-color: rgb(137, 230, 217);
        }
        header{
            display: inline-block;
            background-color: #232427;
            color:#ffffff;
            text-align: center;
            padding: 2rem 0;
            width: 100%;
            
        
        }

        .header-content h1{
            font-size: 2.5rem;
           text-align: center;
        }
        p{
            padding-top: -70px;
            font-size: 1.25rem;
            margin: 0px;
            margin-bottom: 40px;
        }
       
        nav{
            background-color: #333;
            color: #fff;
            display: inline;
            text-align: center;
        }
        nav ul{
            padding: 25px;
            margin-top: 20px;
            background: #333;
            list-style-type: none;
        }
        nav ul li{
        display: inline;
        margin: 0 20px;
        }
        nav ul li a{
        
        text-decoration: none;
        color:#ffffff;
        }
        #about{
            border: 5px;
            border-color: #333;
        }
        .section-content {
            background-color: #fff;
            padding: 2rem;
            margin: 1rem;
            border: 20px;
            border-color: #223c42;
            box-shadow: 0 0 10 ;
        }
        #resume{
            text-align: center;
        }
        .download-button
        {
            background-color: #223c42;
            color: #fff;
            padding: 10px;

        }
        footer {
            text-align: center;
            padding: 1rem 0;
            background-color: #333;
            color: #fff;
        }
        ul {
            list-style-type: disc;
            padding-left: 20px;
        }            
       
       </style>

</head>  
<body>
    <header>
     <div class="header-content">
       
        <h1>MUTHULAKSHMI K</h1>
        <P>Passionate on Web Developement</P>
     </div>

    </header>
<nav>
    <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#education">Education</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Project</a></li>
        <li><a href="#resume">Resume</a></li>
    </ul>
</nav>
    
<section id="about">
    <div class="section-content">
        <h2>About Me</h2>
        <p>Hello  Everyone! This MUTHULAKSHMI K and i am computer student</p>
    </div>
</section>

<section id="education">
    <div class="section-content">
        <h3>BCA</h3>
        <p>Bharathidhasan university,Trichy.</p>
    </div>
</section>

<section id="skills">
    <div class="section-content">
    <h2>Skills</h2>
    <ul>
        <li>Web developement</li>
        <li>MS Office</li>
    </ul>    
    </div>

</section>

<section id="resume">
    <div class="section-content">
        <h2>Resume</h2>
        <a href="">Download</a>

    </div>
</section>

<footer>
    <p>&copy; 2023 MUTHULAKSHMI K</p>
</footer>

<script>
    document.querySelectorAll('a[herf^="#"]').forEach(anchor =>{
        anchor.addEventListener('click',function(e){
            e.preventDefault();
            const targetId = this.getAttribute('herf').substring(1);
            const targetElement = document.getElementById(targetId);

            if(targetElement){
                window.scrollTo({
                    top: targetElement.offsetTop,
                    behavior: 'smooth'
                });

            }
        });
    });
</script>



</body>
</html>
