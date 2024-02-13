<!DOCTYPE html>
<html lang="en">
    <head>
        <title>YourChoice</title>
        <meta charset='utf-8'>
        <meta http-equiv='X-UA-Compatible' content='IE=edge'>
        <meta name='viewport' content='width=device-width, initial-scale=1'>
    </head>
    <style>
        *{
    margin:0;
    padding:0;

}
:root{
   --navbar-height: 59px;
}

#navbar{
    display: flex;
    align-items:center;
    position:relative;
}

#navbar ul{
    display: flex;
}
#navbar ul li{
    list-style: none;
    font-size: 1.5rem;
}
#navbar ul li a{
    color: white;
    display: block;
    padding: 3px 22px;
    border-radius: 20px;
    text-decoration: none;
}
#navbar ul li a:hover{
    color:black;
    background-color: white;
}
#navbar::before{
 
    content: "";
    background-color: black;
    position:absolute;
    height: 100%;
    width: 100%;
    z-index: -1;
    opacity: 0.9;
}
/home section/
#home{
    display: flex;
    flex-direction: column;
    height: 400px;
    padding:3px 200px;
    justify-content: center;
    align-items: center;
}
#home::before{
    content: "";
    background-size: cover;
    background: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSAXDhNmV63jgZdYumUEaFjL-CrYtBZ-JsRaA&usqp=CAU');
    position:absolute;
    height: 77%;
    width: 100%;
    z-index: -1;
    opacity: 1;
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: 100% 100%;    
}
#home p{

    display: flex;
    text-align: center;
    font-size: 1.2rem;
    padding: 10px;
    color: white;
}
.h-primary{
    font-size: 3.8rem;
    padding: 12px;
    color: white;
}

.btn
{
   padding: 3px 22px;
   border-radius: 100px;
   background-color: chocolate;
   color: white;
   border: 10rem;
   border-color: black;
}
.btn a
{
    color: white;
    display: block;
    padding: 3px 2px;
    border-radius: 30px;
    text-decoration: none;

}
/services/
#services
{
    display: flex;
    margin: 34px;
}
#services .box-1 {
    border:2px solid brown;
}
#services .box-1 img {
    height: 160px;
    width: 160px;
}
#services_container
{
    display: flex;
    margin: 34px;
}
#services_containter .tag1
{
    align-content: center;
    display: flex;
    color: aliceblue;
}
.picks
{
    background-size: cover;
}

    </style>
    <body>
            <nav id = "navbar">
                <ul>
                    <li class="item"><a href="index1.html">Home</a></li>
                    <li class="item"><a href="Services.html">Menu</a></li>
                    <li class="item"><a href="about_us.html">About us</a></li>
                    <li class="item"><a href="Contact_us.html">Contact us</a></li>
                </ul>
            </nav>
            <section id="home">
                <h1 class="h-primary">FoodSpot</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    <br>  
                Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                <button class="btn"><a href = "Services.html">OrderNow!</a> </button>
                <br>
            </section>
            <br>
            <br>
            <br>
            <p>
                <center><h1>MOST POPULAR</h1></center>
            </p>
            <br>
            <br>
            <br>
            <section class="picks">
                <img onmouseover="bigImg(this)" onmouseout="normalImg(this)" border="0" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT5-f6bGtMTPX6MYo4uhSII7vAfg8aAHHF1Iw&usqp=CAU" alt="Smiley" width="300" height="300">
                <img onmouseover="bigImg(this)" onmouseout="normalImg(this)" border="0" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcToq_AHVpah9h1cgL4cQKyPLzuG9vG8cXBTjw&usqp=CAU" alt="Smiley" width="300" height="300">
                <img onmouseover="bigImg(this)" onmouseout="normalImg(this)" border="0" src="https://www.forbesindia.com/media/images/2021/Dec/img_175063_whyisbiryanigettingbrandedalloverthecountry.jpg" alt="smiley" width="300" height="300">
                <img onmouseover="bigImg(this)" onmouseout="normalImg(this)" border="0" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSCwo4FIZqbfqGtkAOV1ux1DiaR_7QJPjgCNQ&usqp=CAU" alt="Smiley" width="300" height="300">
            </section>
            <script>
                function bigImg(x) {
        x.style.height = "350px";
        x.style.width = "350px";
        }

        function normalImg(x) {
         x.style.height = "300px";
         x.style.width = "300px";
        }       
         </script>
           <footer>
            
           </footer>
            


    </body>
</html>
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>About Us</title>
        <meta charset='utf-8'>
        <meta http-equiv='X-UA-Compatible' content='IE=edge'>
        <meta name='viewport' content='width=device-width, initial-scale=1'>
    </head>
    <style>
       *{
    margin:0;
    padding:0;

}
#slogan
{
    display: flex;
    flex-direction: column;
    padding: 30px;
    font-style: italic;
    color: black;
    font-size: 2.8rem;
}
#slogan::before{
    content: "";
    background-color: coral;
    position:absolute;
    height: 40%;
    width: 100%;
    z-index: -1;
    opacity: 0.9;

}

#slogan1
{
    display: flex;
    flex-direction: column;
    text-align: center;
    padding: 30px;
    font-style: italic;
    color: black;
    font-size: 1.8rem;
}
#slogan1::before{
    content: "";
    background-color: rgb(255, 214, 80);
    position:absolute;
    height: 40%;
    width: 100%;
    z-index: -1;
    opacity: 0.9;

}
#slogan3
{
    display: flex;
    flex-direction: column;
    padding: 30px;
    font-style:italic;
    color: black;
    font-size: 1.2rem;
}

    </style>
    <body>
        <sec id="slogan">
        <p>
            <img src="data:image/png;base64,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" height="50px" width="50px" >
            Our mission is to elevate the quality of life for the urban consumer with unparalleled convenience.
            <br>
             Convenience is what makes us tick. It's what makes us get out of bed and say, "Let's do this."
             <br>
             <br>
             <br>

             <img src="https://careers.swiggy.com/assets/img/Swiggy-Journey.jpg" alt="journey" height="500px" width="1200px">
        </p>
        <br>
       <sec id="slogan1">
        <h1>
            What’s In Store For The Future?
        </h1>
        <p>
           Food Spot has grand plans to be India’s most loved hyperlocal player.
            <br>
             It aims to be the most accessible platform on the network - reimagining the meaning of convenience in the country through a variety of service offerings.
             <br>
        </p>
        </sec>
        <section id="slogan3">
            <h1>Get In Touch</h1>
            <h2>Head Office</h2>
            <p>
                Bundl Technologies Pvt. Ltd.
                <br>
                No. 55 Sy No 8 to 14 I & J Block - Ground Floor, Embassy Tech Village |
                <br>
                 Outer Ring Road, Devarbisanahalli, Varthur Bengaluru - 560130
                 <br>
                 <br>
                 <br>
                 <button class="btn"><a href = "home.html">Next</a> </button>
                 <br>
            </p>
        </section>
        

    </body>
    <!DOCTYPE html>
<html>
<head>
<style>
.all-browsers {
  margin: 0;
  padding: 5px;
  background-color: lightgray;
}

.all-browsers > h1, .browser {
  margin: 10px;
  padding: 5px;
}

.browser {
  background: white;
}

.browser > h2, p {
  margin: 4px;
  font-size: 90%;
}

footer {
  text-align: center;
  padding: 3px;
  background-color: rgb(122, 207, 233);
  color: white;
}
</style>
</head>
<body>

<h1>Frequently Asked Questions..</h1>

<article class="all-browsers">
  <h1>Most Popular Questions</h1>
  <article class="browser">
    <h2>What are the delivery timings?</h2>
    <p>The Delivery timings are 24/7</p>
  </article>
  <article class="browser">
    <h2>How can i track my order?</h2>
    <p>You Will Recive a message from our team  from there you can track your orders</p>
  </article>
  <article class="browser">
    <h2>How much time it takes to deliver?</h2>
    <p>Usually its 45 to 110 min..</p>
  </article>
  <article class="browser">
    <h2>Can i order from any location?</h2>
    <p>Yes you can order From any location in hyderabad.</p>
  </article>
  <article class="browser">
    <h2>Does veg and non veg items are cooked seperately?</h2>
    <p>Yes they are cooked seperately You can trust us!!!</p>
  </article>
  <article class="browser">
    <h2>Do you have any discounts?</h2>
    <p>Yes you get 30% discount on your first order and 15% everytime when you order items above 1000/-.</p>
  </article>
  <article class="browser">
    <h2>How can i cancel my order?</h2>
    <p> Please contact helpline Number as soon as possible, we can let the kitchen know before it starts preparing your order. Once the order goes in the process, it can not be changed. With regard to any refund of a payment you have made online, please contact Food spot delivery.</p>
  </article>
  
  <article class="browser">
    <h2>Do you accept bulk orders?</h2>
    <p> Yes,we do but with 24hrs of prior information.</p>
  </article>
  <article class="browser">
  <h2>How can i contact u for any enquires?</h2>
    <p> U can contact us through mail:sirixx7@gmail.com and whatsapp us through the number +919440345390.</p>

  </article>
  </article>

<footer>
  <p>Author: Food spot<br>
  <a href="Foodspot@gmail.com">Foodspot@gmail.com</a></p>
</footer>

<br>
<br>
<button class="btn"><a href = "home.html">home</a> </button>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>YourChoice</title>
        <meta charset='utf-8'>
        <meta http-equiv='X-UA-Compatible' content='IE=edge'>
        <title>Food</title>
        <meta name='viewport' content='width=device-width, initial-scale=1'>
        <link rel='stylesheet' type='text/css' media='screen' href='style3.css'>
    </head>
    <body>
     
      
        <centre>
            <h2><center>Payment Page</center></h2>
            <p><b>only or credit/debit card accepted for payment</b></p>
            <br>
            <p style="color: red;">*please fill all details before confirm order</p>
            <form>
            <p>Student name : </p>
            <input type="placeholer" name = "Student name"/>
            <p>Age : </p>
            <input type="placeholer" name = "Age"/>
            <p>Name of card_holder : </p>
            <input type="placeholer" name = "NAME OF CARD_HOLDER "/>
            <p>Credit Card/Debit Card Number : </p>
            <input type="placeholer" name = "Enter debit/credit card no"/>
            <p>CVV : </p>
            <input type="placeholer" name = "CVV"/>
            <p>Expiry date :</p>
            <input type = "date" name = "date"/>
            <br>
            <br>
            </form>
            <button class="btn"><a href = "submit.html">confirm order</a></button>
        </centre>
        </body>
        <!DOCTYPE html>
<html lang="en">
    <head>
        <title>submit</title>
        <meta charset='utf-8'>
        <meta http-equiv='X-UA-Compatible' content='IE=edge'>
        <title>Food</title>
        <meta name='viewport' content='width=device-width, initial-scale=1'>
    </head>
    <style>
        *{
    margin: 0px;
    padding: 0px;
}
#final p{
    align-items: center;
    justify-content: center;
    
}
    </style>
    <body>
        <section class="final">
        <p>
            <h2>ORDER SUCCESSFUL!!!</h2>
            <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAARMAAAC3CAMAAAAGjUrGAAACIlBMVEXu7u69CQilm5z////x8fGglZbi4ODsAAIDFj6imJkAAADvAADPAwLu9/foREXkAwXLCAjECAjup6bnYWHYBAXL0dG6CQnx/v7I2NjpUVPnAAAiXnrRAAC7AAAAADYAADPmOjrssrEAADwAACwAADDmw8LsbW6VlZUAACnp2doAADnaAADg6OnqkJFcAAAAEjzS5eQAABsAAEHAGBgAACVYaWmHoaBzj4/ru7vx48YcUXAAABMUJ0yKoqLSf37coKCP0M+oAACbAADrhob58O8pMTHoHx//tQAASGG109MARWhKWlphc3JleYScsLBZYHMbAACIpK5xiJgwOVV9maVBQmfNyMjJbW7GXVvQOzjER0mmNSnccFfGUT7QaGLBOjhvUkPTl3f/u5O1e13/+Oy9ISGcZkvypXt3aGHtuJTt0tLgIyPgw6i/ybr/sYbq3tPfkIS+6+o4GxuKZE3DZU7kqoSgwLZ0vruRZ03Ms6XWj2ieS0zLpYiFMyqjcFWyjHR8TzGgg4ImHiC2OhpNPjOtThPFeUjDd1y5tKjprZrCkJLEpaY8AAD108MqLDMAGyJ8XBDWWUNwMS+TcF/z5J5TAACYdSBERkbz2mC5b3B4KjyZKDBvQVNVRVtUTTGCYGDMkQAyb4duAACtTk2Dg5NGID08VWhimptOUG+xssBhHDRtan8tXGkrAACMVmM4LT9vv76UAB95ACWGh5yawMMyM14YucaXAAAYq0lEQVR4nO2dj0Mbx5XHBZpoCav1SiDJeNFKCBBY7BJkBJIOAzKWwrEGgQGbH07OpHA0sUjtutfUubrX1Gnv2suPptdrL5e4uR4OAVO7bVLL/9+9N7v6OSshQtqr0/26EdYwu9r57Htv3ptZ1TZiqVo2S9WymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLCymLB6BpgQ4eQ61jD/+pmQ8KmTK3mccf71MxHa+ZPrjHCMT3wmmDjd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" alt="delivery" height="400px" width="600px">
            <br>
            Delivery person: abc
            <br>
            contact no:7989790909
            <br>
            <h2>YOUR ORDER WILL BE DELIVERED IN 30 MIN</h2>
            <h1>THANK YOU!!!</h1>
        </p>
    </section>
    </body>\
    <!DOCTYPE html>
<html lang="en">
    <head>
        <title>YourChoice</title>
        <meta charset='utf-8'>
        <meta http-equiv='X-UA-Compatible' content='IE=edge'>
        <meta name='viewport' content='width=device-width, initial-scale=1'>
    </head>
    <style>
        *{
    margin:0;
    padding:0;

}
:root{
   --navbar-height: 59px;
}

#navbar{
    display: flex;
    align-items:center;
    position:relative;
}

#navbar ul{
    display: flex;
}
#navbar ul li{
    list-style: none;
    font-size: 1.5rem;
}
#navbar ul li a{
    color: white;
    display: block;
    padding: 3px 22px;
    border-radius: 20px;
    text-decoration: none;
}
#navbar ul li a:hover{
    color:black;
    background-color: white;
}
#navbar::before{
 
    content: "";
    background-color: black;
    position:absolute;
    height: 100%;
    width: 100%;
    z-index: -1;
    opacity: 0.9;
}
/home section/
#home{
    display: flex;
    flex-direction: column;
    height: 400px;
    padding:3px 200px;
    justify-content: center;
    align-items: center;
}
#home::before{
    content: "";
    background-size: cover;
    background: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSAXDhNmV63jgZdYumUEaFjL-CrYtBZ-JsRaA&usqp=CAU');
    position:absolute;
    height: 77%;
    width: 100%;
    z-index: -1;
    opacity: 1;
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: 100% 100%;    
}
#home p{

    display: flex;
    text-align: center;
    font-size: 1.2rem;
    padding: 10px;
    color: white;
}
.h-primary{
    font-size: 3.8rem;
    padding: 12px;
    color: white;
}

.btn
{
   padding: 3px 22px;
   border-radius: 100px;
   background-color: chocolate;
   color: white;
   border: 10rem;
   border-color: black;
}
.btn a
{
    color: white;
    display: block;
    padding: 3px 2px;
    border-radius: 30px;
    text-decoration: none;

}
/services/
#services
{
    display: flex;
    margin: 34px;
}
#services .box-1 {
    border:2px solid brown;
}
#services .box-1 img {
    height: 160px;
    width: 160px;
}
#services_container
{
    display: flex;
    margin: 34px;
}
#services_containter .tag1
{
    align-content: center;
    display: flex;
    color: aliceblue;
}
.picks
{
    background-size: cover;
}

    </style>
    <body>
            <nav id = "navbar">
                <ul>
                    <li class="item"><a href="index1.html">Home</a></li>
                    <li class="item"><a href="Services.html">Menu</a></li>
                    <li class="item"><a href="about_us.html">About us</a></li>
                    <li class="item"><a href="Contact_us.html">Contact us</a></li>
                </ul>
            </nav>
            <section id="home">
                <h1 class="h-primary">FoodSpot</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    <br>  
                Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                <button class="btn"><a href = "services.html">OrderNow!</a> </button>
                <br>
            </section>
            <br>
            <br>
            <br>
            <p>
                <center><h1>MOST POPULAR</h1></center>
            </p>
            <br>
            <br>
            <br>
            <section class="picks">
                <img onmouseover="bigImg(this)" onmouseout="normalImg(this)" border="0" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT5-f6bGtMTPX6MYo4uhSII7vAfg8aAHHF1Iw&usqp=CAU" alt="Smiley" width="300" height="300">
                <img onmouseover="bigImg(this)" onmouseout="normalImg(this)" border="0" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcToq_AHVpah9h1cgL4cQKyPLzuG9vG8cXBTjw&usqp=CAU" alt="Smiley" width="300" height="300">
                <img onmouseover="bigImg(this)" onmouseout="normalImg(this)" border="0" src="https://www.forbesindia.com/media/images/2021/Dec/img_175063_whyisbiryanigettingbrandedalloverthecountry.jpg" alt="smiley" width="300" height="300">
                <img onmouseover="bigImg(this)" onmouseout="normalImg(this)" border="0" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSCwo4FIZqbfqGtkAOV1ux1DiaR_7QJPjgCNQ&usqp=CAU" alt="Smiley" width="300" height="300">
            </section>
            <script>
                function bigImg(x) {
        x.style.height = "350px";
        x.style.width = "350px";
        }

        function normalImg(x) {
         x.style.height = "300px";
         x.style.width = "300px";
        }       
         </script>
           <footer>
            
           </footer>
            


    </body>
</html>
