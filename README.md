<head>
    <style>
        *{
            --theme-color: #1e88e5;
            --background-color: rgba(0, 0, 0, 0.04);
        }
        img{
            border-radius: 5px;
        }
        .projects{
            display: flex;
            justify-content: center;
            flex-flow: row nowrap;
        }
        .projects>*{
            text-decoration: none;
        }
        .card{
            background-color: var(--background-color);
            padding: rem;
            margin: 1rem;
            border-radius: 5px;
            width: 33%;
            /* background-color: red; */
        }
        .card .content{
            padding: 1rem;
        }
        #contact{
            width: 100%;
            display: flex;
            flex-flow: row nowrap;
            justify-content: center;
        }
        .contact-list{
            width: auto;
            list-style-type: none;
            display: flex;
            flex-flow: row nowrap;
            align-items: center;
        }
        .contact-item{
            text-decoration: none;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }
        .contact-item > a{
            flex: 0 0 auto;
            padding: 12px;
            margin: 6px;
            overflow: visible;
            font-size: 1.5rem;
            text-align: center;
        }
        .contact-item > a > i{
            width: 100%;
        }
    </style>

</head>

# Hello There
I am Lars Bloemers, an Embedded Software Engineer from the Netherlands, interested in robotics, embedded systems, and IoT. I have always been fascinated by technology as a kid. As an adult, I wish to explore the possibilities it has to offer. 

If you have any questions/feedback about me or my work, feel free to [contact](#contact) me!


## Projects

<!-- All project images must be 400x300 -->
<section class="projects">
    <a 
        class="card" 
        href="https://gitlab.com/Larsbl00/ros2-turtlebot-3-navigation" target="_blank"
    >
        <div >
            <div class="thumbnail"><img src="img/ros2-navigation.webp"/></div> 
            <div class="content">
                <h2>ROS2 Navigation</h2>
                <p>
                    Using ROS 2, Turtlebot 3 and Navigation 2, we programmed a robot to drive from point to point without hitting any obstacles.
                    When you are using the 2d GUI, you can mark points for the robot to travel between.
                    These are then performed in the 3d simulation.        
                </p>
            </div>
        </div>
    </a>
    <a  
        class="card"
        href="https://github.com/Larsbl00/OI3-ComputerVision" target="_blank"
    >
        <div>
            <div class="thumbnail"><img src="img/lloid.webp"/></div> 
            <div class="content">
                <h2>L.L.O.I.D.</h2>
                <p>             
                    L.L.O.I.D. or otherwise known as the 'Locomotive Lidar Operated Interactive Drone', is an interactive autonomous robot.
                    For this project, I was responsible for the facial recognition, so the robot knows where people are located.
                </p>
            </div>
        </div>
    </a>
    <a  
        class="card"
        href="https://github.com/Larsbl00/MonsterBattle" 
        target="_blank"
    >
        <div>
            <div class="thumbnail"><img src="img/monster-battle.webp"/></div> 
            <div class="content">
                <h2>Monster Battle</h2>
                <p>
                    Monster Battle is a small turn-based game programmed to be displayed in the terminal.
                    The project came to be, to familiarize myself more with modern C++.
                </p>
            </div>
        </div>
    </a>
</section>

<!-- Create a banner below the content with all contact icons -->
<span id="contact">
    <ul class="contact-list">
        <li class="contact-item">
            <a href="mailto:larsbloemers@gmail.com" target="_blank">  
                <i class="fa fa-envelope" aria-hidden="true"></i>
            </a>
        </li>
        <li class="contact-item">
            <a href="https://www.linkedin.com/in/lars-bloemers/" target="_blank">  
                <i class="fa fa-linkedin-square" aria-hidden="true"></i>
            </a>
        </li>
        <li class="contact-item">
            <a href="https://www.youtube.com/c/LarsBl" target="_blank">  
                <i class="fa fa-youtube-play" aria-hidden="true"></i>
            </a>
        </li>
        <li class="contact-item">
            <a href="https://github.com/Larsbl00" target="_blank">  
                <i class="fa fa-github" aria-hidden="true"></i>
            </a>
        </li>
        <li class="contact-item">
            <a href="https://gitlab.com/Larsbl00" target="_blank">  
                <i class="fa fa-gitlab" aria-hidden="true"></i>
            </a>
        </li>
    </ul>
</span>