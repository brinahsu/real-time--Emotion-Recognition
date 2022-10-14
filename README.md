# Real-time Emotion Recognition
人類以臉部表情表達情緒，假如電腦可以根據人類的表情變化來偵測使用者心情，可提供更人性化的服務，我們使用多種深度學習框架對情緒資料集(FER 2013)進行訓練，最後得到準確率最高的是mini-Xception模型，準確率是60%，我們認為準確率很難提高的原因是因為情緒不容易判斷，例如生氣和傷心的表情。  
期望未來能與AR作結合，能針對不同的心情即時產生不同的AR濾鏡

## Dataset
Kaggel facial expression recognition (FER) challenge 2013  
<img align="right" src="https://ppt.cc/fFLzBx@.png">
<ul>  
<li>Image size： 48 x 48 pixels</li><br/>
<img align="right" src="https://ppt.cc/fReVyx@.png">
<li>Image number：34034（grayscale)</li><br/>
<li>Emotion labels：0: 'Angry',<br/>
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1: 'Disgust'<br/>   
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2: 'Fear'<br/>  
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3: 'Happy'<br/>
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4: 'Sad'<br/>
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5: 'Surprise'<br/>  
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6: 'Neutral'</li><br/>
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
![](https://ppt.cc/fC22Jx@.png)

## Results
![](https://ppt.cc/fuKAFx@.png)

