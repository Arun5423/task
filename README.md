<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>  
        *{
            padding: 0%;
            margin: 0%;
        }
        body{
            background-color: rgba(56, 168, 233, 0.877);
        }
      
        .vibes{
            display:block;
            margin: 0% 43%;
            width: 300px;
          text-align: center;
         position:relative;
         background-color: rgb(130, 221, 130);
           justify-content: center;
            border-radius: 10px;
        }
        .box{
            
          margin: 0% 35%;
          display: block;
           background-color: blanchedalmond;
           width: 500px;
           height:fit-content;
           border-radius: 15px;
           justify-content: center;
            box-shadow: grey;
        }
        .form{
          font-size: 22px;
          
        }
        .c1{
            margin: 10px 10px;
            padding: 5px 10px;
            font-size: 13px;
        }
        .button{
            background-color: honeydew;
            width: 100%;
            border-radius: 20px;
          
            height: 34px;
            font-size: 25px;
          color: green;
                  }
                  .button:hover{
                      color: rgb(76, 168, 76);
                      cursor: pointer;
                  }
                  #Gender{
                      font-size: 19px;
                      margin: -5px;
                      padding: 5px;
                  }
       .dropdown{
           cursor: pointer;
       }
       .dropdown:hover{
          font-size: 20px;
       }
     
    </style>
</head>
<body>
    <h1>
        <div class="vibes">Good Vibes Form
        </div>
        </h1>
    <div class="box">
        <h2>Tell us something positive that happened to you today.</h2>
    <form action="#" class="form">
        Name <input class="c1" type="text" placeholder="Enter your Name"><br>
        Email <input class="c1" type="email" placeholder="Enter your Email address">
        <div class="form">
            Gender <input  type="radio" name="male" >
            <label class="c1" id="Gender" for="male">male</label>
            <input type="radio" name="male">
            <label class="c1" id="Gender" for="male">Female</label>
            </div>
        <div>on a scale 1-10,How good was it <input class="c1" type="number" placeholder="Enter a no. between 1-10"></div>
  <label  for="dropdown">Where did it happen?</label>
  <select class="dropdown" name="Location of positive event"class="c1"  id="dropdown">
      <option value="Home">Home</option>
      <option value="Community">At Community</option>
      <option value="work">At work</option>
      <option value="street"> on the street</option>
      <option value="other ">other</option>
  </select>
  
<div>At what time of day it happen?</div>
<div> <input type="radio"name="Morning">Morning
</div>
<div> <input type="radio"name="Morning">Afternoon</div>
<div> <input type="radio"name="Morning">Evening
<div>What emotions did you experience?(Select all that apply)</div>
<div>
    <input type="checkbox" >Excited
</div>
<div> <input type="checkbox" >loved</div>
<div> <input type="checkbox" >humbled</div>
<div> <input type="checkbox" >Enthusiastic</div>
<button class="button">Submit</button>
    </form>
    </div>
</body>
</html>
