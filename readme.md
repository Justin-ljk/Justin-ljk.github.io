<h1>Heading  1</h1>
<h2>1. Introduction</h2>
<h3>1.1 background</h3>
<p>Nowadays, as internet became widespread among people, fashion is changing almost every second. 
Under this situation, many teenagers, especially girls, are entangled in the problem of what to wear daily considering weather and their mood.</p>
<h3>1.2 current approach</h3>
<p>Along side of the development of internet, online shopping had became more weel-rounded, 
including intelligent cloth recommendation. There are already many programs reccomending clothes for buyers, but none of them can help to determine what to wear under given circumstances.</p>
<h3>1.3 objective </h3>
<p>The purpose of this product is to recommend clothing options to user through virtual assistant. By comparing with big data, it will be able to tell different styles of clothing, and provide valuable suggestions according to local weather, users' mood, and their plans for the day. The clothing data is mianly collected from social medias, tracking messages and photos posted by stars that the user follow. Temporarily, there are no similar products in the market yet.
<h2>2. methodology</h2>
![](https://github.com/Justin-ljk/Justin-ljk.github.io/blob/main/draw.png)
<h3>2.1 machine learning</h3>
<h4>2.1.1 data</h4>
<h5>format</h5>
<p>the pictures provided in the dataset are in "ubyte" format, so it requires a program to interpret them and turn them into visually pictures of all kinds of clothes
<h5>tags</h5>
<p>the tags of different clothes are also included in the dataset, these tags are written in numbers, so it requires a program to correspond it with the language that we speak like "ankle boots"
![](https://github.com/Justin-ljk/Justin-ljk.github.io/blob/main/L001.jpg)
![](https://github.com/Justin-ljk/Justin-ljk.github.io/blob/main/L002.jpg)
![](https://github.com/Justin-ljk/Justin-ljk.github.io/blob/main/L003.jpg)
![](https://github.com/Justin-ljk/Justin-ljk.github.io/blob/main/L004.jpg)
![](https://github.com/Justin-ljk/Justin-ljk.github.io/blob/main/L005.jpg)
![](https://github.com/Justin-ljk/Justin-ljk.github.io/blob/main/L006.jpg)
![](https://github.com/Justin-ljk/Justin-ljk.github.io/blob/main/L007.jpg)
![](https://github.com/Justin-ljk/Justin-ljk.github.io/blob/main/L008.jpg)
![](https://github.com/Justin-ljk/Justin-ljk.github.io/blob/main/L009.jpg)
![](https://github.com/Justin-ljk/Justin-ljk.github.io/blob/main/L010.jpg)
<p>the dataset consisted of two different subsets, training and testing, the function of them perfectly matched their names
<h4>2.1.2 artificial intelligence</h4>
<h5>developing</h5>
<p>Import libraries and load the data downloaded
<p>build network model
<h6>define optimizer, training and testing methods</h6>
<p>every time after training, the program will calculate the errors made during training and the artificial intelligence will refine itself according to the optimizer
<h5>testingand training</h5>
<p>call trian and test functions
<p>predict outputs and show pictures

