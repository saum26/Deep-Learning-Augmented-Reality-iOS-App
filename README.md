# Sculpture-Identification-Using-Deep-Learning-Models

By just aiming the camera at the statue, a mobile application may recognize it and play an embedded video on the screen in a matter of seconds. This software makes it simple to learn about the history of sculptures around the University of Dayton without exerting any additional effort.

For the Training dataset, accuracy of about 98 percent was reached, and for Testing it in real-time, accuracy of around 94 percent was achieved.

The dataset comprises over 6000 photos of 24 sculptures that were painstakingly gathered in varied lighting situations, at various times and angles in order for the model to perform accurately in extreme settings.

Transfer Learning is the foundation of the model. EfficientNet Lite v4 was utilized. It is precise and well-suited for use on mobile platforms. The model was trained and converted to a TFLite model, which was then utilized in the final version of the app.

The app was created using Unity 2019.4.32f1 and included the ML and Barracuda packages. The Unity project is transformed into an iOS/Xcode project for deployment on iOS systems after the UI and assets have been built.
