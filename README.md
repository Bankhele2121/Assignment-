
Assignment 1
Html file 
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap Assignment 1</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <link rel="stylesheet" href="/assignment 1/css/style.css">
</head>
<body>  
<div class="container-fluid">
  <div class="row">
    <div class="col-lg-3 col-md-4 col-sm-5 col-xs-12">
        <div class="d1">Box 1</div>
    </div>
    <div class="col-lg-3 col-md-4 col-sm-5 col-xs-12">
        <div class="d2">Box 2</div>
    </div>
    <div class="col-lg-3 col-md-4 col-sm-5 col-xs-12">
        <div class="d3">Box 3</div>
    </div>
    <div class="col-lg-3 col-md-4 col-sm-5 col-xs-12">
        <div class="d4">Box 4</div>
    </div>
    <div class="col-lg-3 col-md-4 col-sm-5 col-xs-12">
        <div class="d5">Box 5</div>
    </div>
    <div class="col-lg-3 col-md-4 col-sm-5 col-xs-12">
        <div class="d6">Box 6</div>
    </div>
    <div class="col-lg-3 col-md-4 col-sm-5 col-xs-12">
        <div class="d7">Box 7</div>
    </div>
    <div class="col-lg-3 col-md-4 col-sm-5 col-xs-12">
        <div class="d8">Box 8</div>
    </div>
  </div>
</div>

</body>
</html>
Css file
*{
    margin: 0;
    padding: 0;
}
.d1,.d2,.d3,.d4,.d5,.d6,.d7,.d8{
    border: 1px solid black;
    margin: 10px;
    padding: 10px;
}
/*CSS for the Large screen*/
@media screen and (min-width:1200px){
    .d1,.d2,.d3,.d4,.d5,.d6,.d7,.d8,.img-slider{
        background-color:lime;
        height: 80px    ;
    }

}
@media screen and (max-width:1200px){
    .d1,.d2,.d3,.d4,.d5,.d6,.d7,.d8,.img-slider{
        background-color:lightskyblue;
        height: 100px    ;
    }

}
@media screen and (max-width:990px){
    .d1,.d2,.d3,.d4,.d5,.d6,.d7,.d8,.img-slider{
        background-color:lightsalmon;
        height: 150px    ;
    }

}
@media screen and (max-width:770px){
    .d1,.d2,.d3,.d4,.d5,.d6,.d7,.d8,.img-slider{
        background-color:yellowgreen;
        height: 70px    ;
    }

}
Assignment 2nd-
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap Assignment 2</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <link rel="stylesheet" href="/Assignment 2/css/style.css">
</head>
<body>  
<div class="container-fluid">
  <div class="row">
    <div class="col-lg-3 col-md-4 col-sm-10 col-xs-6">
        <div class="d1">Box 1</div>
    </div>
    <div class="col-lg-9 col-md-8 col-sm-11 col-xs-6">
        <div class="d2">Box 2</div>
    </div>
    <div class="col-lg-9 col-md-12 col-sm-12 col-xs-9">
        <div class="d3">Box 3</div>
    </div>
    <div class="col-lg-3 col-md-10 col-sm-5 col-xs-3">
        <div class="d4">Box 4</div>
    </div>
    <div class="col-lg-3 col-md-2 col-sm-7 col-xs-7">
        <div class="d5">Box 5</div>
    </div>
    <div class="col-lg-9 col-md-7 col-sm-9 col-xs-5">
        <div class="d6">Box 6</div>
    </div>
    <div class="col-lg-6 col-md-5 col-sm-3 col-xs-12">
        <div class="d7">Box 7</div>
    </div>
    <div class="col-lg-6 col-md-12 col-sm-12 col-xs-12">
        <div class="d8">Box 8</div>
    </div>
  </div>
</div>

</body>
</html>
Css file-
{
    margin: 0;
    padding: 0;
}
.d1,.d2,.d3,.d4,.d5,.d6,.d7,.d8{
    border: 1px solid black;
    margin: 10px;
    padding: 10px;
}
/*CSS for the Large screen*/
@media screen and (min-width:1200px){
    .d1,.d2,.d3,.d4,.d5,.d6,.d7,.d8,.img-slider{
        background-color:lime;   
    }
    .d5,.d6{
        height: 80px;
    }

}
/*CSS for The medium screen*/
@media screen and (max-width:1200px){
    .d1,.d2,.d3,.d4,.d5,.d6,.d7,.d8,.img-slider{
        background-color:lightskyblue;
       
    }

}
/*CSS For the small screen*/
@media screen and (max-width:990px){
    .d1,.d2,.d3,.d4,.d5,.d6,.d7,.d8,.img-slider{
        background-color:lightsalmon;
      
    }
    .d1{
        margin-top: 100px;
    }

}
/*CSS for the extra small screen*/
@media screen and (max-width:770px){
    .d1,.d2,.d3,.d4,.d5,.d6,.d7,.d8,.img-slider{
        background-color:yellowgreen;
        margin: 10px;
    }
    .d1,.d2{
        height: 60px;
    }
    .d3,.d4,{
        height: 70px;
    }
    .d5,.d6,.d7,.d8{
        height: 90px;
    }
}
Assignment 3rd
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Bootstrap Assignment 3</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css"
        integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
    <link rel="stylesheet" href="./css/style.css">
</head>

<body>

    <div class="container-fluid">
        <div class="row">
            <div class="col-lg-3 col-md-3 col-sm-12 col-xs-12">
                <div class=d1>D1</div>
            </div>
            <div class="col-lg-9 col-md-9 col-sm-12 col-xs-12">
                <div class=d2>D2</div>
            </div>
            <div class="col-lg-3 col-md-3 col-sm-3 col-xs-6">
                <div class=d3>D3</div>
            </div>
            <div class="col-lg-3 col-md-6 col-sm-9 col-xs-6">
                <div class=d4>D4</div>
            </div>
            <div class="col-lg-3 col-md-3 col-sm-5 col-xs-6">
                <div class=d5>D5</div>
            </div>
            <div class="col-lg-3 col-md-7 col-sm-7 col-xs-6">
                <div class=d6>D6</div>
            </div>
            <div class="col-lg-12 col-md-5 col-sm-12 col-xs-12">
                <div class=d7>D7</div>
            </div>
            <div class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
                <div class=d8>D8</div>
            </div>
            
        </div>
    </div>
</body>

</html>
Css file - 
   margin: 10px;
    border: 1px solid black;
    padding: 10px;
}
@media screen and (max-width:1200px){
    .d7,.d6{
        height: 100px;
       
    }
    .d3,.d4,.d5{
        height: 100px;
        ;
    }
    .d8{
        height: 30px;
        
    }
    .d1,.d2,.d3,.d4,.d5,.d6,.d7,.d8{
        background-color: cadetblue;
    }
  
}
@media screen and (min-width:1200px){
  .d3,.d4,.d5,.d6{
      height: 150px;
  }
  .d7,.d8{
      height: 30px;
  }
  .d1,.d2,.d3,.d4,.d5,.d6,.d7,.d8{
    background-color: lawngreen;
}
}

@media screen and (max-width:990px){
    .d1,.d7,.d8{
        height: 30px;
        background-color: brown;
    }
    .d3,.d4{
        height: 200px;
    }
    .d5,.d6{
        height: 150px;
    }
    .d1,.d2,.d3,.d4,.d5,.d6,.d7,.d8{
        background-color: brown;
    }
}
@media screen and (max-width:770px){
    .d1{
        height: 40px;
    }
    .d2,.d8{
        height: 30px;
    }
    .d3,.d4,.d5,.d6{
        height: 150px;
    }
    .d7{
        height: 100px;
    }
    .d1,.d2,.d3,.d4,.d5,.d6,.d7,.d8{
        background-color: lightcoral
    }
}
Assignment 4 th-
Html file - 
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Bootstrap Assignment 4</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css"
        integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
    <link rel="stylesheet" href="./css/style.css">
</head>

<body>

    <div class="container-fluid">
        <div class="row">
            <div class="col-lg-3 col-md-3 col-sm-2 col-xs-2">
                <div class="d1 txt-center">Logo</div>
            </div>
            <div class="col-lg-9 col-md-9 col-sm-10 col-xs-10">
                <div class="d2 txt-center">Header And Banner</div>
            </div>
            <div class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
                <div class="d3 txt-center">Menu Bar </div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 col-xs-12">
                <div class="d4 txt-center">Content 1</div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 col-xs-12">
                <div class="d5 txt-center">Content 2</div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 col-xs-12">
                <div class="d6 txt-center">Content 3</div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 col-xs-12">
                <div class="d7 txt-center">Content 4</div>
            </div>
            <div class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
                <div class="d8 txt-center">Footer</div>
            </div>
            
        </div>
    </div>
</body>

</html>
Css file - 
{
    margin: 0%;
    padding: 0%;
}
.txt-center{
    text-align: center;
}


.d1,.d2,.d3,.d4,.d5,.d6,.d7,.d8{
    margin: 10px;
    border: 1px solid black;
    padding: 10px;
}
/* CSS for Large Screen*/
@media screen and (min-width:1200px){
    .d1,.d2,.d3,.d4,.d5,.d6,.d7,.d8{
        background-color: chartreuse;
    }
    .d1,.d2{
        height: 70px;
    }
    .d3{
        height: 50px;
    }
    .d4,.d5,.d6,.d7{
        height: 150px;
    }

}
/* CSS for Medium Screen*/
@media screen and (max-width:1200px){
    .d1,.d2,.d3,.d4,.d5,.d6,.d7,.d8{
        background-color: lightgreen;
    }
    .d1,.d2{
        height: 40px;
    }
    .d3{
        height: 50px;
    }
    .d4,.d5,.d6,.d7{
        height: 150px;
    }
}
/* CSS for Small Screen*/
@media screen and (max-width:990px){
    .d1,.d2,.d3,.d4,.d5,.d6,.d7,.d8{
        background-color: lightskyblue;
    }
    .d1,.d2{
        height: 60px;
    }
    .d3{
        height: 30px;
    }
    .d4,.d5,.d6,.d7{
        height: 200px;
    }
    .d8{
        height: 30px;
    }
}
/* CSS for Xtra Small Screen*/
@media screen and (max-width:770px){
    .d1,.d2{
        height: 40px;
    }
    .d4,.d5,.d6,.d7{
        height: 100px;
    }
    .d1,.d2,.d3,.d4,.d5,.d6,.d7,.d8{
        background-color: lightcoral
    }
}
Assignment 5th-
Html file 
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Bootstrap Assignment 5</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css"
        integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
    <link rel="stylesheet" href="./css/style.css">
</head>

<body>

    <div class="container-fluid">
        <div class="row">
            <div class="col-lg-3 col-md-3 col-sm-2 col-xs-2">
                <div class="d1 txt-center">Logo</div>
            </div>
            <div class="col-lg-9 col-md-9 col-sm-10 col-xs-10">
                <div class="d2 txt-center">Header And Banner</div>
            </div>
            <div class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
                <div class="d3 txt-center">Menu Bar </div>
            </div>
            <div class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
                <div class="img-slider txt-center">Image/slider</div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 col-xs-12">
                <div class="d4 txt-center">Content 1</div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 col-xs-12">
                <div class="d5 txt-center">Content 2</div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 col-xs-12">
                <div class="d6 txt-center">Content 3</div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 col-xs-12">
                <div class="d7 txt-center">Content 4</div>
            </div>
            <div class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
                <div class="d8 txt-center">Footer</div>
            </div>
            
            
        </div>
    </div>
</body>

</html>
Css file - 
{
    margin: 0%;
    padding: 0%;
}
.txt-center{
    text-align: center;
}


.d1,.d2,.d3,.d4,.d5,.d6,.d7,.d8,.img-slider{
    margin: 10px;
    border: 1px solid black;
    padding: 10px;
}
/* CSS for Large Screen*/
@media screen and (min-width:1200px){
    .d1,.d2,.d3,.d4,.d5,.d6,.d7,.d8,.img-slider{
        background-color: chartreuse;
    }
    .d1,.d2{
        height: 70px;
    }
    .d3{
        height: 30px;
    }
    .d4,.d5,.d6,.d7{
        height: 150px;
    }
    .img-slider{
        height: 130px;
    }

}
/* CSS for Medium Screen*/
@media screen and (max-width:1200px){
    .d1,.d2,.d3,.d4,.d5,.d6,.d7,.d8,.img-slider{
        background-color: lightgreen;
    }
    .d1,.d2{
        height: 40px;
    }
    .d3{
        height: 50px;
    }
    .d4,.d5,.d6,.d7{
        height: 150px;
    }
    .img-slider{
        height: 130px;
    }
    .d8{
        height: 30px;
    }
}
/* CSS for Small Screen*/
@media screen and (max-width:990px){
    .d1,.d2,.d3,.d4,.d5,.d6,.d7,.d8,.img-slider{
        background-color: lightskyblue;
    }
    .d1,.d2{
        height: 60px;
    }
    .d3{
        height: 30px;
    }
    .d4,.d5,.d6,.d7{
        height: 200px;
    }
    .d8{
        height: 30px;
    }
}
/* CSS for Xtra Small Screen*/
@media screen and (max-width:770px){
    .d1,.d2{
        height: 40px;
    }
    .d4,.d5,.d6,.d7{
        height: 100px;
    }
    .d1,.d2,.d3,.d4,.d5,.d6,.d7,.d8,.img-slider{
        background-color: lightcoral
    }
} 
