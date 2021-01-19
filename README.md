[![HitCount](http://hits.dwyl.com/hershyz/CRNN.svg)](http://hits.dwyl.com/hershyz/CRNN)
<p align="center">
<img src="https://raw.githubusercontent.com/sam-shridhar1950f/konnect-cs/master/logo.png"/>

</p>
<p align="center">
<i>Konnect, pioneering the combination of machine learning and inexpensive rehabilitation.</i>
</p>


<p align="center">
  The code in this repository was a software engineering project in the <a href="https://www.gcpsk12.org/gsmst">GSMST</a> engineering fair.<br/>
  Konnect is an intelligent, affordable assistive wearable constructed in the .NET framework.
</p>

<br/>
<p align="center">
<h3>Prototype:</h3>
<img src="https://raw.githubusercontent.com/sam-shridhar1950f/konnect-cs/master/Documentation/model.PNG"/>
</p>
<p align="center">
<h3>GUI:</h3>
<img src="https://raw.githubusercontent.com/sam-shridhar1950f/konnect-cs/master/Documentation/GUI.PNG"/>
</p>
<h3>Datasets:</h3>
<p>A dataset in a spreadsheet would look like this, having labels and text corresponding to numerical data.</p>
<table class="tg">
<thead>
  <tr>
    <th class="tg-0pky">Geographical Area</th>
    <th class="tg-0pky">Factor1</th>
    <th class="tg-0pky">Factor2</th>
    <th class="tg-0pky">Factor3</th>
    <th class="tg-0pky">Factor n...</th>
    <th class="tg-0lax">Confirmed COVID-19 Deaths</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky">area1</td>
    <td class="tg-0pky">#</td>
    <td class="tg-0pky">#</td>
    <td class="tg-0pky">#</td>
    <td class="tg-0pky">#</td>
    <td class="tg-0lax">x...</td>
  </tr>
  <tr>
    <td class="tg-0pky">area2</td>
    <td class="tg-0pky">#</td>
    <td class="tg-0pky">#</td>
    <td class="tg-0pky">#</td>
    <td class="tg-0pky">#</td>
    <td class="tg-0lax">y...</td>
  </tr>
  <tr>
    <td class="tg-0pky">area3</td>
    <td class="tg-0pky">#</td>
    <td class="tg-0pky">#</td>
    <td class="tg-0pky">#</td>
    <td class="tg-0pky">#</td>
    <td class="tg-0lax">z...</td>
  </tr>
</tbody>
</table>

<p>
  Training and prediction datasets passed into the network must be stripped of all text as shown below.
  A dataset may have any number of numerical input factors, but the last output column must always be the number of confirmed COVID-19 deaths in the respective geographic area.<br/>
  This is becasue the training algorithm finds the impact correlation of each feature on the resulting deathcount of an area, being able to predict risk of new geographic areas.
</p> 

<table class="tg">
<thead>
  <tr>
    <th class="tg-0pky">#</th>
    <th class="tg-0pky">#</th>
    <th class="tg-0pky">#</th>
    <th class="tg-0pky">#</th>
    <th class="tg-0lax">x...</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky">#</td>
    <td class="tg-0pky">#</td>
    <td class="tg-0pky">#</td>
    <td class="tg-0pky">#</td>
    <td class="tg-0lax">y...</td>
  </tr>
  <tr>
    <td class="tg-0pky">#</td>
    <td class="tg-0pky">#</td>
    <td class="tg-0pky">#</td>
    <td class="tg-0pky">#</td>
    <td class="tg-0lax">z...</td>
  </tr>
</tbody>
</table>

<p>Datasets used for training, testing, and diagnosis throughout the course of this project can be found <a href="https://github.com/hershyz/CRNN/tree/main/datasets">here</a>.</p>

<br/>

<h3>Project Documents:</h3>
<ul>
  <li><a href="https://github.com/sam-shridhar1950f/konnect-cs/blob/master/Paper/Kinect Analysis of Obstacles & Feedback for the Visually-Impaired.pdf">Short Paper</a></li>
  <li><a href="https://github.com/sam-shridhar1950f/konnect-cs/blob/master/Documentation/Slideshow.pdf">Final Slideshow</a></li>
</ul>
