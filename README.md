[![HitCount](http://hits.dwyl.com/hershyz/CRNN.svg)](http://hits.dwyl.com/hershyz/CRNN)

<img src="https://raw.githubusercontent.com/sam-shridhar1950f/konnect-cs/master/logo.png"/>
<p><i>Forecast COVID-19 risk in any geographical area using a predictive neural network.</i></p>



<p>
  The code in this repository was a software engineering project in the <a href="https://www.gcpsk12.org/gsmst">GSMST</a> engineering fair.<br/>
  Konnect is an intelligent, affordable assistive wearable made in the .NET framework.
</p>

<br/>

<h3>Prototype:</h3>
<img src="https://raw.githubusercontent.com/sam-shridhar1950f/konnect-cs/master/Documentation/model.PNG"/>

<h3>Predictions:</h3>
<img src="https://raw.githubusercontent.com/hershyz/CRNN/main/assets/testing.gif"/>

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
  <li><a href="https://github.com/hershyz/CRNN/blob/main/documents/Background%20Research%20Outline.pdf">Background Research Outline</a></li>
  <li><a href="https://github.com/hershyz/CRNN/blob/main/documents/Research%20Plan.pdf">Research Plan</a></li>
  <li><a href="https://github.com/hershyz/CRNN/blob/main/documents/CERA.pdf">CERA</a></li>
  <li><a href="https://github.com/hershyz/CRNN/blob/main/documents/slides.pdf">Final Slideshow</a></li>
</ul>
