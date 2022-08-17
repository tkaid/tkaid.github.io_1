# Unit-_11_Homework_Web_Visualization_Dashboard

<!DOCTYPE html>
<html lang="en">



  <head>
  <meta charset="UTF-8">
  <title>Bootstrap Visualization Dashboard</title>

<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa"
        crossorigin="anonymous"></script>

  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
  <link rel="stylesheet" href="style.css">
  
</head>
  
<body>
<nav class="navbar navbar-default">
 <div class="container-fluid">
   
   <div class="navbar-header">
     <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1" aria-expanded="false">
       <span class="sr-only">Toggle navigation</span>
       <span class="icon-bar"></span>
       <span class="icon-bar"></span>
       <span class="icon-bar"></span>
     </button>
     <a class="navbar-brand">Lattitude</a>
   </div>

  
   <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
     <ul class="nav navbar-nav navbar-right">
       <li class="dropdown">
         <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Plots<span class="caret"></span></a>
         <ul class="dropdown-menu">
           <li><a href="max_temp.html">Max Temperature</a></li>
           <li><a href="humidity.html">Humidity</a></li>
           <li><a href="cloudiness.html">Cloudiness</a></li>
           <li><a href="Wind_Speed.html">Wind Speed</a></li>
         </ul>
       </li>
       <li><a href="comparisons.html">Comparisons</a></li>
       <li><a href="data.html">Data</a></li>
     </ul>
   </div>
 </div>
</nav>

 

  
  <main class="container">
  <div class = "row" > 
  <div class ="col-md-6"> 


  <h1>Summary: Latitude vs. X </h1>
  
    <section id="main-bio">
      <section id="figure">
        
        <img id="bio-image" src="/Users/tamanikaid/Desktop/Unit-_11_Homework_Web_Visualization_Dashboard/Resources/assets/images/Fig1.png" class="col-sm-12 col-md-6" style="width:40%";>
      </section>
      <p>The purpose of this project was to analyse how weather changes as you get closer to the equator.  To accomplish this analysis, we first pulled data from the OpenWeathterMap API to assemble a dataset on over 500 cities.</p>
    
    <p>After assembling the dataset, we used Matplotlb to plot various aspects of the weather vs. lattitude.  Factors we looked at included: temperature, cloudiness, wind speed and humidity.  This site provides the source data and visualizations created as part of the analysis, as well as explanations and descriptions of any trends and correlations witnessed.</p>
    </section>
    </div>
    <div class ="col-md-6"> 
    <aside id="Visualizations">
      <h2>Visualizations</h2>
      <ul>
        <li><img id="bio-image" src="/Users/tamanikaid/Desktop/Unit-_11_Homework_Web_Visualization_Dashboard/Resources/assets/images/Fig1.png" class="col-sm-12 col-md-6" style="width:40%";></li>
        <li><img id="bio-image" src="/Users/tamanikaid/Desktop/Unit-_11_Homework_Web_Visualization_Dashboard/Resources/assets/images/Fig2.png" class="col-sm-12 col-md-6" style="width:40%";></li>
        <li><img id="bio-image" src="/Users/tamanikaid/Desktop/Unit-_11_Homework_Web_Visualization_Dashboard/Resources/assets/images/Fig3.png" class="col-sm-12 col-md-6" style="width:40%";></li>
        <li><img id="bio-image" src="/Users/tamanikaid/Desktop/Unit-_11_Homework_Web_Visualization_Dashboard/Resources/assets/images/Fig4.png" class="col-sm-12 col-md-6" style="width:40%";></li>

      </ul>
    </aside>

   </div>  
  </div>  
  </main>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  
</body>
</html>
