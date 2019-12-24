# Object Detection App For visually Impaired Users

## Descriptions
This app made for visually impaired users. I believe that this app is going to make make the life of blind and visually impired users easier. App is quite intuitive and very easy to use. It detects object in a image taken by a user and gives output as audio message, ex: *"This is a wallet"*

## Implementation
For the implementation of this app Camera 2.0 API, TextToSpeech API and Pretrained [Inception model](https://www.tensorflow.org/lite/guide/hosted_models) are used. First image is taken, then it's center is cropped as square and resolution changed to 299x299 pixels. After that image inputted to to Inception model. Lastly, according to result audio message is otputted.  

## Demo
[Demo Video](https://drive.google.com/file/d/1mW_cRn1LAl3-fmC7-QXfq5b9QtnbPxtF/view?usp=sharing)
![](assets/demo.gif)
