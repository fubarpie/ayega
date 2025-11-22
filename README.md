# Ayega

Ayega is under early development and is not functioning yet. 

Ayega is an open-source Android application that gives you control over your device's wake word. It allows you to choose a custom wake word to activate your preferred voice assistant. This project is built using the [openWakeWord](https://github.com/dscripka/openWakeWord) framework.

## 🚀 Features

* **Custom Wake Words:** Replace "Hey Google" or "Alexa" with a phrase of your choosing.
* **Assistant Integration:** Launch Google Assistant, Amazon Alexa, or Samsung Bixby.
* **Always-On Detection:** Runs as a background service to listen for your wake word.
* **User-Controlled Sensitivity:** Adjust the detection threshold to balance between false activations and missed detections.

## ⚠️ Licensing Status

This project aims to be a fully open-source application under a permissive license (Apache 2.0). However, the initial version uses pre-trained models from the openWakeWord project that are licensed under **CC BY-NC-SA 4.0**. The "NC" (NonCommercial) clause means that if you build and distribute the app with these models, it cannot be for commercial purposes.

Our roadmap includes training and providing new, permissively licensed models to remove this restriction.

## 🛠️ Build & Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/fubarpie/ayega.git](https://github.com/fubarpie/ayega.git)
    ```
2.  **Open in Android Studio:** Open the cloned directory in the latest version of Android Studio.
3.  **Build the APK:** From the menu, select `Build` > `Build Bundle(s) / APK(s)` > `Build APK(s)`.
4.  **Install the APK:** Once the build is complete, you can find the APK in the `app/build/outputs/apk/debug/` directory. Install this file on your Android device.

##  Usage

1.  Upon first launch, you will be asked to grant the "Record Audio" permission. This is necessary for the app to listen for the wake word.
2.  Use the main toggle switch to start or stop the wake word detection service.
3.  Select your desired wake word and the voice assistant you want to launch from the dropdown menus.
4.  Adjust the "Sensitivity" slider to fine-tune the detection accuracy for your environment.

## 🤝 Contributing

We welcome contributions! Please see the [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines on how to get involved.
