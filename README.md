<!DOCTYPEhtml>
	<head>
		<meta charset="UTF-8"/>
		<title> My First Website</title>
	<link rel="stylesheet" href="../CSS/MyFirstWebsite.css"/>
	<link rel="stylesheet" href="../CSS/Normalize.css"/>
	</head>
	 
	<style>
		/* Start Main rules */

body
{
    height: 4000px;
    color: black;
}

.container
{
    width:1000px;
    margin: auto;
    overflow: hidden;
}

.clearfix{clear: both}

/* End Main rules */


/* Start Header */
.header .slider 
{
    background-image: url('../images/Crisis-Code_Photo-Shunyu-Fan-1170x600.jpg');
    background-size:cover; /*CSS3*/
}

.header .slider .intro
{
    height: 600px;
    text-align: center;
    padding-top: 200px;
}

.header .slider .intro h2
{
    color: white;
    margin: 0px;
    border-top: 3px solid white;
    border-bottom: 3px solid white;
    font-size: 75px;
}

.header .slider .intro button
{
    background: none;
    color: white;
    margin-top:30px;
    font-size: 20px;
    font-weight: bold;
    border: 2px solid white;
    padding: 10px 20px;
}

.header .navbar
{
    background-color: #252F31;
    color: white;
    overflow: hidden;
}

.header .navbar a
{
    color: white;
    text-decoration: none;
}

.header .navbar ul li a:hover
{
    color: #2BC975;
}

.header .navbar h2
{
    float:left;
    text-transform: uppercase;
}

.header .navbar h2 span
{
    color:#2ecc71;
}

.header .navbar ul
{
    list-style: none;
    padding-left: 0px;
    float: right;
}

.header .navbar ul  li 
{
    float: left;
    padding:10px;
}

/* End Header */


    /* Start features */
.features
{
    overflow: hidden;
    padding-top: 30px;
    padding-bottom: 30px;
}

.features   .feat
{
    float:left;
    width:33%;
    height: 150px; 
  
}

.features   .feat p
{
    line-height: 20px;
    color: #888;
}

.features   .feat h3
{
    color:#555 ;
    text-transform: capitalize;
}

    /* End features */


    /* Start About Me */
    .about-me
    {
        overflow: hidden;
        background-color: #F2F2F2;
    }
    
    .about-me .image
    {
        overflow: hidden;
        float: left;
        width: 40%;
    }
    
    
    .about-me .info
    {
        float: left;
        width: 60%;
    }
    
    .about-me .info h2
    {
        margin: 40px 0px 20px 40px;
        color: #555;
    }
    
    .about-me .info > p
    {
        margin: 0 0 10px 40px;
        line-height: 1.7;
        color: #555;
    }
    
    .about-me .info p:last-of-type
    {
        margin:40px 0px 20px 40px;
        color: #555;
    }
    
    .about-me .hobbies
    {
        overflow: hidden;
        float: left; 
        margin:40px 0 0 40px;
        width: 800px;
    }
    
    
    
    .about-me .hobbies h3
    {
        color: #555;
    }
    
    .about-me .hobbies div
    {
        float: left;
        width: 40%;
        min-height: 100px;
    }
    
    .about-me .info .hobbies p
    {
        margin-top: -2px;
        line-height: 1.7;
        margin-left: 0;
        color: #888;
    }

    .about-me .hobbies .icon
    {
        width: 62px;
        margin-right:10px ;
    }
    
    .about-me .info .hobbies .icon img
{
    max-width: 100%;
}


    
    /* End About Me */

    /* Start My Skills */
        .my-skills
        {
            padding-top: 30px;
            padding-bottom: 50px;
            overflow: hidden;
        }

        .my-skills .skills,
        .my-skills .progress
        {
            width: 50%;
            float: left;
        }

        .my-skills .skills > p
        {
            margin-bottom: 30px;
            color: #888;
        }

        .my-skills .skills button
        {
            background: none;
            padding: 10px 20px;
            border: 3px solid #2DCC70;
            margin-top:20px ;
            color: #2DCC70;
            font-weight: bold;
            text-transform: uppercase;
        }

        .my-skills .skills h2
        {
            color: #555;
        }

        .my-skills .progress .technique h3
        {
            color: #555;
        }

        .my-skills .progress .technique
        {
            margin-left: 50px;
        }

        .my-skills .progress .technique div
        {
            background-color: #F2F2F2;
            height: 25px;
        }

        .my-skills .progress .technique div span
        {
            background-color:#2DCC70 ;
            width: 80%;
            height: 25px;
            display: block;
            line-height: 25px; /* هيخلي النسبة في النصف عشان الطول 25 بكسل هوا كمان */
            text-align: right;
            color: white;
            font-weight: bold;
        }

    /* End My Skills */
    
        /*Start Resume*/
        .resume
        {
            background-color: #F2F2F2;
            text-align: center;
        }

        .resume h2
        {
           color:#555 ; 
        }

        .resume p 
        {
            color: #888;
            line-height: 1.7;
        }

        .resume button
        {
            background: none;
            padding: 10px 20px;
            border: 3px solid #2DCC70;
            margin-top:20px ;
            color: #2DCC70;
            font-weight: bold;
            text-transform: uppercase;
        }

        .resume .resume-two
        {
            padding: 50px 70px 70px 70px;
        }
        /*End Resume*/

     /* Start My Education */
     .my-education
     {
         padding-top: 30px;
         padding-bottom: 30px;
         overflow: hidden;
     }

     .my-education .main,
     .my-education .exp
     {
         width: 50%;
         float: left;
     }

     .my-education .main h2
     {
         color: #555;
     }

     .my-education .main p
     {
        color: #888;
        line-height: 1.6;
     }

     .my-education .main p:last-of-type
     {
         margin-top: 35px;
     }

     .my-education .exp
     {
         margin-top: 46px;
        
     }

     .my-education .exp h3
     {
         color: #555;
         text-transform: uppercase;
     }

     .my-education .exp p
     {
         color: #888;
         line-height: 1.6;
     }

     .my-education .exp button
     {
         background-color:#2DCC70 ;
         border: 1px solid #2DCC70;
         color: white;
         margin-bottom: 10px;
         margin-top: 10px;
     }

     .my-education .exp h4
     {
         margin-top: 40px;
         color: #555;
     }

     .my-education .exp p:last-of-type
     {
         margin-bottom: 100px;
     }

     .exp-two h4 
     {
         color: #555;
         text-transform: uppercase;
         margin-top: 75px;
     }

     .exp-two button
     {
        background-color:#2DCC70 ;
        border: 1px solid #2DCC70;
        color: white;
        margin-bottom: 10px;
     }

     .exp-two {overflow: hidden;}

     .exp-two hr
     {
         width: 600px;
         float: right;
         margin-top: 10px;
     }

     .exp-two p
     {
         line-height: 1.6;
         color: #888;
     }

     
    /* End My Education */

    /*Start testimonials*/
    .testimonials
    {
        background-color: #F2F2F2;
        text-align: center;
    }

    .testimonials p
    {
        color: #888;
        line-height: 1.6;
        font-style: italic;
    }

    .testimonials h3
    {
        color: #555;
    }
    .testimonials-two
    {
        padding: 50px 50px 80px 50px;
    }
    

    /*End testimonials*/


    /*Start Portfolio*/
        
        .portfolio
        {
            padding-top: 30px;
            padding-bottom: 30px;
            text-align: center;
        }

        .portfolio .our-work
        {
            overflow: hidden;
        }

        .portfolio .our-work > div
        {
            float: left;
            width: 31.333333%;
          
        }

        .portfolio .our-work > div img
        {
            width: 93%;
            margin: 10px;
        } 

        .portfolio h2 
        {
            color: #555;
        }

        .portfolio p
        {
            color: #888;
            ;line-height: 1.6;
            margin-bottom: 70px;
        }
    /*End Portfolio*/


    /*Start Contact Me*/
        .contact-me
        {
            background-color: #252F31;
            overflow: hidden;
        }

        .contact-me h2 {color: #F6F8FA;}

        .contact-me p {color: #515A5C; line-height: 1.6;}

        .contact-me .info,
        .contact-me .form
        {
            width: 50%;
            float: left;
        }

        .contact-me .info h2
        {
            color: #F2F2F2;
        }

        .contact-me .form .real-form
        {
            width: 350px;
            background-color: #555;
            color: #555;
            height: 30px;
        }

        .contact-me .form p
        {
            color: #F2F2F2;
        }

        .contact-me .form .not-form
        {
            width: 350px;
            background-color: #555;
            color: #555;
            height: 300px;
            margin-bottom: 40px;
        }
     /*End Contact Me*/

     /* Start Footer */
        .footer
        {
            background-color: #191E22;
            color:#515A5C ;
            text-align: center;
            padding: 20px;
        }

        .footer .container
        {
            text-transform: uppercase;
            font-weight: bold;
        }

        .footer .container ul li
        {
            display: inline;
            color: #888;
        }
     /* End Footer */


	</style>
	 
	 <body>
		 <!-- start header-->
	<div class="header">
	<div class="slider">
		<div class="container">
			<div class="intro">
				<h2>Web &amp; Graphic Designer</h2>
				<button>Learn More</button>
			</div>
		</div>
	</div>


<div class="navbar">
	<div class="container">
		<h2>Fo<span>cal</span></h2>
<ul>
	<li><a href="">Home</a></li>
	<li><a href="#about-me">About Us</a></li>
	<li><a href="#my-skills">Skills</a></li>
	<li><a href="#resume">Resume</a></li>
	<li><a href="#testimonials">Testimonials</a></li>
	<li><a href="#portfolio">Portfolio</a></li>
	<li><a href="#contact-me">Contact Me</a></li>

</ul>
	</div>
</div>
	
		 </div>
	  
	  <!-- end header-->



	  <!--Start features-->
		<div class="features">
			<div class="container">
				<div class="feat">
					<h3>Values</h3>
					<p>Lorem ipsum dolor sit amet, ea doming untilepicuri iudicabit nam, te usu virute placerat.Purto brutedisplando cu est.</p>
				</div>

				<div class="feat">
					<h3>Goals</h3>
					<p>Lorem ipsum dolor sit amet, ea doming untilepicuri iudicabit nam, te usu virute placerat.Purto brute displando cu est.</p>
				</div>

				<div class="feat">
					<h3>Hobbies</h3>
					<p>Lorem ipsum dolor sit amet, ea doming untilepicuri iudicabit nam, te usu virute placerat.Purto brute displando cu est.</p>
				</div>


			</div>
		</div>
	<!--End features-->


	   <!--Start About Me-->
	   <div class="about-me" id="about-me">
			<div class="container">
				<div class="image">
					<img src="../images/GRA_01171-500x500-c-default.jpg" alt="Test">
				</div>
				<div class="info">
					<h2>About Me</h2>
					<p>Lorem ipsum dolor sit amet, ea doming untilepicuri iudicabit nam, te usu virepiepicuri iudicabit nam, te usu virute placerat.te usu virepiepicuri iudicabit nam, te usu virute placeratLorem ipsum dolor sit amet, ea doming untilepic te usu virute placerat.te ri iudicabit nam, te usu virute placerat</p>
					<div class="hobbies">
						<div class="web-design">
							<div class="icon">
								<img src="../images/globe-earth-geograhy-planet-school-128.png">
							</div>
							<h3>Web Design</h3>
							<p>Lorem ipsum dolor sit amet, ea doming untilepicuri iudicabit nam.</p>
						</div>
	
						<div class="graphic-design">
							<div class="icon">
								<img src="../images/brush-pencil-128.png">
							</div>
							<h3>Graphic Design</h3>
							<p>Lorem ipsum dolor sit amet, ea doming untilepicuri iudicabit nam.</p>
						</div>
	
						<div class="marketing">
							<div class="icon">
								<img src="../images/14_Microsoft_People-128.png">
							</div>
							<h3>Online Marketing</h3>
							<p>Lorem ipsum dolor sit amet, ea doming untilepicuri iudicabit nam.</p>
						</div>
	
						<div class="seo">
							<div class="icon">
								<img src="../images/note-128.png">
							</div>
							<h3>SEO</h3>
							<p>Lorem ipsum dolor sit amet, ea doming untilepicuri iudicabit nam.</p>
						</div>
					</div>
				</div>
				
			</div>
	   </div>
	   <!--End About Me-->
	   
		<!-- Start My Skills-->
			<div class="my-skills" id="my-skills">
				<div class="container">
					<div class="skills">
						<h2>My Skills</h2>
						<p>Lorem ipsum dolor sit amet, ea doming untilepicuri iudicmabit na, te usu virute placerat.Purto brute displando cu est untilepicuri iudicmabit na iudicmabit na, te usu virute placerat.Purto brute displando cu.</p>
						<p>Lorem ipsum dolor sit amet, ea doming untilepicuri iudicmabit na, te usu virute placerat.Purto brute displando cu est .</p>

						<button>Contact Me</button>
					</div>

					<div class="progress">
						<div class="technique">
							<h3>PHOTOSHOP</h3>
							<div>
								<span style="width: 90%;">90% &nbsp;</span>
							</div>
						</div>

						<div class="technique">
							<h3>ILLUSTRATOR</h3>
							<div>
								<span style="width: 80%;">80% &nbsp;</span>
							</div>
						</div>

						<div class="technique">
							<h3>HTML / CSS</h3>
							<div>
								<span style="width: 90%;">90% &nbsp;</span>
							</div>
						</div>

						<div class="technique">
							<h3>PHP / MYSQL</h3>
							<div>
								<span style="width: 70%;">70% &nbsp;</span>
							</div>
						</div>

						
					</div>

				</div>
			</div>
		<!-- End My Skills-->

		<!--Start Resume-->
		<div class="resume" id="resume">
			<div class="container">
			   <div class="resume-two">
				<h2>RESUME</h2>
				<p>Lorem ipsum dolor sit amet, ea doming untilepicuri iudicabit nam, te usu virute placerat.Purto brute displando cu est lepicuri iudicabit nam, te usu virute placerat.Purto brute displando cu est picuri iudicabit nam, te us.</p>
				<button>Download Resume</button>
			   </div>
			</div>
		</div>
		<!--End Resume-->

		<!-- Start My Education-->
		<div class="my-education">
			<div class="container">
				
				<div class="main">
					<h2>My Education</h2>
					<p>Lorem ipsum dolor sit amet, ea doming untilepicuri iudicabit nam, te usu virute placerat.Purto brute displando cu est Lorem ipsum dolor sit amet,e doming untilepicuri iudicabit nam, te usu virute place.</p>
					<p>Lorem ipsum dolor sit amet, ea doming untilepicuri iudicabit nam, te usu virute placerat.Purto brute displando cu est Lor.</p>
				</div>

				<div class="exp">
					<h3>Graphic Design Diploma</h3>
					<p>Reeves College / June 2008 - May 2010</p>
					<button>4.0 GPA</button>
					<hr>
					<p>Lorem ipsum dolor sit amet, ea doming untilepicuri iudicabit nam, te usu virute placerat.Purto brute displando cu est Lorem ipsum dolor sit amet,e doming untilepicuri iudicabit nam.</p>
					<h4>CIT DIPLOMA</h4>
					<p>Lethbridge College / June 2006 - May 2008</p>
					<button>4.0 GPA</button>
					<hr>
					<p>Lorem ipsum dolor sit amet, ea doming untilepicuri iudicabit nam, te usu virute placerat.Purto brute displando cu est Lorem ipsum dolor sit amet,e doming untilepicuri iudicabit nam.</p>
				</div>
<div class="clearfix"></div>
				<hr>

				<div class="main">
					<h2>Work Experience</h2>
					<p>Lorem ipsum dolor sit amet, ea doming untilepicuri iudicabit nam, te usu virute placerat.Purto brute displando cu est Lorem ipsum dolor sit amet,e doming untilepicuri iudicabit nam, te usu virute place.</p>
					<p>Lorem ipsum dolor sit amet, ea doming untilepicuri iudicabit nam, te usu virute placerat.Purto brute displando cu est Lor.</p>
				</div>				

				<div class="exp-two">
					<h4>lead web designer</h4>
					<p>ABC Company, Saskatoon / June 2011 - Present</p>
					<button>3 Years</button>
					<hr>
					<p>Lorem ipsum dolor sit amet, ea doming untilepicuri iudicabit nam, te usu virute placerat.Purto brute displando cu est Lorem ipsum dolor sit amet,e doming untilepicuri iudicabit nam, te usu.</p>
					<h4>junior designer</h4>
					<p>XYZ Company, Lethbridge / June 2008 - May 2009</p>
					<button>1 Year</button>
					<hr>
					<p>Lorem ipsum dolor sit amet, ea doming untilepicuri iudicabit nam, te usu virute placerat.Purto brute displando cu est Lorem ipsum dolor sit amet,e doming untilepicuri iudicabit nam, te usu.</p>
					<h4>Web developer</h4>
					<p>The Company, Lethbridge / June 2007 - May 2008</p>
					<button>1 Year</button>
					<hr>
					<p>Lorem ipsum dolor sit amet, ea doming untilepicuri iudicabit nam, te usu virute placerat.Purto brute displando cu est Lorem ipsum dolor sit amet,e doming untilepicuri iudicabit nam, te usu.</p>


				</div>
			</div>
		</div>
		<!-- End My Education-->

		<!--Start Testmonials-->
			<div class="testimonials" id="testimonials">
				<div class="container">
					<div class="testimonials-two">
						<p>"Lorem ipsum dolor sit amet, ea doming untilepicuri iudicabit nam, te usu virute placerat.Purto brute displando cu est Lorem ipsum dolor sit amet,e doming untilepicuri iudicabit nam Lorem ipsum dolor sit amet, ea doming untilepicuri iudicabit nam, te usu virute placerat.Purto brute displando cu est Lorem ipsum dolor sit amet,e doming untilepicuri iudicabit nam Purto brute displando"</p>
						 <h3>Hassan Mohamed</h3>
						 <input type="radio" class="two">
						 <input type="radio" class="two">
						 <input type="radio" class="two">

					</div>
					
				</div>
			</div>

		<!--End Testimonials-->
			
			<!--Start Portfolio-->
				<div class="portfolio" id="portfolio">
					<div class="container">
						<h2>PORTFOLIO</h2>
						<p>Lorem ipsum dolor sit amet, ea doming untilepicuri iudicabit nam, te usu virute placeratPurto brute displando cu est  ea doming untilepicuri iudicabit nam, te usu virute placeratPurto brute displando cu est brute displando cu est  ea .</p>
							<div class="our-work">
								<div> <img src="../images/dallas_mavericks_2017-pres.png" alt=""> </div>
								<div><img src="../images/images2.png" alt=""></div>
								<div><img src="../images/images3.png" alt=""></div>
								<div><img src="../images/images4.png" alt=""></div>
								<div><img src="../images/images5.png" alt=""></div>
								<div><img src="../images/logo-hivemq.png" alt=""></div>
								<div><img src="../images/images7.png" alt=""></div>
								<div><img src="../images/images8.png" alt=""></div>
								<div><img src="../images/images99.png" alt=""></div>
							</div>
					</div>
				</div>
			<!--End Portfolio-->


			<!--Start Contact Me-->
				<div class="contact-me" id="contact-me">
					<div class="container">
						<div class="info">
							<h2>CONTACT ME</h2>
							<p>Lorem ipsum dolor sit amet, ea doming untilepicuri iudicabit nam, te usu virute placerat.Purto brute displando cu est  te usu virute placerat.Purto br displando cu est  te usu virut.</p>
							<p>122 33rd Street East</p>
							<p>Saskatoon, SK</p>
							<p>S7K 1R9</p>
							<p>Email:&nbsp;&nbsp;&nbsp;&nbsp; info@Focal.com <br> Phone:&nbsp;&nbsp;&nbsp;&nbsp; 1-306-222-2323 </p>
						</div>

						<div class="form">
							<p>Name *</p>
							<div class="real-form">
								Type your name
							</div>
							<p>Email address *</p>
							<div class="real-form">
								Type your name
							</div>
							<p>Message *</p>
							<div class="not-form">
								Type your name
							</div>
						</div>
					</div>
				</div>
			<!--End Contact Me-->

			<!--Start Footer-->
				<div class="footer">
					<div class="container">
						Copyright &copy; 2014 Focal - Built With Passion
						<ul>
							<li><img src="../images/facebook_circle_color-32.png"></li>
							<li><img src="../images/iconfinder_twitter_circle_color_107170.png"></li>
							<li><img src="../images/google-plus-32.png"></li>
							<li><img src="../images/iconfinder_linkedin_circle_color_107178.png"></li>
						</ul>
					</div>
				</div>
			<!--End Footer-->


	 </body>
</html>
