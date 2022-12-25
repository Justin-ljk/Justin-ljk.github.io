<h1>Heading  1</h1>
<h2>1. Introduction</h2>
<h3>1.1 background</h3>
<p>Nowadays, as internet became widespread among people, fashion is changing almost every second. 
Many teenagers, especially girls, have many pieces of clothes, each with their own features.  These clothes each fit different weather and mood, making them hard to choose from. Teens are especially known as active internet users and they are more likely to follow clothing trends popular on social media. Keeping up with fashiona and wearing similar clothes as peers can increase their sense of belonging within their community. It became a problem that people are entangled in the problem of what to wear according to these preconditions.</p>
<h3>1.2 current approach</h3>
<p>Along side of the development of internet, online shopping had became more well-rounded, including intelligent cloth recommendation. There are already many programs reccomending clothes for buyers, in online stores like Amazon and Taobao, buyers will be recommended similar clothes when they decide to purchase one. However, none of these programs can help users to determine what to wear under given circumstances. Temporarily, there are no similar products in the market yet.</p>
<h3>1.3 objective </h3>
<p> Ideally, BDBVACR will be composed of both hardweare and softwear. The hardware will be connected to personal computers and able to interact with intelligent houseware. The purpose of this product is to recommend clothing options to user via virtual assistant. By comparing with big data, it will be able to identify different styles of clothing from social media, and provide valuable suggestions according to local weather, users' mood, and their plans for the day. Also, it will be able to track the user's social media viewing history, following the clothing trend of stars and internet celebrities that the user subscribes.It is expected that it can interact with other intelligent furnitures such as closets to provide information about where to find the recommended clothes. 
<h2>2. methodology</h2>

![](https://github.com/Justin-ljk/Justin-ljk.github.io/blob/main/methodology.png)
<p>The program starts by inquiring the user about what style of clothes through python input function. The answer to these questions are typed in by the user and it will be recorded. Then the program recommend clothes that corresponds to the tags given by the user. The program will also record what clothes are already owned by the user thorugh python lists function and later transfer them into csv files. The clothes recorded will be more favored in the process of recommendation. With respect to the expected weather and popular trend, recommendation will be made. If the user gives a negative feedback, then the product will re-recommend by asking the user more details about the clothing wanted. The tags marked as “dislike” will be avoided in similar situations in the future.<p>
  
<p>First, the program imports the csv file used to store information about clothes and the 10 clothes pictures being tested. Then the pictures of the clothes are read and resized into a 800*800 pixel square to later fit the recommendation page. Using 'input' function, we acquire necessary information including the style of the cloth and where it will be put from the user. The program will atomatically check if the storgae space is available for the cloth, if yes, an overview of the closets will be showed in the recommendation page and where the cloth is stored will be highlighted. Later, if the user acquires a piece of clothes, then the style and mood of it will be typed in via the input function. If it corresponds to one or maybe several pieces of clothes, the name and location of the clothes will be printed out and their pictures will be shown in the recommendation page.

<h3>2.1 fashion MNIST</h3>
<h4>2.1.1 data</h4>

<p>Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. Zalando intends Fashion-MNIST to serve as a direct drop-in replacement for the original MNIST dataset for benchmarking machine learning algorithms. It shares the same image size and structure of training and testing splits.<p>
<h5>format</h5>
<p>Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255. The training and test data sets have 785 columns. The first column consists of the class labels (see above), and represents the article of clothing. The rest of the columns contain the pixel-values of the associated image. The pictures provided in the datasets are in "ubyte" format, so it requires a program to interpret them and turn them into visually pictures of clothes which can be distinguished and compared by the AI.
<h5>labels</h5>
<p>The labels of different clothes are also included in the dataset, these labels are written in codes, so it requires a program to "translate" them into everyday language that we speak.<p>
<p>Each training and test example is assigned to one of the following labels:

0: T-shirt/top,
1: Trouser,
2: Pullover,
3: Dress,
4: Coat,
5: Sandal,
6: Shirt,
7: Sneaker,
8: Bag,
9: Ankle boot.<p>

<h4>2.1.2 Show contents and labels</h4>
<p>The 4th to 7th byte of the training dataset is the number of labels. Every byte after that is a label ranging from 1 to 9. After reading the contents of the dataset, all the pictures of the clothes in the dataset can be shown using function openCV. The pictures are displayed along with the translated labels and the serial numbers<p>
<p>The reaults are as follows.<p>
 
![](https://github.com/Justin-ljk/Justin-ljk.github.io/blob/main/open%20picture.png)
![](https://github.com/Justin-ljk/Justin-ljk.github.io/blob/main/programming%20drawio.png)

<h3>2.2 AI training</h3>
<h4>2.2.1 AI engine prediction</h4>
<p>Import libraries and load the data downloaded
<h4>2.2.2 CNN network</h4>
<h5>define optimizer, training and testing methods</h5>
<p>every time after training, the program will count the number of errors made during training and the artificial intelligence will refine itself according to the optimizer
<h4>2.2.3testing and training</h4>
<p>call train and test functions
<p>predict outputs and show pictures


<h3>2.3 Recommendation engine</h3>

![](https://github.com/Justin-ljk/Justin-ljk.github.io/blob/main/%E6%97%A0%E6%A0%87%E9%A2%98.png)
![](https://github.com/Justin-ljk/Justin-ljk.github.io/blob/main/18DB15C8-5E94-4c07-943A-A5E8C41AABF1.png)


<h3>2.4 Software</h3>
<h4>2.4.1 UI</h4>
<p> cloth style&location input<p>

<h4>2.4.2 Cloth database</h4>

<h3>2.5 hardware</h3>
<p>The building fo the hardware of many parts, the most important part is the virtual assistant. The virtual assistant is responsible for the interaction from acquiring specific information to the end of the whole process of recommending. There are also other parts including the microphone to analyse speaking and the computer used to collect data, ect.<p>
<p>(a picture of the built hardware)<p>


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
