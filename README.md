# Web Design using Bootstrap Framework

## AIM:
To design a website using bootstrap framework.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using bootstrap grid system.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
## Home html:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <title>BPRD</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>

<div class="p-5 bg-info text-white text-center">
    <h1>Bureau of Cyber Crime In India</h1>
    <h3>Ministry of Home Affairs</h3> 
</div>

<nav class="navbar navbar-expand-sm bg-dark navbar-dark">
  <div class="container-fluid">
    <ul class="navbar-nav">
        <li class="nav-item">
            <a class="nav-link active" href="/static/home.html">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"></a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" href="/static/gallery.html">Gallery</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" href="/static/about.html">About Us</a>
          </li>
    </ul>
  </div>
</nav>
<div class="text-center">
      <img src="./cyberlogo.png" alt="police"/>
  </div>

    <h1>
        what is cyber crime
    </h1>
    <p>
       <h4> Cybercrime is a broad term that is used to define criminal activity in which computers or computer networks are a tool, a target, or a place of criminal activity and include everything from electronic wracking to denial of service attacks</p></p><p> It is a general term that covers crimes like phishing, Credit card frauds, bank robbery, illegal downloading, industrial espionage, child pornography, kidnapping children via chat rooms, scams, cyber terrorism, creation and or distribution of viruses, spam and so on.</p>
       </h4>
    </p>
    <p>
        <h3>
            It also covers that traditional crimes in which computers or networks are used to enable the illicit activity. Cyber crime is increasing day by day, nowadays it has become a new fashion to earn money by fraud calls or to take revenge through hacking other accounts.
        </h3>
    </p>
    <p>
        <h4>Cyber Laws:
            
        </h4>
        <p>
            <h4>Cyber crimes are anew class of crimes which are increasing day by day due to extensive use of internet these days. <p>To combat the crimes related to internet The Information Technology Act, 2000 was enacted with prime objective to create an enabling environment for commercial use of I.T.</p> <p>The IT Act specifies the acts which have been made punishable. The Indian Penal Code, 1860 has also been amended to take into its purview cyber crimes.</p>
            </h4>
        </p>
    </p>
    </div>
  </div>
</div>
<div class="text-center">
  <img src="./cyber india.jpg" alt="bureau-of-police-research-and-development"/>
</div>



<div class="mt-5 p-4 bg-danger text-black text-center">
  <p></p>This code Developed
  By Prethiveerajan P
</div>

</body>
</html>

## Gallery page:
<!DOCTYPE html>
<html lang="en">
<head>
  <title>BPRD</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
  <style>
  .fakeimg {
    height: 200px;
    background: #aaa;
  }
  </style>
</head>
<body>

<div class="p-5 bg-info text-white text-center">
    <h1>Bureau of Cyber Crime In Indiat</h1>
    <h3>Ministry of Home Affairs</h3> 
</div>

<nav class="navbar navbar-expand-sm bg-dark navbar-dark">
  <div class="container-fluid">
    <ul class="navbar-nav">
        <li class="nav-item">
            <a class="nav-link active" href="/static/home.html">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"></a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" href="/static/gallery.html">Gallery</a>
          </li>
          
          <li class="nav-item">
            <a class="nav-link active" href="/static/about.html">About Us</a>
          </li>
    </ul>
  </div>
</nav>

<div class="container mt-5">
  <div class="row">
    <div class="col-sm-4">
        
      <ul class="nav nav-pills flex-column">
        <li class="nav-item">
            <h3 class="mt-4">Links on News and Events</h3>
            <p>Click below</p>
            <a class="nav-link active" href="https://cybercrime.gov.in/Webform/Crime_AuthoLogin.aspx">Cyber Crime India  Portal</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"></a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" href="https://en.wikipedia.org/w/index.php?search=Cybercrime+in+India&title=Special:Search&profile=advanced&fulltext=1&ns0=1">wikipedia of Cyber Crime India  Portal</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"></a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" href="https://twitter.com/cybercellindia?lang=en">Twitter of Cybercrime</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"></a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" href="https://timesofindia.indiatimes.com/topic/cybercrime">Important News</a>
          </li>
      </ul>
      <hr class="d-sm-none">
    </div>
    <div class="col-sm-8">
      <h2>GALLERY:</h2>
      <h3> This are some images of The given website a side
        
      </h3>
    </br>
      <img src="./official.png"   style="height:150px;"  alt="police">
      <img src="./wikki.png"   style="height:150px;"  alt="police">
      <img src="./twitter.png"   style="height:150px;"  alt="police">
      <img src="./crimes.png"   style="height:150px;"  alt="police">
    </div>
  </div>
</div>

<div class="mt-5 p-4 bg-danger text-black text-center">
    <p></p>This code Developed
    By Prethiveerajan P
  </div>
  
</body>
</html>

## about us page:

<!DOCTYPE html>
<html lang="en">
<head>
  <title>BPRD</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
  <style>
  .fakeimg {
    height: 300px;
    background: rgb(180, 69, 69);
  }
  </style>
</head>
<body>

<div class="p-5 bg-info text-dark text-center">
    <h1>Bureau of Cyber Crime In India</h1>
    <p>Ministry of Home Affairs</p> 
</div>

<nav class="navbar navbar-expand-sm bg-white navbar-white">
  <div class="container-fluid">
    <ul class="navbar-nav">
        <li class="nav-item">
            <a class="nav-link active" href="/static/home.html">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"></a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" href="/static/gallery.html">Gallery</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"></a>
          </li>
          
          <li class="nav-item">
            <a class="nav-link active" href="/static/about.html">About Us</a>
          </li>
    </ul>
  </div>
</nav>


    <div class="col-sm-8">
      <h2>ABOUT US</h2>
      <h5>CREATION:</h5>
      <p> 1. The Government of India vide Resolution No.8/136/68-P.I (Pers.I) dated 28.08.1970 formally established the Bureau of Cyber Crime In India , under the Ministry of Home Affairs giving a new orientation to then existing Police Research and Advisory Council (1966) for the following reasons and with the primary objective of modernization of police force </p>
      <p>2.The Bureau was established with the following two divisions initially with a well laid out charter of duties</p>
      <p>Research, Statistics and Publication</p>
      
    </div>
  </div>
</div>


<div class="mt-5 p-4 bg-danger text-black text-center">
  <p></p>This code Developed
  By Prethiveerajan P
</div>

</body>
</html>
```

## OUTPUT:

### Home Page:
![OUTPUT]![home](https://user-images.githubusercontent.com/94233064/153750452-ab8adc73-30ad-44dd-a1ea-37267c4c8f0b.png)


## Gallery Page:
![OUTPUT]![gallery](https://user-images.githubusercontent.com/94233064/153750560-e301897e-cef6-42a2-b424-2b934449f1d6.png)

  
## About us:
![OUTPUT![aboutus](https://user-images.githubusercontent.com/94233064/153750553-35f6f06c-0f3e-49e3-90d2-e088e50dc47c.png)





## Result:
 THUS WE SUCCESSFULLY MADE THE WEBSITE USING BOOTSTRAP

