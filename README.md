

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>3SMART TECHNOLOGIES</title>
    <link rel="stylesheet" href="./style.css">
    <link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap" rel="stylesheet">
</head>
  <style>
    *{
    list-style: none;
    padding: 0;
    text-decoration: none;
    box-sizing: border-box;
    font-family: "Poppins", sans-serif;
}

a{
    float: right;
    margin-right: 4%;
    color: rgb(107, 82, 82);
    margin-top: 2%;

}

.marg{
    margin-right: 150px;
}

.pics{
    width: 100%;
}

.pic2{
    width: inherit;
}
   


.contact{
    width: 47%;
    padding: 5%;
}

.forms{
    width:47%;
    padding: 5%;
}
input, textarea{
    width: 100%;
    height: 6%;
    border-radius: 10px;
    outline: none;
}

input{
    margin-bottom: 30px;
    border: 1px solid black;
    border-bottom: 0;
    border-top: 3px solid black;
}

.pic1{
    float: left;
    
}

.but{
    width: 47%;
    height: 10%;
    overflow: auto;
    margin-top: 30px;
   
}

.but2{
    width: 100%;
    height: 100%;
    border-radius: 10px;
    color: rgb(2, 32, 2);
    font-size: 20px;
    background-color: orange;
    
}

.phone{
    margin-left: 150%;
    width: 70%;
    font-size: 20px ;
    color: rgb(107, 82, 82);
    padding: 20px;
    margin-top: -130%;
 
}

b{
    color: black;
}

.row{
    height:150px; 
    
}

::placeholder{
    font-size: 15px;
}

#message{
    height: inherit;
}

a:hover{
    color: red;
}

@media(max-width:650px){
    button{
        font-size: 15px;
    }

   .phone{
        font-size: 13px;
        background-color: black;
        margin-top: 0;
        margin-left: 0;
        width:100%;

   }
    b{
        color:white;
    }
    .contact{
        font-size: 15px;
        width:100%;
        border-bottom: 1px solid black;
        padding: 1%;
    }

  a{
        font-size: 10px;
        margin-right: 2%;
    }

   .pic1{
        width: 15%;
    }

   .marg{
        margin-right: 0;
    }

   .forms{
        width: 100%;
   }
}



  </style>
<body>
    
   <nav>
            <ul>
                <a href="#"> <li class="marg">Contact</li></a>
                <a href="#"> <li>Solar Installment</li></a>
                <a href="#"> <li>About</li> </a>
                <a href="#"> <li>Change Overs</li> </a>
                <img src="./3smart.png" alt="3SMART" class="pic1" >
            </ul>
        </nav>
        

   <div class="pics"><img src="./contact_us.png" alt="contact us" class="pic2"></div>

   <div class="contact">
        <h1 id="con">Contact us</h1>
        <p id="lorem">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolor sint, 
            odit voluptatibus molestiae omnis vitae facere distinctio doloremque 
            veniam necessitatibus id ipsam cumque? Quae, nam eligendi quasi illo 
            deleniti aspernatur!
        </p>
    </div>

   <div class="forms">
        <form action="#">
            <label for="fname">Full name</label>
            <br>
             <input type="text" id="fname">

   <br>
            <label for="mail">Email</label>
            <br>
             <input type="email" id="mail">
             <br>
            <label for="reason">Reasons for writing this</label>
            <br>
             <input type="text" id="reason">
             <br>

   <div class="row">
                <label for="message">Message</label>
                <br>
                <textarea  id="message" cols="30" rows="10" placeholder="Enter your message here"></textarea>
                
   </div>

             
   <div class="but">
               
             

   <button class='but2' onclick="copyContact()">Submit</button>
            </div>
        </form>

   <div class="phone">
            <p><b>Phone: </b> 0000-000-0000</p>
            <p><b>Email: </b> contactus@gmail.com</p>
            <p><b>Office: </b> @banana Island Ilesa Osun state</p>
            <p><b>Opening hours: </b> <br>
            Monday: 8:00am - 7:00pm <br>
            Tuesday: 8:00am - 7:00pm <br>
            Wednessday: 8:00am - 7:00pm <br>
            Thursday: 8:00am - 7:00pm <br>
            Friday: 8:00am - 7:00pm <br>
            Saturday: 8:00am - 7:00pm <br>
        </p>
    
   <p><b>We cannot wait to hear from you!!!</b></p>
        </div>
        
   <script>
            function copyContact(){
                var get = document.getElementById("lorem");
                document.getElementById("message").innerHTML = get.innerHTML;
            }

   </script>
    </div>

        
        


       
       
    

    
</body>
</html>

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/prettygenius220/contactUs/edit/main/README.md) to maintain and preview the content for your website in Markdown files.



Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
