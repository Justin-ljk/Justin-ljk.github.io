<h1>Heading  1</h1>
<h2>1. Introduction</h2>
<h3>1.1 background</h3>
<p>Nowadays, as internet became widespread among people, fashion is changing almost every second. 
Under this situation, many teenagers, especially girls, are entangled in the problem of what to wear daily considering weather and their mood.</p>
<h3>1.2 current approach</h3>
<p>Along side of the development of internet, online shopping had became more well-rounded, 
including intelligent cloth recommendation. There are already many programs reccomending clothes for buyers, but none of them can help to determine what to wear under given circumstances. Temporarily, there are no similar products in the market yet.</p>
<h3>1.3 objective </h3>
<p>The purpose of this product is to recommend clothing options to user via virtual assistant. By comparing with big data, it will be able to tell different styles of clothing, and provide valuable suggestions according to local weather, users' mood, and their plans for the day. It is also expected that it can interact with other intelligent furnitures such as closets to provide information about where to find the recommended clothes. The clothing data is mianly collected from social medias, tracking messages and photos posted by stars that the user follow and the user's purchase history.
<h2>2. methodology</h2>

![](https://github.com/Justin-ljk/Justin-ljk.github.io/blob/main/draw.png)
<p>The program starts by asking the user what style of clothes through python input function. The answer to these questions are typed in by the user and it will be recorded. Then the program recommend clothes that corresponds to the tags given by the user. The program will also record what clothes are already owned by the user thorugh python lists function and later transfer them into csv files. The clothes recorded will be more favored in the process of recommendation. With respect to the expected weather and popular trend, recommendation will be made. If the user gives a negative feedback, then the product will re-recommend by asking the user more details about the clothing wanted. The tags marked as “dislike” will be avoided in similar situations in the future.<p>
  
<p>First, the program imports the csv file used to store information about clothes and the 10 clothes pictures being tested. Then the pictures of the clothes are read and resized into a 800*800 square to later fit the recommendation page. Using 'input' function, we acquire necessary information including the style of the cloth and where it will be put from the user. The program will atomatically check if the storgae space is available for the cloth, if yes, an overview of the closets will be showed in the recommendation page and where the cloth is stored will be highlighted.

<h3>2.1 machine learning</h3>
<h4>2.1.1 data</h4>
<h5>format</h5>
<p>the pictures provided in the dataset are in "ubyte" format, so it requires a program to interpret them and turn them into visually pictures of all kinds of clothes
<h5>tags</h5>
<p>the tags of different clothes are also included in the dataset, these tags are written in codes, so it requires a program to "translate" it into everyday language that we speak like. For example, the word "ankle boots" corresponds to code...

![](https://github.com/Justin-ljk/Justin-ljk.github.io/blob/main/L001.jpg)
![](https://github.com/Justin-ljk/Justin-ljk.github.io/blob/main/L002.jpg)
![](https://github.com/Justin-ljk/Justin-ljk.github.io/blob/main/L003.jpg)
![](https://github.com/Justin-ljk/Justin-ljk.github.io/blob/main/L004.png)
![](https://github.com/Justin-ljk/Justin-ljk.github.io/blob/main/L005.png)
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
<p>every time after training, the program will count the number of errors made during training and the artificial intelligence will refine itself according to the optimizer
<h5>testing and training</h5>
<p>call train and test functions
<p>predict outputs and show pictures

  
![](https://github.com/Justin-ljk/Justin-ljk.github.io/blob/main/18DB15C8-5E94-4c07-943A-A5E8C41AABF1.png)

<h3>2.2 hardware</h3>
<p>The building fo the hardware of many parts, the most important part is the virtual assistant. The virtual assistant is responsible for the interaction from acquiring specific information to the end of the whole process of recommending. There are also other parts including the microphone to analyse speaking and the computer used to collect data, ect.<p>
<p>(a picture of the built hardware)<p>
<h3>2.3 testing</h3>

<h2>3. Results and Discussion</h2>
<h3>3.1 Results</h3>
<h4>3.1.1 Data Collection</h4>
<p>Through the web crawler, the product will be able to collect (this much) data from (social medias), it can also (whatever function).
<h4>3.1.1 Data analysis</h4>
<p>Using the AI we previously trained, the data collected from the social media will be analysised and sorted into many categories. (actual results) (errors?)
<h4>3.1.1 Recommendation</h4>
<p>During the process of recommendation, the clothing that user already has or from a social media that the user follows will be valued higher than others. (actual results)
<h3>3.2 Comparsion with Expectation</h3>
<p>One thing I have expected but can't be realized yet is the automatic recording of the location of the clothes. This process involves detecing the taking out and putting in of every single cloth. I've done basic programming of this function, which includes the recording clothes input and searching for specific clothes. However,  I hadn't find the right hardware and match it with my programs yet.

<h2>4. Conclusion</h2>
<h3>4.1 Does it reach my ultimate purpose?</h3>
<p>I would ay that this project effectively achieved/didn't achiheve my ultimate purpose. It......through/because...... Compared with my purpose, 
<h3>4.2 Future Possibilities</h3>
<p>Though I'm satisfied with my current product, I believe much future improvements can be made. ......
