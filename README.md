# ML_eye_disease_classifier_ios_app
Utilized Neural Network and ion's ML architecture to create an app that classifier a healthy eye with the diseased eye in real-time.

# Methodology
1. Collection and augmentation of data
2. Creation of Neural Network trained on the 1400 augmented data images
3. Conversion of Neural Network to the format accepted by apple platform
4. Designing of the app using Apple Xcode's UIkit framework
5. Deploying the converted keras model on the iphone app using CoreML kit, built in Xcode.
6. Working Prototype

## 1. Collection and augmentation of dataset
Custom dataset with 100 "normal" and "cataract" eye images and fetched 1400 images of the same dataset by applying augmentation techniques using "Augmentor" python library<img width="865" alt="Screen Shot 2022-08-21 at 9 56 28 PM" src="https://user-images.githubusercontent.com/42109704/185823924-156dfe03-ca3d-4e79-a391-43643d5464fb.png">

## 2. Creation of NN trained on the image data<img width="890" alt="Screen Shot 2022-08-21 at 10 02 00 PM" src="https://user-images.githubusercontent.com/42109704/185824404-be1814e5-417c-48bf-a448-bd53a7c889d7.png">

## 3. Converting NN to apple format using "coremltools"![WhatsApp Image 2022-08-18 at 10 50 50 PM](https://user-images.githubusercontent.com/42109704/185824469-0e3628f3-65fe-494d-96f1-659220a22b6c.jpeg)

## 4. User Interface design![Simulator Screen Shot - iPhone 13 mini - 2022-08-18 at 22 54 26](https://user-images.githubusercontent.com/42109704/185824546-1d63ebdb-cc09-480b-9d8a-c11cc5cd5d5c.png)![Simulator Screen Shot - iPhone 13 mini - 2022-08-18 at 22 59 18](https://user-images.githubusercontent.com/42109704/185824624-1709cc2b-9449-43fe-a8c8-b2831e02738f.png)
![Uploading Simulator Screen Shot - iPhone 13 mini - 2022-08-18 at 22.59.18.png…]()

## 5. Deployment<img width="1440" alt="Screen Shot 2022-08-21 at 10 07 47 PM" src="https://user-images.githubusercontent.com/42109704/185824892-78c39154-f180-47a0-9507-d90781fe3511.png">





