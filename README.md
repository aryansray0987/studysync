<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Study sync</title>
    <link rel="stylesheet" href="index.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@200;300;400;500&family=Poppins:wght@400;700&family=Roboto:wght@400;700&display=swap" rel="stylesheet">
<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@200;300;400;500&family=Poppins:wght@400;700&family=Roboto:wght@400;700&display=swap');
 


*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Inter, sans-serif;
  
}
.header{
    width: 100%;
    height: 5rem;
 
   
}
.head{
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    align-items: center;
   
    
    
}
.icon i{
font-size: 3rem;
margin-top: 1rem;
color: #6366f1;
}
.icon i:hover{
    color: grey;
}
.icon a{
    text-decoration: none;
    color: black;
    margin-left: 0.2rem;
}
.icon span{
    font-size: 2rem;
    font-weight: 700;
    font-family: Arial, Helvetica, sans-serif
}
.option a{
    margin: 1rem;
    text-decoration: none;
    font-size: 1.25rem;
    color: rgb(78, 78, 78);
}
.option{
    margin-right:2rem;
    margin-top: 1rem;
}
.option a:hover{
    color: #2563eb;
}
.button button{
    width: 7.3rem;
    height: 2.35rem;
    color: white;
    background-color: #6366f1;;
    border-radius: 4px;
    border: 3px solid transparent;
    font-weight: 650;
    font-size: .95rem;

}
.button button:hover{
    border: 1px solid black;
    border-radius: 4px;
    background-color: #5254f8;
}
.main1{
    display: flex;
    justify-content: space-between;
    height: 500px;
    width: 100%px;
   
    margin-top: 4rem;
}
.img1{
    height: 500px;
    width: 700px;
    
    background-image: url("photo.jpg");
    background-size: cover;
   
}

.script>p{
    margin-bottom: 1.7rem;
    color: #6366f1;;
    font-weight: 650;
}
.script h1{
    font-size: 3rem;
    margin-bottom: 2.25rem;
}
.script{
    width: 500px;
    margin-left: 9.25rem;
    
}
.para1 p{
    color: rgb(79, 77, 77);
    margin-bottom: 2rem;
    line-height: 1.6rem;
   letter-spacing: 1px;
}
.script button{
    width: 7.3rem;
    height: 2.35rem;
    color: white;
    background-color: #6366f1;;
    border-radius: 4px;
    border: 3px solid transparent;
    font-weight: 650;
    font-size: .95rem;
}
#button{
    background-color: rgb(58, 56, 56);

}
.script button:hover{
    border: 3px solid black;
}
.trust{
    width: 100%;
    height: 12rem;
   
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
.box1{
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 5rem;
    width: 30rem;
   
    background-color: rgb(245, 245, 245);
}
.trust h1{
    font-size: 2.4rem;
    margin-bottom: 2rem;
}
.main2{
    width: 100%;
    height: 900px;
  background-color: whitesmoke;
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 4rem;
}
.advantage{
    text-align: center;
    margin-bottom: 1.5rem;
    margin-top: 1rem;
}
.advantage h1{
    margin-bottom: 1rem;
    font-size: 2.3rem;
}
.advantage p{
    color: rgb(84, 82, 82);
    
}
.container{
    width: 780px;
    height: 270px;
 
display: flex;

}
.section1{
width: 370px;
height: 210px;
border-radius: 3px;
margin-right: 1.5rem;
background-color: rgb(22, 173, 233);
display: flex;
flex-direction: column;
align-items: center;

}
.section1 h3{
    font-weight: 700;
    color: white;
    margin-bottom: .4rem;
    margin-top: .6rem;
}
.section1 p{
    color: white;
    opacity: 0.86;
}
.section1 i{
    font-size: 2rem;
    margin-top: .6rem;
}
.section2{
    width: 370px;
    height: 210px;
border-radius: 3px;
display: flex;
flex-direction: column;
align-items: center;

background-color: rgb(239, 70, 98);
}
.section2 h3{
    font-weight: 700;
    color: white;
    margin-bottom: .4rem;
    margin-top: .6rem;
}
.section2 p{
    color: white;
    opacity: 0.86;
}
.section2 i{
    font-size: 2rem;
    margin-top: .6rem;
}
.section3{
    display: flex;
flex-direction: column;
align-items: center;
    width: 370px;
    height: 210px;
border-radius: 3px;
margin-right: 1.5rem;
background-color: rgb(232, 153, 25);
}
.section3 h3{
    font-weight: 700;
    color: white;
    margin-bottom: .4rem;
    margin-top: .6rem;
}
.section3 p{
    color: white;
    opacity: 0.86;
}
.section3 i{
    font-size: 2rem;
    margin-top: .6rem;
}
.section4{
    width: 370px;
    height: 210px;
border-radius: 3px;
display: flex;
flex-direction: column;
align-items: center;
background-color: rgb(52, 199, 150);
}
.section4 h3{
    font-weight: 700;
    color: white;
    margin-bottom: .4rem;
    margin-top: .6rem;
}
.section4 p{
    color: white;
    opacity: 0.86;
}
.section4 i{
    font-size: 2rem;
    margin-top: .6rem;
}
.section5{
    width: 370px;
    height: 210px;
border-radius: 3px;
margin-right: 1.5rem;
background-color: green;
display: flex;
flex-direction: column;
align-items: center;
}
.section5 h3{
    font-weight: 700;
    color: white;
    margin-bottom: .4rem;
    margin-top: .6rem;
}
.section5 p{
    color: white;
    opacity: 0.86;
}
.section5 i{
    font-size: 2rem;
    margin-top: .6rem;
}
.section6{
    width: 370px;
    height: 210px;
border-radius: 3px;
display: flex;
flex-direction: column;
align-items: center;
background-color: #6366f1;;
}
.section6 h3{
    font-weight: 700;
    color: white;
    margin-bottom: .4rem;
    margin-top: .6rem;
}
.section6 p{
    color: white;
    opacity: 0.86;
}
.section6 i{
    font-size: 2rem;
    margin-top: .6rem;
}
.main3{
    background-color: white;
    width: 100%;
    display: flex;
   
    flex-direction: column;
    align-items: center;
    height: 1200px;
    
}
.main3 h1{
    font-size: 2.2rem;
    margin: 2rem;
}
.container1{
    width: 1250px;
    height: 250px;
   
    display: flex;
    justify-content: space-between;
    align-items: center;

}
.review1{
    height: 250px;
    width: 400px;
    border: 2px solid rgb(181, 181, 181);
    border-radius: 3px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-around;
    text-align: center;
    font-weight: 500;
    background-color: whitesmoke;
    
}
.review2{
    height: 250px;
    width: 400px;
    border: 2px solid rgb(181, 181, 181);
    border-radius: 3px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-around;
    text-align: center;
    font-weight: 500;
    background-color: whitesmoke;
  
}
.review3{
    height: 250px;
    width: 400px;
    border: 2px solid rgb(181, 181, 181);
    border-radius: 3px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-around;
    text-align: center;
    font-weight: 500;
    background-color: whitesmoke;
   
   
}
.photo1{
    width: 5rem;
    height: 5rem;
   
    background-image: url("photo1.jpg");
   background-size: cover;
    border-radius: 100%;
}
#purple{
   color: #6366f1;; 
   font-weight: 600;
}
.photo2{
    width: 5rem;
    height: 5rem;
   
    background-image: url("photo2.jpg");
   background-size: cover;
    border-radius: 100%;
}
.photo3{
    width: 5rem;
    height: 5rem;
   
    background-image: url("photo3.jpg");
   background-size: cover;
    border-radius: 100%;
}
.updates{
    width: 1250px;
    height: 320px;
   background-color: whitesmoke;
    display: flex;
    margin-top: 3.5rem;
    border: 1px solid grey;
}
.cartoon{
    width: 625px;
    height: 320px;
    background-image: url("cartoon1.avif");
    background-size: cover;
   
}
.email{
    width: 625px;
    height: 320px;
   
   padding: 1.7rem;  
   text-align: center;
   
}
.email h1{
    font-size: 2.5rem;
    color: #6366f1;;
    margin-top: .4rem;
}
#sign{
    font-size: 0.6rem;
    opacity: .8;
    font-size: 1.2rem;
    margin-bottom: 1rem;
}
input{
    width: 11rem;
    height: 2rem;
    border: 1px solid grey;
    border-radius: 3px;
}
.email button{
    width: 5rem;
    height: 2rem;
    color: white;
    background-color: #6366f1;;
    border: 2px solid rgb(92, 90, 90);
    border-radius: 3px;
}

.footer{
    display: flex;
    width: 1250px;
    height: 300px;
 
    margin-top: 5rem;

}
.footer1{
    padding: .6rem;
    height: 300px;
    width: 300px;
   
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-evenly;
}
#logo2{
    font-size: 2rem;
    color: #6366f1;;
}
.footer1 i{
    font-size: 1.25rem;
}
.footer1 h2{
    margin-bottom: 2.5rem;
}
.section7 h3{
    margin: 1rem;
    margin-bottom: 1.4rem;
    


}

.section7 a{
    text-decoration: none;
    color: rgb(109, 108, 108);
 
   
    

}
.section7 p{
    margin-bottom: 1rem;
    margin-left: 1rem;
}
.section7{
    margin-left: 8rem;
}
.footer2{
    display: flex;
}
#condition{
    margin: 1rem;
}
</style>

</head>
<body>
    <div class="header">
        <div class="head">
            <div class="icon">
                <i class="fa-solid fa-building-columns"></i>
                <span><a href="#">Study sync</a></span>
            </div>
            <div class="option">
                <a href="#">Home</a><a href="#">Features</a><a href="#">Pricing</a><a href="#">Blog</a><a href="#">About</a>
            </div>
            <div class="button">
                <button>Contact Us</button>
            </div>
        </div>
    </div>
    <div class="main1">
        <div class="script">
            <p>Very pround to introduce</p>
            <h1>Seamless learning for brighter future</h1>
           <div class="para1">
            <p>Our innovative program offers  an effortless and seamless appraoch to learning.Empowering students of all the agesto achieve brighter future.Join us on a transformative journey to simplify education and unlock your full potential.</p>
           </div>
            <button>Start now</button>
            <button id="button">Take tour</button>
        </div>
        <div class="img1">
           
        </div>
    </div>
    <div class="trust">
        <h1>Trusted by the best</h1>
        <div class="box1">
            <div class="google">
                <i class="fa-brands fa-google"></i>
                <span>Google</span>
            </div>
            <div class="microsoft"><i class="fa-brands fa-microsoft"></i><span>Microsoft</span></div>
            <div class="linkedin"><i class="fa-brands fa-linkedin"></i><span>LinkedIn</span></div>
            <div class="apple"><i class="fa-brands fa-apple"></i><span>Apple</span></div>
        </div>

    </div>
   <div class="main2">
    <div class="advantage">
        <h1>Our competitive advantage</h1>
        <p>This is a section of some filler text,also known as placeholder text.It shares some characteristics </p>
        <p>of real written text but is random or otherwise generated</p>
    </div>
    <div class="container">
        <div class="section1">
            <i class="fa-solid fa-lightbulb"></i>
            <h3>Personalised Learning</h3>
            <p>Offer taitored learning experience through</p>
            <p>AI and machine learning to cater to</p>
            <p>individual student needs.</p>
        </div>
        <div class="section2">
            <i class="fa-solid fa-less-than"></i>
            <h3>Affordability</h3>
            <p>Offer taitored learning experience through</p>
            <p>AI and machine learning to cater to</p>
            <p>individual student needs.</p>
        </div>
    </div>
    
    <div class="container">
        <div class="section3">
            <i class="fa-solid fa-industry"></i>
            <h3>Industry Partnership</h3>
            <p>Offer taitored learning experience through</p>
            <p>AI and machine learning to cater to</p>
            <p>individual student needs.</p>
        </div>
        <div class="section4">
            <i class="fa-solid fa-computer"></i>
            <h3>Innovative Technology</h3>
            <p>Offer taitored learning experience through</p>
            <p>AI and machine learning to cater to</p>
            <p>individual student needs.</p>
        </div>
    </div>
    <div class="container">
        <div class="section5">
            <i class="fa-solid fa-phone"></i>
            <h3>Responsive Support</h3>
            <p>Offer taitored learning experience through</p>
            <p>AI and machine learning to cater to</p>
            <p>individual student needs.</p>
        </div>
        <div class="section6">
            <i class="fa-solid fa-chart-line"></i>
            <h3>Analytics and Insights</h3>
            <p>Offer taitored learning experience through</p>
            <p>AI and machine learning to cater to</p>
            <p>individual student needs.</p>
        </div>
    </div>
   </div>
   <div class="main3">
    <h1>What Others Say About Us</h1>
    <div class="container1">
        <div class="review1">
            <p>"Study Sync revolutionised my classroom!Engaging</p>
            <p>Content and teacher resources make learning</p>
            <p>
                enjoyable.Highly recommended for educators."
            </p>
            <div class="photo1"></div>
            <p id="purple">Aryan Gupta</p>
            <p>Founder And CEO of Code Shuttle</p>
        </div>
        <div class="review2">
            <p>"Study Sync revolutionised my classroom!Engaging</p>
            <p>Content and teacher resources make learning</p>
            <p>
                enjoyable.Highly recommended for educators."
            </p>
            <div class="photo2"></div>
            <p id="purple">Aryan Gupta II</p>
            <p>Software Engineer At Google</p>
            

        </div>
        <div class="review3">
            <p>"Study Sync revolutionised my classroom!Engaging</p>
            <p>Content and teacher resources make learning</p>
            <p>
                enjoyable.Highly recommended for educators."
            </p>
            <div class="photo3"></div>
            <p id="purple">Abhisekh Singh</p>
            <p>IAS Officer</p>
        </div>
    </div>
    <div class="updates">
        <div class="cartoon">

        </div>
        <div class="email">
            <h1>Get the latest updates</h1>
            <p id="sign">Sign up for our newsletter</p>
            <input type="text" placeholder="Email">
            <button>Send</button>
            <p id="condition">By signing up to our newsletter you agree to our <a href="#">Terms of Services </a>and <a href="#">Privacy Policy</a></p>
        </div>
      </div>
      <div class="footer">
        <div class="footer1">
            <i  id="logo2"  class="fa-solid fa-building-columns"></i>
           <h2>Study Sync</h2>
            <p>Seamless Learning for Brighter Future</p>
            <div class="icon2">
                <i class="fa-brands fa-instagram"></i>
                <i class="fa-brands fa-twitter"></i>
                <i class="fa-brands fa-linkedin"></i>
                <i class="fa-brands fa-github"></i>
            </div>
        </div>
        <div class="footer2">
            <div class="section7">
                <h3>Products</h3>
              <p><a href="">Overview</a></p>
              <p><a href="">Solution</a></p>
              <p><a href="">Pricing</a></p>
              <p><a href="">Customers</a></p>
            </div>
            <div class="section7">
                <h3>Company</h3>
                <p><a href="">Overview</a></p>
                <p><a href="">Solution</a></p>
                <p><a href="">Pricing</a></p>
                <p><a href="">Customers</a></p>
            </div>
    <div class="section7">
        <h3>Support</h3>
        <p><a href="">Overview</a></p>
        <p><a href="">Solution</a></p>
        <p><a href="">Pricing</a></p>
        <p><a href="">Customers</a></p>
    </div>
    <div class="section7">
        <h3>Legal</h3>
        <p><a href="">Overview</a></p>
        <p><a href="">Solution</a></p>
        <p><a href="">Pricing</a></p>
        <p><a href="">Customers</a></p>
    </div>
    
    
        </div>
       </div>
   </div>
  
  
</body>
</html>
