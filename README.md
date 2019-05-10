# newone<!DOCTYPE html>
<html lang="en">
<head>
 
  <title>Module3 Solution</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.0/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
  <link rel="stylesheet" href="styles1.css">
</head>
<body>

<nav class="navbar navbar-expand-md bg-dark navbar-dark">
  <a class="navbar-brand" href="#">FOOD,LCC</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
    <span class="navbar-toggler-icon"></span>
  </button>
  </nav>
  <div class="container-fluid">
  <div class="collapse navbar-collapse" id="collapsibleNavbar">
    <ul class="navbar-nav">
      <li class="nav-item">
        <a class="nav-link" href="#">Chicken</a><hr>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Beef</a><hr>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Sushi</a>
      </li>    
    </ul>
  </div> 
  </div>

<h1 class="center-aligned"> Our Menu</h1>


 <div class="row">
<div class="col-lg-4 col-md-6 col-xs-12">
<section class="p1">
  <h2>Chicken</h2>
  <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.
  Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,
  when an unknown printer took a galley of type and scrambled it to make a type 
  specimen book. It has survived not only five centuries, but also the leap into
  electronic typesetting, remaining essentially unchanged. hhhhhhhhhh hsdvcns 
  specimen book. including versions  including versions of Lorem Ipsum
  .<p>	</section>
</div>
<div class="col-lg-4 col-md-6 col-xs-12">
<section class="p2">
  <h2>Beef</h2>
  <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.
  Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,
  when an unknown printer took a galley of type and scrambled it to make a type 
  specimen book. It has survived not only five centuries, but also the leap into
  electronic typesetting, remaining essentially unchanged. It was popularised in
  the 1960s with the release of Letraset sheets containing Lorem Ipsum passages,
  and more recently with desktop publishing software like Aldus PageMaker 
  including versions of Lorem Ipsum including versions of Lorem Ipsum	.</p></section>
</div>
<div class="col-lg-4 col-md-12 col-xs-12">
<section class="p3">
  <h2>Sushi</h2>
  <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
	.</p>
	</section>
</div>
</div>
</div>
</body>

</html>
* {

    box-sizing: border-box;
    font-family: Helvetica;
}
nav{border: 1px solid black;}

body {
    background-color: white;
}

 ul{
     text-align: center;
 border: 2px solid black;
  margin-top:0.4px;
 margin-left:-15px;
 margin-right:120px;
 margin-bottom: 2px;
  width: 707px;
box-sizing: border-box; 


}
hr{border: 1px solid black;}


h1 {  text-align:center;

}
h2 {
    text-align: center;   

}

section {
    border: 1px solid black;
    background-color: #b5c4d2;
    margin: 10px;

}

section>p {
    padding: 30px 15px 15px 15px;
}

.row {
    width: 100%;
}
      
/********** larger view options **********/

@media(min-width: 992px) {
    .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
        float: left;
    }
    .col-lg-1 {
        width: 8.33%;
    }
    .col-lg-2 {
        width: 16.66%;
    }
    .col-lg-3 {
        width: 25%;
    }
    .col-lg-4 {
        width: 33.33%;
    }
    .col-lg-5 {
        width: 41.66%;
    }
    .col-lg-6 {
        width: 50%;
    }
    .col-lg-7 {
        width: 58.33%;
    }
    .col-lg-8 {
        width: 66.66%;
    }
    .col-lg-9 {
        width: 74.99%;
    }
    .col-lg-10 {
        width: 83.33%;
    }
    .col-lg-11 {
        width: 91.66%;
    }
    .col-lg-12 {
        width: 100%;
    }
}


/********** medium view options **********/

@media(min-width: 768px) and (max-width: 991px) {
    .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
        float: left;
    }
    .col-md-1 {
        width: 8.33%;
    }
    .col-md-2 {
        width: 16.66%;
    }
    .col-md-3 {
        width: 25%;
    }
    .col-md-4 {
        width: 33.33%;
    }
    .col-md-5 {
        width: 41.66%;
    }
    .col-md-6 {
        width: 50%;
    }
    .col-md-7 {
        width: 58.33%;
    }
    .col-md-8 {
        width: 66.66%;
    }
    .col-md-9 {
        width: 74.99%;
    }
    .col-md-10 {
        width: 83.33%;
    }
    .col-md-11 {
        width: 91.66%;
    }
    .col-md-12 {
        width: 100%;
    }
}
/* small Mobile view options */

@media(max-width: 767px) {
    .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
        float: left;
    }
    .col-sm-1 {
        width: 8.33%;
    }
    .col-sm-2 {
        width: 16.66%;
    }
    .col-sm-3 {
        width: 25%;
    }
    .col-sm-4 {
        width: 33.33%;
    }
    .col-sm-5 {
        width: 41.66%;
    }
    .col-sm-6 {
        width: 50%;
    }
    .col-sm-7 {
        width: 58.33%;
    }
    .col-sm-8 {
        width: 66.66%;
    }
    .col-sm-9 {
        width: 74.99%;
    }
    .col-sm-10 {
        width: 83.33%;
    }
    .col-sm-11 {
        width: 91.66%;
    }
    .col-sm-12 {
        width: 100%;
    }
}
