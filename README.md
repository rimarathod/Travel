<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style type ="text/css">
        
        header{
            width: 100%;
           height:100vh;
            background:linear-gradient(rgba(0,0,0,0.3),rgba(0,0,0,0.3)),
                     url('D:\nature.jpg');
            background-size:cover;
            font-family: sans-serif;
            background-position: center;
        }
        nav{
            width:100%;
            height:100px;
            display: flex;
            color:white;
          
            justify-content:space-around;
            align-items: center;

        }
        .logo{
            font-size:2em;
            letter-spacing:2px;
        }
        .nav-links li{
            list-style: none;
            display: inline-block;
            margin:10px 30px;

        }
        .nav-links li a{
            text-decoration: none;
            color:white;
        }

       
        
        .register a{
            text-decoration: none;
            color:black;
            padding: 8px 20px;
            font-size: 14px;
            background: #fff;
            border-radius: 20px;

        }
        .container{
            padding:0 5%;

        }
       header h1{
            font-size:4vw;
            font-weight:500;
            color:white;
            text-align:center;
            padding-top:10%;
        }
        
        .search-bar{
            width:84%;
            background: #fff;
            border-radius: 50px;
            padding:10px 10px 6px 30px;
            margin:20px auto;

        }
        .search-bar form{
            display:flex;
            align-items:center;
            flex-wrap:wrap;

        }
        .search-bar form input{
            border:0;
            display:block;
            outline:none;
            background: transparent;

        }
        .search-bar form button{
            background:lightpink;
            border-radius: 30px;
            width:15%;
            height:30px;
            cursor: pointer;
        }
        .location-in{
            flex :1;
        }
        .search-bar form label{
            font-weight: 600;
        }
      
    </style>
</head>
<body>
    <header>
        <nav>
        <div class="logo">Travel-X</div>
    
            <ul class="nav-links">
           <li><a href="popular.html">POPULAR PLACES</a></li>
            <li><a href="travel-1.html">TRAVEL OUTSIDE</a></li>
            <li><a href="online.html">ONLINE TICKET</a></li>
            <li><a href="contact.html">CONTACT </a></li>
            </ul>
        </div>
        <div class="register">
            <a href="#" >Register Now</a>
        </div>
        </nav>
        <div class="container">
            <h1>Find Your Next Stay</h1>
            <div class="search-bar">
                <form>
                    <div class="location-in">
                        <label>Location</label>
                        <input type="text" placeholder="where are you going?">
                    </div>
                      
                   <div>
                        <label>Check in</label>
                        <input type="text" placeholder="Add date">
                    </div>
                    
                    <div>
                        <label>Check out</label>
                        <input type="text" placeholder="Add date">
                    </div>
                    <div>
                        <label>Guest</label>
                        <input type="text" placeholder="Add guest">
                    </div>
                    <button type="submit">submit</button>
                </form>
            </div>
        </div>
        </div>
        
    
            </div>
        
        
    
    </header>
    
</body>
</html>
