# Text Recognition Using Tesserocr
<H4> Installation Guide </h4>
1.Follow installation_guide.txt in repo<br>

<h4> Usage:</h4>
1.Only print the text from image
<h6>$ python3 main.py --image './images/5.png'</h6>

2.Print the each word from image with its confidence
<h6>$ python3 main.py --image './images/5.png' --confidence True</h6>

<h3>Outputs: </h3>
<p>
 1. OCR on straight image:<br>
 <img src="images/5.png", height="150", width="80"></img>&nbsp&nbsp&nbsp&nbsp
 <img src="images/op_5.png", height="150",width="80"></img><br>
 </p><br>
 
<p>
 2. OCR on Blur image:<br>
 <img src="images/3.jpeg", height="150", width="80"></img>&nbsp&nbsp&nbsp&nbsp
 Output:Image is Blur,unable to get OCR
 </p><br>
 
<p>
 3. OCR on rotated image:<br>
 <img src="images/1.jpg", height="150", width="80"></img>&nbsp&nbsp&nbsp&nbsp
 <img src="images/op_1.png", height="150",width="80"></img><br>
 </p><br>
 

 
 

