# Task-1
<!DOCTYPE html>
<html>
    <head>
        <title> Landing page </title>
        <style type="text/css">
            *{padding:0;margin: 0;box-sizing: border-box;}
            header{
                width:100%;
                height:100vh;
                background-image:linear-gradient(rgba(0,0,0,0.8),rgba(0,0,0,0.2)),url('https://us.123rf.com/450wm/olegdudko/olegdudko1906/olegdudko190603357/124928686-collection-of-old-books-on-wooden-desk.jpg?ver=6');
                font-family: sans-serif;
            }
            nav{
                width:100%;
                height:100px;
                color:brown;
                display: flex;
                justify-items: space-around;
                align-items: center;
            }
           .logo{
            font-size: 2em;
            letter-spacing: 2px;
           }
           .menu a{
            text-decoration: none;
            color:white;
            padding:10px 20px;
            font-size: 20px;
            position: relative;
           }
           .menu a:before{
            content: '';
            position:absolute;
            top:0;
            left:0;
            width:0%;
            height:100%;
            border-bottom: 2px solid indianred;
            transition: 0.4% linear;
           }
           .menu a:hover:before{
            width:90%;
           }
           .register a{
            text-decoration: none;
            color:white;
            padding:10px 20px;
            font-size: 20px;
            background: indianred;
            border-radius: 8px;
            transition:0.4s;
           }
           .register a:hover{
            background:transparent;
            border:1px solid indianred;
           }
           .h-txt{
            max-width: 650px;
            position:absolute;
            top:50%;
            left:50%;
            transform:translate(-50%,-50%);
            text-align: center;
            color:white;
           }
           .h-text span{
            letter-spacing: 5px;
           }
           .h-txt h1{
            font-size: 3.0em;
           }
           .h-txt a{
            text-decoration: none;
            background: indianred;
            color:white;
            padding:10px 20px;
            letter-spacing: 5px;
            transition: 0.4s;
           }
           .h-txt a:hover{
            background:transparent;
            border:1px solid indianred;
           }          
    </style>
    </head>
    <bodY>
        <header>
            <nav>
                <div class="logo">
                    Books
                </div>
                <div class="menu">
                    <a href="#">Home</a>
                    <a href="#">Book Bank</a>
                    <a href="#">Best offers</a>
                    <a href="#">Our sites</a>
                    <a href="#">Contact</a>
                </div>
                <div class="register">
                    <a href="#">Register</a>
                </div>
            </nav>
            <section class="h-txt">
                <span>Enjoy</span>
                <h1>Reading for all time!</h1>
                <br>
                <a href="#">Book Now</a>
            </section>
        </header>
    </bodY>
</html>
