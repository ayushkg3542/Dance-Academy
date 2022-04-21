# Dance-Academy
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
    <title>Dance Academy</title>
    <style>
        .affix {
            top: 0;
            width: 100%;
            z-index: 9999 !important;
        }

        .affic+.container {
            padding-top: 70px;
        }
    </style>
</head>

<body data-spy="scroll" data-target=".navbar" data-offset="50">
    <div class="container-fluid" style="padding-left: 0px; padding-right: 0px;">
        <nav class="logo" style="background-color:black; height: 58px;">
            <img src="fb.webp" style="height: 30px; margin-left: 14px;" alt=""><span class="badge"
                style="position: absolute;">1M+</span>
            <img src="insta.webp" style="height: 30px; margin: 10px; margin-left: 42px;" alt=""><span class="badge"
                style="position: absolute;">2.5M</span>
            <img src="youtube.webp" style="height: 30px; margin: 10px; margin-left: 42px;" alt="">
            <img src="bird.webp" style="height: 30px; margin: 10px;" alt="">
            <div class="glyphicon glyphicon-earphone" style="float: right; margin: 19px; color: red;">
                <button>9873432938</button>
                <button>6574392372</button>
            </div>
        </nav>
        <div class="header" style="background-color: #f7ba00;">
            <img src="logo2.png" height="100px" width="450px">
            <div class="btn" style="padding-left: 800px;">
                <button class="btn btn-lg btn-danger" data-toggle="modal" data-target="#firstmodal"
                    style="margin: 15px;">Login</button>
                <div class="modal fade" id="firstmodal">
                    <div class="modal-dialog modal-dialog-centered modal-dialog-scrollable">
                        <div class="modal-content">
                            <div class="modal-header">
                                <h3 class="modal-title">Login into your account</h3>
                                <button class="close" type="button" data-dismiss="modal" aria-label="Close">
                                    <span>&times;</span>
                                </button>
                            </div>
                            <div class="modal-body">
                                <div class="form">
                                    <label for="typeEmail" class="form-label"><b>Email address</b></label>
                                    <input type="email" id="typeEmail" placeholder="Enter yout email"
                                        class="form-control" style="width: 300px; border-color: grey;">
                                </div>
                                <div class="form">
                                    <label for="typePassword" class="form-label"><b>Password</b></label>
                                    <input type="password" id="typePassword" placeholder="Enter yout password"
                                        class="form-control" style="width: 300px; border-color: grey;">
                                </div>
                                <div class="modal-footer">
                                    <button class="btn bg-light">Submit</button>
                                    <button class="btn bg-danger">Close</button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <button class="btn btn-lg btn-primary" style="margin: 15px;">Sign Up</button>
            </div>
        </div>
    </div>
    <nav class="navbar navbar-inverse" style="margin-bottom: 0px;" data-spy="affix" data-offset-top="200">
        <div class="container">
            <div class="navbar-header">
                <button class="navbar-toggle" data-toggle="collapse" data-target="#mynavbar">
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
            </div>
            <div class="collapse navbar-collapse" id="mynavbar">
                <ul class="nav navbar-nav">
                    <li><a href="#home">Home</a></li>
                    <li><a href="#aboutus">About Us</a></li>
                    <li><a href="#" class="dropdown-toggle" data-toggle="dropdown">Events <span
                                class="caret"></span></a>
                        <ul class="dropdown-menu">
                            <li><a href="#previous">Previous Events</a></li>
                            <li><a href="#upcoming">Upcoming Events</a></li>
                            <li><a href="#virtual">Virtual Events</a></li>
                        </ul>
                    </li>
                    <li><a href="#category">Categories</a></li>
                    <li><a href="#contactus">Contact Us</a></li>
                </ul>
                <form class="navbar-form navbar-left" style="padding-left: 229px;">
                    <div class="form-group">
                        <input type="text" class="form-control" placeholder="Search">
                    </div>
                    <button class="btn btn-default" type="submit">Submit</button>
                </form>
            </div>
        </div>
    </nav>
    <div class="container-fluid" id="home" style="padding-left: 0px; padding-right: 0px;">
        <div id="myCarousel" class="carousel slide" data-ride="carousel">
            <ol class="carousel-indicators">
                <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
                <li data-target="#myCarousel" data-slide-to="1"></li>
                <li data-target="#myCarousel" data-slide-to="2"></li>
            </ol>
            <div class="carousel-inner">
                <div class="item active">
                    <img src="dance1.avif" alt="" style="width:100%; height: 500px; opacity: .6;">
                    <div class="carousel-caption" style="padding-bottom: 170px;">
                        <h1
                            style="font-family: Georgia, 'Times New Roman', Times, serif; color: black; font-size: 55px;">
                            Dance with Your Favourite Dancers</h1>
                        <p
                            style="color: black; font-size: 30px; font-family: Georgia, 'Times New Roman', Times, serif;">
                            Learn to dance online form the world's best.</p>
                        <button class="btn-lg btn-danger" style="border-radius: 5px;">Get Started</button>
                    </div>
                </div>
                <div class="item">
                    <img src="dance2.avif" alt="" style="width:100%; height: 500px; opacity: .6;">
                    <div class="carousel-caption" style="padding-bottom: 170px;">
                        <h1
                            style="font-family: Georgia, 'Times New Roman', Times, serif; color: black; font-size: 60px;">
                            Experience the Top Dance, Music and
                            Speaking</h1>
                        <h1 style="font-family: gerif; color: black; font-size: 40px;">Classes at "D"2"X" Academy</h1>
                    </div>
                </div>
                <div class="item">
                    <img src="dance3.webp" alt="" style="width:100%; height: 500px; opacity: .6;">
                    <div class="carousel-caption" style="padding-bottom: 170px">
                        <h1
                            style="font-size: 60px; color: #56faea; font-family: Georgia, 'Times New Roman', Times, serif;">
                            Dance till you Drip</h1>
                        <h3
                            style="font-family: Georgia, 'Times New Roman', Times, serif; color: #adf5a7; font-size: 30px;">
                            Experience full body workout featuring the hottest songs, hype instructor,and dance moves
                            you'd actually do</h3>
                        <button class="btn" style="border-radius: 10px; background-color: crimson;">"Don't hold back"
                            Get Started</button>
                    </div>
                </div>
                <a class="left carousel-control" href="#myCarousel" data-slide="prev">
                    <span class="glyphicon glyphicon-chevron-left"></span>
                </a>
                <a class="right carousel-control" href="#myCarousel" data-slide="next">
                    <span class="glyphicon glyphicon-chevron-right"></span>
                </a>
            </div>
        </div>
    </div>
    <br>
    <h1 class="learn"
        style="font-size: 50px; font-family: Georgia, 'Times New Roman', Times, serif; padding-left: 30px;">Learn a
        Variety of Dance</h1>
    <br>
    <div class="row">
        <div class="col-sm-4">
            <div class="thumbnail">
                <img src="img1.jpg" alt="">
                <div class="caption" style="text-align: center;">Hip Hop</div>
            </div>
        </div>
        <div class="col-sm-4">
            <div class="thumbnail">
                <img src="img2.jpg" alt="">
                <div class="caption" style="text-align: center;">Contempory</div>
            </div>
        </div>
        <div class="col-sm-4">
            <div class="thumbnail">
                <img src="img3.jpg" alt="">
                <div class="caption" style="text-align: center;">Dance Workout</div>
            </div>
        </div>
        <div class="col-sm-4" style="float: right;">
            <div class="thumbnail">
                <img src="img4.jpg" alt="">
                <div class="caption" style="text-align: center;">Ballet</div>
            </div>
        </div>
        <div class="col-sm-4">
            <div class="thumbnail">
                <img src="img7.jpg" alt="">
                <div class="caption" style="text-align: center;">Salsa</div>
            </div>
        </div>
        <div class="col-sm-4">
            <div class="thumbnail">
                <img src="img8.jpg" alt="">
                <div class="caption" style="text-align: center;">Jazz</div>
            </div>
        </div>
    </div>
    <br>
    <div class="page" style="text-align: center;">
        <ul class="pagination">
            <li class="active"><a href="#">1</a></li>
            <li><a href="#">2</a></li>
            <li><a href="#">3</a></li>
            <li><a href="#">4</a></li>
        </ul>
    </div>
    <h1 class="learn"
        style="font-size: 50px; font-family: Georgia, 'Times New Roman', Times, serif; padding-left: 30px;">
        Step-by-Step Learning</h1>
    <p style="padding: 2px; padding-left: 32px;">Whether you are just starting out or you've got some training under
        your belt - we got you covered.</p>
    <br>
    <div class="row">
        <div class="col-sm-3">
            <div class="level-block" style="background-color: #f9ff32; padding: 4px; border-radius: 10px;">
                <h3 class="header" style="background-color: white; text-align: center;">BRAND NEW</h3>
                <h2 class="new">Got two left feet <br>Start with our 10-day intro program.</h2>
            </div>
        </div>
        <div class="col-sm-3">
            <div class="level-block" style="background-color: #bbf789; padding: 4px; border-radius: 10px;">
                <h3 class="header" style="background-color: white; text-align: center;">BEGINNER</h3>
                <h2 class="new">Got The Basic Down?<br>Level up with new moves and routines.</h2>
            </div>
        </div>
        <div class="col-sm-3">
            <div class="level-block" style="background-color: #5efe95; padding: 4px; border-radius: 10px;">
                <h3 class="header" style="background-color: white; text-align: center;">INTERMEDIATE</h3>
                <h2 class="new">Feel pretty confident?<br>Learn more challenges skills and pieces.</h2>
            </div>
        </div>
        <div class="col-sm-3">
            <div class="level-block" style="background-color:#08ffae; padding: 4px; border-radius: 10px;">
                <h3 class="header" style="background-color: white; text-align: center;">ADVANCED</h3>
                <h2 class="new">Already killin.it?Train with <br> the top choreographers in the game.</h2>
            </div>
        </div>
    </div>
    <br>
    <div class="container" id="aboutus">
        <h1 style="text-align: center; font-size: 60px; font-family: Georgia, 'Times New Roman', Times, serif;">Why
            Us</h1>
        <div class="col" style="background-color: bisque; border-radius: 60px;">
            <img src="step1.jpeg" height="275px" width="340px" style="margin: 20px;" alt="">
            <div class="col-md-6" style="float: right; padding:35px;margin-right:95px; ">
                <h1 style="font-size: 50px; font-family: cursive;">Risk Free</h1>
                <p>We understand that dance classes won't be for everyone. With that in mind our policy is "try
                    before you buy". At the same time we believe that we offer quality instruction at reasonable
                    rates. If you aren't sure whether you (or your child) wants to dance, you may try it first with
                    no risk. If you decide not to continue dancing with us then you owe nothing. If you do decide to
                    continue with us there is a one-time registration fee of $25 and you will be charged for the
                    trial class. Monthly fees for first-time students enrolling mid-month will be prorated.</p>
            </div>
        </div>
        <br>
        <div class="col" style="background-color: lemonchiffon; border-radius: 60px;">
            <img src="step2.jpeg" height="275px" style="margin: 20px;" width="340px" alt="">
            <div class="col-md-6" style="margin: 70px;">
                <h1 style="font-family: cursive; font-size: 50px;">Dance Team</h1>
                <p>Northern Dance Academy has a competitive dance team that performs throughout the Northwest.
                    Tryouts for the Dance Team are held at the end of each season for the following season. If
                    interested, please contact us.</p>
            </div>
        </div>
    </div>
    <div class="container-fluid" style="text-align: center;" id="previous">
        <h1 style="font-size: 60px; font-family: Georgia, 'Times New Roman', Times, serif;">Dance Events of D2X
            Academy</h1>
        <ul class="breadcrumb" style="background-color: #bbf789;">
            <li><a href="#">Home</a></li>
            <li><a href="#">Events</a></li>
            <li><a href="#">Previous Events</a></li>
            <li><a href="#">Upcoming Events</a></li>
            <li><a href="#">Virtual Events</a></li>
        </ul>
        <h3 style="font-family: Georgia, 'Times New Roman', Times, serif; font-size: 30px;">Previous Events</h3>
        <br>
        <div class="col-sm-3">
            <img src="dd1.webp" height="260px" width="300px" alt="">
            <h2>Danceizere 2016</h2>
        </div>
        <div class="col-sm-3">
            <img src="dd2.jpeg" height="260px" width="300px" alt="">
            <h2>Danceizere 2017</h2>
        </div>
        <div class="col-sm-3">
            <img src="dd3.png" height="260px" width="300px" alt="">
            <h2>Danceizere 2019</h2>
        </div>
        <div class="col-sm-3">
            <img src="dd4.jpg" height="260px" width="300px" alt="">
            <h2>Danceizere 2020</h2>
        </div>
    </div>
    <br>
    <br>
    <div class="container" id="upcoming">
        <h3 style="font-family: Georgia, 'Times New Roman', Times, serif; font-size: 30px; text-align: center;">Upcoming
            Events</h3>
        <div class="col-sm-3" style="color: red;">
            <div class="thumbnail" style="border-color: blueviolet; border-width: 5px;">
                <b>April 15</b>
                <h3>Fall Registration Opens</h3>
            </div>
        </div>
        <div class="col-sm-3" style="color:slateblue">
            <div class="thumbnail" style="border-color: orchid; border-width: 5px;">
                <b>April 15-April 22</b>
                <h3>No classes Spring Break</h3>
            </div>
        </div>
        <div class="col-sm-3" style="color: #03b479;">
            <div class="thumbnail" style="border-color: #9aff00; border-width: 5px;">
                <b>April 30</b>
                <h3>Freestyle Fridays</h3>
                <p>Sat 6:00 pm - 8:00 pm</p>
            </div>
        </div>
        <div class="col-sm-3" style="color: blue;">
            <div class="thumbnail" style="border-color: chocolate; border-width: 5px;">
                <b>April 30</b>
                <h3>Last Day of Dance Classes</h3>
            </div>
        </div>
    </div>
    <div class="container-fluid" id="virtual">
        <h1 style="text-align: center; font-size: 30px; font-family: Georgia, 'Times New Roman', Times, serif;">Virtual
            Events</h1>
        <div class="row" style="display: flex; padding: 50px; background-color: #a2fefe;">
            <img src="vir1.jpeg" height="270px" width="300px" alt="">
            <p style="padding: 72px; font-size: 20px;">We were lucky that we did figure out some ways to host a few
                (smaller) Finals competitions throughout the
                summer, and they were great. Seeing how appreciative and excited these kids and studios were just to be
                back dancing was amazing!</p>
        </div>
        <div class="row" style="display: flex; padding: 50px; background-color: aquamarine">
            <img src="vir2.jpeg" height="270px" width="300px" alt="">
            <p style="padding: 72px; font-size: 20px;">Our biggest challenge was figuring out how to still provide
                dancers with that “competition experience”
                even for a virtual event. A few other competitions in our industry were also doing virtual events, but
                they were having dancers submit videos from past competitions or past performances. For us, this
                defeated the purpose. We wanted to get kids back dancing and studios a reason to open their doors.</p>
        </div>
        <div class="row" style="display: flex; padding: 50px; background-color: #00d88f">
            <img src="vir3.jpg" height="270px" width="300px" alt="">
            <p style="padding: 72px; font-size: 20px;">This is a great question! Honestly, everyone is doing it
                differently. But for us, virtual works almost
                exactly like in-person competition. You perform, you're judged, and you receive your award. It was
                important for us to keep this experience the same for dancers. We also wanted to give studios a chance
                to keep their doors open and classes running. So basically,
                studios or dancers have to record themselves performing their routine in full costume, hair, and makeup
                just like they would at a normal competition.</p>
        </div>
    </div>
    <div class="container" id="category">
        <h1 style="text-align: center; font-size: 60px; font-family: Georgia, 'Times New Roman', Times, serif;">
            Categories</h1>
        <table class="table">
            <thead style="background-color: #f845fe;">
                <tr>
                    <th>Category</th>
                    <th>Number of Dancers</th>
                </tr>
            </thead>
            <tbody style="background-color: #f2c5ff;">
                <tr>
                    <td>Solos</td>
                    <td>1 Dancer</td>
                </tr>
                <tr>
                    <td>Duets/Trios</td>
                    <td>2-3 Dancers</td>
                </tr>
                <tr>
                    <td>Small Groups</td>
                    <td>4-9 Dancer</td>
                </tr>
                <tr>
                    <td>Large Groups</td>
                    <td>10-12 Dancer</td>
                </tr>
                <tr>
                    <td>Extended Lines</td>
                    <td>17-20 Dancer</td>
                </tr>
            </tbody>
        </table>
    </div>
    <div class="container" id="contactus">
        <h1 style="text-align: center; font-size: 60px; font-family: Georgia, 'Times New Roman', Times, serif;">
            Contact Us</h1>
        <h2 style="text-align: center; background-color: rgb(165, 165, 165);">Overview</h2>
        <p style="text-align: center;">The mission of D2X Academy is to inspire the growth of youth, families and
            the community through quality
            Dance and Music programs. </p>
        <div class="section">
            <h3><b>Contact Us:</b></h3>
            <p>838-928-2721 or info@d2xacademy.org</p>
            <br>
            <h3><b>Summer Office Hours:</b></h3>
            <p>Monday-Friday, 9am-6pm</p>
            <br>
            <h3><b>Address:</b></h3>
            <p>3415 Sector-4 Bokaro Steel City, Jharkhand</p>
            <br>
            <h3><b>Travel:</b></h3>
            <p>By public transportation take 2/5 trains to Gunhill Road; Metro-North to Williams Bridge; or Bx 28, 30,
                38, 39, 41 and Bx M11 buses. There is no parking lot on site.</p>
            <br>
            <h3><b>Accessibility</b></h3>
            <p>Our facilities are ADA accessible equipped with an elevator and exterior ramp.</p>
        </div>
    </div>
    <div class="container-fluid">
        <h1 style="font-size: 60px; font-family: Georgia, 'Times New Roman', Times, serif;">Pick Your Plan</h1>
        <h4>Sign up for a Premium plan to get unlimited access to 1500+ classes and our full range of instructors.</h4>
        <br>
        <div class="col-md-4"
            style="background-color: bisque; margin: 10px; border-radius: 15px; margin-left: 100px; text-align: center;">
            <h2>MONTHLY PLAN</h2>
            <br>
            <h1>$20/month</h1>
            <h6>$20 billed monthly.</h6>
            <br>
            <div class="section">
                <h3 style="background-color:white ;">START FREE 7 DAY TRIAL</h3>
            </div>
        </div>
        <div class="col-md-4"
            style="background-color: rgb(203, 255, 121); margin: 10px; border-radius: 15px; margin-left: 284px; text-align: center;">
            <h2>ANNUAL PLAN</h2>
            <br>
            <h1>$8.33/month <span class="label label-danger" style="font-size: 10px; position: absolute;">New
                    Offer</span></h1>
            <h6>$100 billed annualy.</h6>
            <br>
            <div class="section">
                <h3 style="background-color:rgb(161, 161, 247) ;">START FREE 7 DAY TRIAL</h3>
            </div>
        </div>
    </div>
    <br>
    <div class="container-fluid" style="background-color: #5efe95;">
        <div class="col-md-4">
            <h1 class="glyphicon glyphicon-heart-empty"> 1500+ CLASSES</h1>
        </div>
        <div class="col-md-4">
            <h1 class="glyphicon glyphicon-thumbs-up">10+ BEGINNER PROGRAMS</h1>
        </div>
        <div class="col-md-4">
            <h1>150+ INSTRUCTORS</h1>
        </div>
    </div>
    <div class="container-fluid" style="background-color: black; color: rgb(253, 230, 50);">
        <div class="col-md-3">
            <h4>About D2X</h4>
            <p>The D2X comprises of the D2X academy and D2X student repertory company.</p>
        </div>
        <div class="col-md-3">
            <h4>NEW DELHI</h4>
            <p>The D2X, C-2, Creche Plot, Sushant Lok Phase 1,</p>
            <p>Near Vyapar Kendra,</p>
            <p>Gurgaon - 122 002,</p>
            <p>Haryana, India.</p>
        </div>
        <div class="col-md-3">
            <h4>MUMBAI OFFICE</h4>
            <p>The D2X, 314, Laxmi Business Park,</p>
            <p>Laxmi Industrial estate,</p>
            <p>Mumbai - 400053,</p>
            <p>Maharashtra, India.</p>
        </div>
        <div class="col-md-3">
            <h4>INDANCE PERFORMING ARTS PVT LTD</h4>
            <p>53, Iris Park,</p>
            <p>Plot no 40-41, Military Road</p>
            <p>JUHU, Mumbai 400049</p>
            <p>Ph no.: 9892827921</p>
        </div>
    </div>



</body>

</html>
