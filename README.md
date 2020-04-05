# AlphabetSoup
<br>How many neurons and layers did you select for your neural network model? 
<br>I started with two layers with Layer 1 = 100, Layer 2 = 10 neurons
<br>I have tried multiple combinations of neurons and layers.results below.
<br>Were you able to achieve target model performance? 
<br>No. My Accuracy came out as 0.73 with Loss of 0.53
<br>
<br>What steps did you take to try and increase model performance? 
<br>So I tried multiple combinations of layers, neurons and epocs
<br>
<br>1.	Layer 1 = 100, Layer 2 = 10, epochs = 100
<br>Loss: 0.5692654501661962, Accuracy: 0.7292128205299377
<br>2.	Layer 1 = 80, Layer 2 = 30, epochs = 75
<br>Loss: 0.5601488410314388, Accuracy: 0.7257142663002014
<br>3.	Layer 1 = 100, epochs = 500
<br>Loss: 0.5702820965708518, Accuracy: 0.7295626997947693
<br>
<br>If you were to implement a different model to solve this classification problem, which would you choose and why?
	<br>I can see many input values here have negative values, So I will try to use and alternative model of LeakyReLU whereby negative input values will be considered in the return values.
