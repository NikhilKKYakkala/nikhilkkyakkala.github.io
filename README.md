<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nikhil Yakkala | Portfolio</title>
    <link rel ="stylesheet" href="style3.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <link href='https://fonts.googleapis.com/css?family=Averia Sans Libre' rel='stylesheet'>
</head>
<body>
    <div id="header">
        <div class="container">
            <nav>
                <!-- <img src="images/logo.png" class="logo"> -->
                <span class="logo"><span class="inside">P</span>ortfolio.</span>
                <ul id="sidemenu">
                    <li><a href="#header">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#experience">Experience</a></li>
                    <li><a href="#portfolio">Projects</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <i class="fas fa-times" onclick = "closemenu()"></i>
                </ul>
                <i class="fas fa-bars" onclick = "openmenu()"></i>
            </nav>
            <div class="header-text">
                <h1>Hi, I'm <span>Nikhil Yakkala</span> </h1>
                <p> Master's in CS @ DePaul </p>
            </div>
        </div>
    </div>
<!-- ---------------------ABOUT----------------- -->
    <div id="about">
        <div class="container">
            <div class="row">
                <div class="about-col-1">
                    <img src="images/myself.jpeg" >
                </div>
                <div class="about-col-2">
                    <h1 class="sub-title">About Me</h1>
                    <p>I am a curious and a growth oriented individual with 2+ years of experience in the Software domain.<br> I love creating solutions to real life problems through software technologies.
                     </p>
                    <div class="tab-titles">
                        <p class="tab-links active-link"  onclick="opentab('skills')">Skills</p>
                        <!-- <p class="tab-links" onclick="opentab('experience')">Experience</p> -->
                        <p class="tab-links" onclick="opentab('education')">Education</p>
                    </div>
                    <div class="tab-contents active-tab" id="skills" >
                        <ul>
                            <li>
                            <span>Web Development</span><br>
                            Java Full stack with Spring Boot<br>
                            MERN / MEAN stack<br>
                            </li>
                            <li>
                            <span>Machine Learning</span><br>
                            Building ML and deep learning models using various algorithms<br>
                            Tools: scikit-learn, spaCy, TensorFlow<br>
                            </li>
                            <li>
                                <span>Big Data technologies</span><br>
                                Building highly available, fault tolerant and scalable solutions.<br>
                                Tools: Hadoop, PySpark <br>
                            </li>
                        </ul>
                    </div>
                    <div class="tab-contents" id="education">
                        <ul>
                            <li>
                            <span>Masters in Computer Science - 3.77/4</span><br>
                            University: University of Texas at Dallas <br>
                            Graduation: May 2024 <br>
                            </li>
                            <li>
                            <span>Bachelors in Electronics and Communication - 3.77/4</span><br>
                            Univeristy: JNTU-H<br>
                            Gradutation: Jun2 2021<br>
                            </li>
                            <li>
                                <span>MERN Stack Bootcamp</span><br>
                                Institution: The Hacking School<br>
                                Graduation: Dec 2021
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>


<!-- ------------------work experience------------- -->

<div id="experience">
    <div class="container">
        <h1 class="sub-title">Work Experience</h1>
        <div class="exp-work-list">
            <div class="exp-work">
                <div >
                    <h3><span>Cognizant technologies</span><span>March 2020 - July 2022</span></h3>
                    <h4>Software Developer</h4>
                    <ul>
                        <li>Worked on both Spring Boot and MERN projects</li>
                        <li>Reduced the database query time by 40% with optimized indexing.</li>
                        <li>Achieved 15% in speed of several backend functionalities.</li>
                        <li>Increased user engagement by 50% by implementing intuitive design.</li>
                    </ul>
                </div>
            </div>
            <div class="exp-work">
                <div >
                    <h3><span>Smart Interviews</span><span>Jan 2022 - April 2022</span></h3>
                    <h4>Teaching Assistant for Data Structures and Algorithms</h4>
                    <ul>
                        <li>Ensured a solid conceptual understanding among students<br> 
                        in topics like Trees, Tries, Hashing, DP, Recursion, and other related algorithms.</li>
                        <li>Helped students to overcome programming errors <br>
                            in languages like C, C++, Java, Python, JavaScript, GoLang<br>
                            on platforms like Hackerank, LeetCode, Codeforces.
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</div>
<!-- -------------------portfolio------------------- -->

<div id="portfolio">
    <div class="container">
        <h1 class="sub-title">My Projects</h1>
        <div class="tab-headings">
            <p class="tab-heading active-heading"  onclick="openprojs('wd')">Web Development</p>
            <p class="tab-heading "  onclick="openprojs('ml')">Machine Learning</p>
            <p class="tab-heading "  onclick="openprojs('bd')">Big Data</p>
            <p class="tab-heading "  onclick="openprojs('os')">Operating System</p>
        </div>
        <div class="tab-infos" id="os">
        <div class="work-list">
            <div class="work">
                <img src="images/forport-2.png" >
                <div class="pro-name">
                    <p>Unix Shell</p>
                    <p class="skills">
                        #C Programming  <br>#Multi-process concept
                    </p>
                </div>
                <div class="layer">
                    <h3>Baby Unix shell</h3>
                    <p>Developed a program to replicate basic functionalities of a Unix shell.</p>
                    <a href="https://github.com/poojaminna/baby-unix-shell.git"><i class="fab fa-github" ></i>  </a>
                </div>
            </div>
            <div class="work">
                <img src="images/forport-2.png" >
                <div class="pro-name">
                    <p>Sleeper Barber Variant</p>
                    <p class="skills">
                        #C Programming  <br>
                        #Semaphore<br>
                        #mutex <br>
                        #Multi-process concept<br>
                    </p>
                </div>
                <div class="layer">
                    <h3>Seeking Tutor Problem</h3>
                    <p>Created a program to exhibit concurrent thread programming. Implemented a variant
                        of sleeper barber problem.</p>
                    <a href="https://github.com/poojaminna/sleeper-barber-variant.git"><i class="fab fa-github" ></i>  </a>
                </div>
            </div>
        </div>
        </div>
        <div class="tab-infos active-info" id="wd">
        <div class="work-list"> 
            <div class="work">
                <img src="images/forport-2.png" >
                <div class="pro-name">
                    <p>E-commerce WebApp</p>
                    <p class="skills">
                        #React.js  <br>
                        #JavaScript<br>
                        #MongoDB<br>
                        #Node.js 
                    </p>
                </div>
                <div class="layer">
                    <h3>E Commerce Web Application</h3>
                    <p>Built a full fledged web application. Implemented user and admin functionalities,
                        designed database schema to store inventory and integrated payment gateway</p>
                    <a href="https://github.com/poojaminna/e-commerce-web-application"><i class="fab fa-github" ></i>  </a>
                </div>
            </div>
            <div class="work">
                <img src="images/forport-2.png" >
                <div class="pro-name">
                    <p>Travel Website</p>
                    <p class="skills">
                        #HTML, CSS  <br>
                        #JavaScript<br>
                        #MySQL<br>
                        #PHP
                    </p>
                </div>
                <div class="layer">
                    <h3>Booking Website </h3>
                    <p>Built a website where users can book flights, hotels, rental cars. Focussed on backend.</p>
                    <a href="https://github.com/poojaminna/booking-website"><i class="fab fa-github" ></i>  </a>
                </div>
            </div>
            <div class="work">
                <img src="images/forport-2.png" >
                <div class="pro-name">
                    <p>Beginner project-1</p>
                    <p class="skills">
                        #HTML, CSS <br>
                        #JavaScript<br>
                    </p>
                </div>
                <div class="layer">
                    <h3>Early stage small project - 1</h3>
                    <p>Timer , Clock, and Stop watch</p>
                    <a href="https://github.com/poojaminna/poojaminna.github.io/tree/main/timer"><i class="fab fa-github" ></i>  </a>
                    <a href="https://poojaminna.github.io/timer/"><i class="fas fa-play"></i>  </a>
                </div>
            </div>
            <div class="work">
                <img src="images/forport-2.png" >
                <div class="pro-name">
                    <p>Beginner project-2</p>
                    <p class="skills">
                        #HTML, CSS <br>
                        #JavaScript<br>
                    </p>
                </div>
                <div class="layer">
                    <h3>Early stage small project - 2</h3>
                    <p>Virtual Keyboard</p>
                    <a href="https://github.com/poojaminna/poojaminna.github.io/tree/main/keyboard"><i class="fab fa-github" ></i>  </a>
                    <a href="https://poojaminna.github.io/keyboard/"><i class="fas fa-play"></i>  </a>
                </div>
            </div>
            <div class="work">
                <img src="images/forport-2.png" >
                <div class="pro-name">
                    <p>Beginner project-3</p>
                    <p class="skills">
                        #HTML, CSS <br>
                        #JavaScript<br>
                    </p>
                </div>
                <div class="layer">
                    <h3>Early stage small project - 3</h3>
                    <p>Shopping cart basic functionalities</p>
                    <a href="https://github.com/poojaminna/poojaminna.github.io/tree/main/fshoppingCart"><i class="fab fa-github" ></i>  </a>
                    <a href="https://poojaminna.github.io/fshoppingCart/"><i class="fas fa-play"></i> </a>
                </div>
            </div>
            <div class="work">
                <img src="images/forport-2.png" >
                <div class="pro-name">
                    <p>Beginner project -4</p>
                    <p class="skills">
                        #HTML, CSS <br>
                        #JavaScript<br>
                    </p>
                </div>
                <div class="layer">
                    <h3>Early stage small project - 4</h3>
                    <p>Binary to Decimal Converter</p>
                    <a href="https://github.com/poojaminna/poojaminna.github.io/tree/main/BtoDconverter"><i class="fab fa-github" ></i>  </a>
                    <a href="https://poojaminna.github.io/BtoDconverter/"><i class="fas fa-play"></i></a>
                </div>
            </div>
            <div class="work">
                <img src="images/forport-2.png" >
                <div class="pro-name">
                    <p>Beginner project-5</p>
                    <p class="skills">
                        #HTML, CSS <br>
                        #JavaScript<br>
                    </p>
                </div>
                <div class="layer">
                    <h3>Early stage small project - 5</h3>
                    <p>Golden ratio demonstration</p>
                    <a href="https://github.com/poojaminna/poojaminna.github.io/tree/main/golden-ratio"><i class="fab fa-github" ></i>  </a>
                    <a href="https://poojaminna.github.io/golden-ratio/"><i class="fas fa-play"></i>  </a>
                </div>
            </div>
        </div>    
        </div>
        <div class="tab-infos" id="bd">
        <div class="work-list">
            <div class="work">
                <img src="images/forport-2.png" >
                <div class="pro-name">
                    <p>Classification problem</p>
                    <p class="skills">
                        #Naive Bayes <br>
                        #PySpark<br>
                        #Hadoop 
                    </p>
                </div>
                <div class="layer">
                    <h3>Naive Bayes for Big Data</h3>
                    <p>Implemented Naive Bayes from scratch for Big Data</p>
                    <a href="https://github.com/poojaminna/naive-bayes-for-big-data"><i class="fab fa-github" ></i>  </a>
                </div>
            </div>
            <div class="work">
                <img src="images/forport-2.png" >
                <div class="pro-name">
                    <p>Stock Market Prediction</p>
                    <p class="skills">
                        #Recurrent Neural N/w <br>
                        #PySpark<br>
                        #Hadoop 
                    </p>
                </div>
                <div class="layer">
                    <h3>RNN for Stock Market Prediction</h3>
                    <p>Predicted Stock Market value for a company using RNN.</p>
                    <a href="https://github.com/poojaminna/stock-market-prediction-with-rnn"><i class="fab fa-github" ></i>  </a>
                </div>
            </div>
            <div class="work">
                <img src="images/forport-2.png" >
                <div class="pro-name">
                    <p>Document Search</p>
                    <p class="skills">
                        #Tf - idf <br>
                        #PySpark<br>
                        #Hadoop 
                    </p>
                </div>
                <div class="layer">
                    <h3>Search Engine for Movie Plot summaries</h3>
                    <p>Suggesting movie names by searching for search words in abundant movie summaries</p>
                    <a href="https://github.com/poojaminna/movie-plot-idf."><i class="fab fa-github" ></i>  </a>
                </div>
            </div>
        </div>
        </div>
        <div class="tab-infos" id="ml">
        <div class="work-list">    
            <div class="work">
                <img src="images/forport-2.png" >
                <div class="pro-name">
                    <p>Logistic regression</p>
                    <p class="skills">
                        #Python <br>
                    </p>
                </div>
                <div class="layer">
                    <h3>Logistic regression.</h3>
                    <p>Implemented logitisc regression from scratch.</p>
                    <a href="https://colab.research.google.com/drive/1e8NdNYWuatxm0QZzPGILjc38FXj1qT9_"><i class="fas fa-external-link-alt"></i>
                    </a>
                </div>
            </div>
            <div class="work">
                <img src="images/forport-2.png" >
                <div class="pro-name">
                    <p>Decision Tree</p>
                    <p class="skills">
                        #Python <br>
                    </p>
                </div>
                <div class="layer">
                    <h3>Decision Tree</h3>
                    <p>Implemented id3 Decision Tree from scratch.</p>
                    <a href="https://colab.research.google.com/drive/18SLo2Vs9H3EAh5juKD54FWNCU5ziaPQq#scrollTo=3IZfYOX_9Wtt"><i class="fas fa-external-link-alt"></i>
                    </a>
                </div>
            </div>
            <div class="work">
                <img src="images/forport-2.png" >
                <div class="pro-name">
                    <p>Naive Bayes</p>
                    <p class="skills">
                        #Python <br>
                    </p>
                </div>
                <div class="layer">
                    <h3>Naive Bayes</h3>
                    <p>Implemented Multinomial Naive Bayes from scratch.</p>
                    <a href="https://colab.research.google.com/drive/1AZjX_ZluPrbrTfsUJczUHZ8mOUyTqdCf"><i class="fas fa-external-link-alt"></i>
                    </a>
                </div>
            </div>
            <div class="work">
                <img src="images/forport-2.png" >
                <div class="pro-name">
                    <p>Ensemble methods</p>
                    <p class="skills">
                        #Python <br>
                    </p>
                </div>
                <div class="layer">
                    <h3>Ensemble methods</h3>
                    <p>Implemented bagging and boosting with decision tree from scratch. </p>
                    <a href="https://colab.research.google.com/drive/10UuhvIfY6oJD90i_B9mUgvsmb-_b7fNZ"><i class="fas fa-external-link-alt"></i>
                    </a>
                </div>
            </div>
            </div>
        </div>
    </div>
</div>


<!-- ----contact--- -->

<div id="contact">
    <div class="container">
        <div class="row">
            <div class="contact-left">
                <h1 class=""sub-title>Contact Me</h1>
                <p><i class="fas fa-paper-plane"></i>poojaminna0322@gmail.com</p>
                <p><i class="fas fa-phone-square-alt"></i>+1 (469) 853-8016</p>
                <div class="social-icons">
                    <a href=""><i class="fab fa-linkedin" ></i></a>
                    <a href="#"><i class="fab fa-github" ></i>  </a>
                    <a href=""><i class="fab fa-instagram"></i></a>
                </div> 
                <a href="images/Pooja Minna - Resume.pdf" download class="btn btn2">Download Resume</a>
            </div>
            <div class="contact-right">
                <form name="submit-to-google-sheet">
                    <input type="text" name = "Name" placeholder="Your name" required>
                    <input type="email" name="Email" placeholder="Your email" required>
                    <textarea name="Message"  rows="6" placeholder="Your Message"></textarea>
                    <button type="submit" class="btn btn2">Submit</button>
                </form>
                <span id="msg"></span>
            </div>
        </div>
    </div>
    <div class="copyright">
        <p>&copy Pooja Minna.</p>
    </div>
</div>
    <script>
        var tablinks = document.getElementsByClassName("tab-links");
        var tabcontents = document.getElementsByClassName("tab-contents");
        function opentab(tabname){
            for(tablink of tablinks){
                tablink.classList.remove("active-link")
            }
            for(tabcontent of tabcontents){
                tabcontent.classList.remove("active-tab")
            }
            event.currentTarget.classList.add("active-link");
            document.getElementById(tabname).classList.add("active-tab");
        }
        var tabheading = document.getElementsByClassName("tab-heading");
        var tabinfos = document.getElementsByClassName("tab-infos");
        function openprojs(tabproj){
            for(projectwindow of tabheading){
                projectwindow.classList.remove("active-heading")
            }
            for(tabinfo of tabinfos){
                tabinfo.classList.remove("active-info")
            }
            event.currentTarget.classList.add("active-heading");
            document.getElementById(tabproj).classList.add("active-info");
        }
    </script>
    <script>
        var sidemenu = document.getElementById("sidemenu");
        function openmenu(){
            sidemenu.style.right = "0";
        }
        function closemenu(){
            sidemenu.style.right = "-200px";
        }
    </script>

<script>
    const scriptURL = 'https://script.google.com/macros/s/AKfycbzYt7DoBiMhcavwERpQbG2OILA7tgorx03W2F9kD43l3DV19-uO5FbYtFfrgbWVr1NO/exec'
    const form = document.forms['submit-to-google-sheet']
    const msg = document.getElementById("msg");
    form.addEventListener('submit', e => {
      e.preventDefault()
      fetch(scriptURL, { method: 'POST', body: new FormData(form)})
        .then(response => {
            msg.innerHTML="Your details have been submitted successfully!"
            setTimeout(function(){
                msg.innerHTML = "";
                
            }, 3000)
            form.reset();
        })
        .catch(error => console.error('Error!', error.message))
    })
  </script>
</body>
</html>