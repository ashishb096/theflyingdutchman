<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="css/responsive.css">
    <title>The Flying Dutchman</title>
</head>

<body>
    <nav class="navbar background h-nav-resp">
        <ul class="nav-list v-class-resp">
            <div class="logo"><img src="img/logo.png" alt="logo"></div>
            <li><a href="#">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#booktable">Book a Table</a></li>
        </ul>
        
        <div class="burger">
            <div class="line"></div>
            <div class="line"></div>
            <div class="line"></div>
        </div>
    </nav>

    <section class="background firstSection">
        <div class="box-main">
            <div class="firstHalf">
                <p class="text-big">The Flying Dutchman</p>
                <p>   A taste of the countryside in the heart of the city</p>
                <br>
                <p class="text-small">Bar Food, Fast Food, North Indian, Chinese, Continental, Italian, Beverages<br>
                    Indirapuram Habitat Centre, Indirapuram, Ghaziabad</p>

            </div>

            <div class="secondHalf">
                <img src="img/entrance.jpg" alt="restraunt img">
            </div>
        </div>
    </section>

    <section class="section" id="about">
        <div class="paras">
        <p class="sectionTag text-big">A TASTE OF THE COUNTRYSIDE IN THE HEART OF THE CITY</p>
        <p class="sectionSubTag text-small">The Flying Dutchman is known for its exciting ship-themed décor. The Flying Dutchman is also host to a beautiful and classy outdoor seating area. This multicuisine restaurant serves delectable Chinese, North Indian and European dishes. We also have some amazing beverages both alcoholic and non-alcoholic as per your preference.  </p>
        </div>
        <div class="thumbnail">
            <img src="img/entrance.jpg" alt="FlyingDutchman" class="imgFluid">
        </div>
    </section>

    <section class="section" id="about">
        <div class="paras">
        <p class="sectionTag text-big">Bar</p>
        <p class="sectionSubTag text-small">A fully-stocked up bar that has expert bartenders who are known for whipping up some great alcoholic and non-alcoholic drinks. </p>
        </div>
        <div class="thumbnail">
            <img src="" alt="laptop image" class="imgFluid">
        </div>
    </section>

    <section class="section section-left" id="about">
        <div class="paras">
        <p class="sectionTag text-big">Live Music</p>
        <p class="sectionSubTag text-small">Enjoy live music here that will simply enhance the charm of your dining experience. </p>
        </div>
        <div class="thumbnail">
            <img src="https://source.unsplash.com/900x900/?coding,apple,html" alt="laptop image" class="imgFluid">
        </div> 
    </section>
    <section class="section" id="services">
        <div class="paras">
        <p class="sectionTag text-big">Restaurant Features</p>
        <pre class="sectionSubTag text-small">    
         Home Delivery        Smoking Area        Air Condition       Nightlife
   
         Take Away       Outdoor Seating     Live Music      Valet Parking
   
         Wheelchair Accessible       Live Sports Screening       Kids Allowed     
                                            
         Bar

        </pre>
        
        <p class="sectionSubTag text-small"> 
            Table booking is highly recommended in order to spare yourself any last-moment hassles.
         </p>
        </div>
        <div class="thumbnail">
            <img src="https://source.unsplash.com/900x900/?javascript,apple, nature, happy" alt="laptop image" class="imgFluid">
        </div>
    </section>
     
    <section class="booktable" id="booktable">
        <h1 class="text-center">Book a Table</h1>
        <div class="form">
            <input class="form-input" type="text" name="name" id="name" placeholder="Enter Your name">
            <input class="form-input" type="text" name="phone" id="phone" placeholder="Enter Your Phone">
            <input class="form-input" type="email" name="email" id="email" placeholder="Enter Your email">
            <input class="form-input" type="date" name="Date" id="date" placeholder="Select Date">
            <input class="form-input" type="time" name="time" id="time" placeholder="Time">
            <input class="form-input" type="number" name="guests" id="guests" min="1" max="20" placeholder="Select Guests">
            <button class="btn btn-sm btn-dark">Submit</button>
            <input  class="form-input" type="reset">
        </div>
    </section>

    <footer class="background">
        <p class="text-footer">
            Copyright &copy; 2027 - www.TheFlyingDutchman.com - All rights reserved
        </p>
    </footer>
    <script src="js/resp.js"></script>

</body>

</html>
