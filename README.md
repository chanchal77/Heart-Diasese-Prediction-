# Heart-Diasese-Prediction
<html>
  <body>
    <h2> Table of content </h2><br>
      &#x2686; <a href ="#Installation"> Installation </a><br>
      &#x2686;<a href ="#Run"> Run </a><br>
      &#x2686; <a href ="#Deployement on Heroku"> Deployement on Heroku </a><br> 
      &#x2686; <a href ="#Flowchart"> Flowchart </a> <br>
      &#x2686;  <a href ="#Technologies Used">Technologies Used</a>  <br>
      
    
   <h2><div id = "Installation">Installation</div> </h2><br>
        The Code is written in Python 3.8. If you don't have Python installed you can find it ,<a href ="https://www.python.org/downloads/release/python-380/" >here</a>.         If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory<br>
   
    pip install -r requirements.txt
  <h2><div id = "Run">Run</div> </h2><br>
  
  <h2><div id = "Deployement on Heroku">Deployement on Heroku</div> </h2><br>
    <b>Heroku : Platform as a Service(PaaS)</b> 
    <br>To run your project on local service you can deploy it on heroku platform.<br>
    you need to login,create app,install Heroku CLI .and have to run this commands using git CMD if you dont have git you can find it <a href ="https://git-scm.com/download/win" >here.</a><br>
 
    $ heroku login
    $ cd my-project/
    $ git init
    $ heroku git:remote -a hertdisease-predictoreapp
    $ git add .
    $ git commit -am "make it better"
    $ git push heroku master
    $ heroku git:remote -a hertdisease-predictoreap
    
  <h2><div id = "Flowchart">Flowchart</div> </h2><br>
    <img src="https://github.com/chanchal77/Heart-Diasese-Prediction-/blob/main/heart%20disease%20predictor/flowchart.png?raw=true">
  <h2><div id = "Technologies Used">Technologies Used</div> </h2><br>
    Language used : Python<br>
    libraries used : Numpy, Pandas, Matplotlib<br>
    Domain : Machin learning <br>
    platform : heroku
   
    
 </body></html> 
 

