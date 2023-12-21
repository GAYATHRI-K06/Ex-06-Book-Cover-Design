# Ex-06-Book-Cover-Design


## AIM

  To Design a book cover page using HTML and CSS.

## DESIGN PROCEDURE

## Step 1:

Create a html file .

## Step 2:

Choose background image and photo to be used and save it to the repository. position the elements appropriately

## Step 3:
Use html and css code to design the book cover.

## code:

## HTML
``````
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Web Development Technologies</title>
        <link rel="stylesheet" href="book.css">
    </head>
    <body>
        <section class="web">
            <br><br>
        <span id="apple">EXPERT INSIGHT &nbsp;&nbsp;&nbsp;</span>
            <h1>Responsive Web Design with HTML5 and CSS</h1>
            <h4>Develop future-proof responsive websites using the latest HTML5 and CSS techniques</h4>
            <h3>Third Edition&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="picture2.jpg"></h3>
            <footer>
                <div id="brave" class="moon">
                    <span>Ben Frain</span>
                    <span id="cresant"><u>Packt></u></span>
                </div>
            </footer>
    </section>
    </body>
   </html>
``````
## CSS
``````
body{
    color:rgb(255, 255, 255);
    font-family: Helvetica, sans-serif;
    background-color: #1d1c1c
}

.web{
    width: 726px;
    height:891px;
    background-color:rgb(0, 0, 0);
    margin:auto;
    position: relative;
    background-image: url(3311.jpg);
    background-repeat: no-repeat;
    background-size:606px;
    background-position: bottom 150px center;
}
h1{
    font-size:70px;
    margin:50px;
    margin-bottom:0px;
}
h3{
    margin:0px 0px 90px 60px;
    position: absolute;
    bottom:0px;
    font-size: x-large;
    color: #f47027;
}


h4{
    font-size:20px;
    margin:60px;
   margin-top:10px;
   width:430px;
}
#apple{
    border-bottom:2px solid #f47027;
    padding:100px 0px 5px 30px;
}
footer{
    position: absolute;
    bottom: 0px;
    border-top:2px solid #f47027;
    padding-top:10px;
    width:726px;
}
#brave {
    display: flex;
    justify-content: space-between;
}
  #brave span{
    margin:10px 0px 20px 60px;
    font-size: xx-large;
    font-weight: bold;
}
#moon{
  padding-right:60px;
}

``````
## output
![Screenshot 2023-12-21 093006](https://github.com/GAYATHRI-K06/Ex-06-Book-Cover-Design/assets/145742742/ad6205bb-d7e8-4666-b2c7-af4ed4730912)


## Result

Thus The program is completed sucessfully.
