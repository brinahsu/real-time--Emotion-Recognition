# Real-time Emotion Recognition
We implemented a python script that can detect human emotion in real time. Humans display emotions through facial expressions. If computers are able to detect users' emotion by their facial expressions, more customized features can be provided. We trained FER 2013 dataset with multiple deep learning models. In the end, mini-Xception had the highest accuracy of 60% compared to other models. The reason of why raising the accuracy for this model is difficult is due to the ambiguity of facial expressions, for example 'Angry' and 'Sad' faces can be similar.
We hope to integrate with AR in the future by displaying different AR filters according to the mood of the users.

## Dataset
Kaggel facial expression recognition (FER) challenge 2013  
<img align="right" src="https://ppt.cc/fFLzBx@.png">
<ul>  
<li>Image size： 48 x 48 pixels</li><br/>
<img align="right" src="https://ppt.cc/fReVyx@.png">
<li>Image number：34034（grayscale)</li><br/>
<li>Emotion labels：0: 'Angry',<br/>
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1: 'Disgust'<br/>   
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2: 'Fear'<br/>  
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3: 'Happy'<br/>
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4: 'Sad'<br/>
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5: 'Surprise'<br/>  
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6: 'Neutral'</li><br/>
<li>shortage of 'Disgust' data</li>
</ul>
<br/>
<br/>

## Training model--mini-Xception  
<img align="right" src="https://ppt.cc/f2y5Fx@.png">
<br/>

#### hyperparameters:
* optimizer:Adam  
* learning rate: reduce lr 
<br/>

#### training result:  
* Accuracy：0.6106  
* Loss：1.0382  
* Val_accuracy：0.6054  
* Val_loss：1.0599  

<br/>

## Flowchart
![](https://ppt.cc/fM4bEx@.png)

## Results
![](https://ppt.cc/fuKAFx@.png)

