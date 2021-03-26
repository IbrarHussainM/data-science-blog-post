<h1>Data Science Blog Post</h1>

<p>Udacity Data Scientist Nanodegree Project.</p>


<h3>Table of Contents</h3>
<ol>
<li><a href="#installation">Installation</a></li>
<li><a href="#motivation">Project Motivation</a></li>
<li><a href="#files">File Description</a></li>
<li><a href="#results">Results</a></li>
<li><a href="#licensing">Licensing, Authors, and Acknowledgements</a></li>
</ol>

<h2><a id="user-content-installation">Installation</a></h2>
<p>This code runs with Python version 3.* and requires some libraries, to install theses libraries you will need to execute: <br>
<code>pip install -r requirements.txt</code></p>
<p>Also, You will need to download Stackoverflow’s 2017 and 2018 Annual Developer Survey and put them in specific folders. You can download data from<a href="https://insights.stackoverflow.com/survey" rel="nofollow">here</a>. <br></p>
<p>To move the downloaded files to the specific folder, you can execute. <br></p>
<ol>
<li>
<p>Stackoverflow’s 2017 data <br>
<code>mv survey_results_public.csv data-science-blog-post/data/2017/survey_results_public.csv</code><br></p>
</li>
<li>
<p>Stackoverflow’s 2018 data <br>
<code>mv survey_results_public.csv data-science-blog-post/data/2018/survey_results_public.csv</code><br></p>
</li>
</ol>

<h2><a id="user-content-motivation">Project Motivation</a></h2>
<p>I was interested in using Stackoverflow Developer Survey Data to better understand some of the below questions:<br></p>
<ol>
<li>What are the most used programming languages in Brazil? <br></li>
<li>What are the most wanted programming languages in Brazil? <br></li>
<li>How does programming languages used at work relates with programming languages people want to learn? <br></li>
</ol>

<h2><a id="user-content-files">File Description</a></h2>
<p><strong>exploratory_analysis.ipynb</strong>: Notebook containing the data analysis. <br>
<strong>data/2017/survey_results_public.csv</strong>: Stackoverflow's 2017 Annual Developer Survey data. <br>
<strong>data/2018/survey_results_public.csv</strong>: Stackoverflow's 2018 Annual Developer Survey data. <br></p>

<h2><a id="user-content-results">Results</a></h2>
<p>The main findings of the code are:</p>
 <ol>
  <li>We have seen that some older programming languages such as JavaScript, SQL, and Java still dominates.</li>
  <li>Younger programming languages like Python have been well-deserved to be learned, but the oldest ones still have their value and are being much demanded.</li>
  <li>People who already work with a certain programming language have a tendency to learn that language or related languages within correlated areas to improve their own skill.</li>
 </ol>

<h2><a id="user-content-licensing">Licensing, Authors, Acknowledgements</h2>
<p>Must give credit to Stackoverflow for the data. You can find the Licensing for the data and other descriptive information at the Stackoverflow link available <a href="https://insights.stackoverflow.com/survey" rel="nofollow">here</a>.</p>
