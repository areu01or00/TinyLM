# TinyLM - Run Powerful LLM Models on Your Android Device

### Overview

TinyLM is a modern Android application that lets you run powerful Large Language Models (LLMs) directly on your Android device - **no cloud required**. All processing happens on-device, ensuring your interactions remain private while delivering impressive AI capabilities.

## 📱 [Download TinyLM APK (Signed)](https://github.com/areu01or00/TinyLM/raw/tinylm-release/examples/llm_inference/android/apk-distribution/TinyLM-signed.apk)

### Features

- Run LLM models completely on your Android device
- Chat with AI assistants without internet connectivity
- Generate text, summaries, and creative content
- Process all data locally for enhanced privacy
- Modern, intuitive user interface

The app leverages the MediaPipe LLM Inference API to enable on-device AI tasks that would typically require cloud processing.

## Quick Installation

### Direct APK Download

Download and install TinyLM directly from this repository:
- 📥 **[Download TinyLM APK (Signed)](https://github.com/areu01or00/TinyLM/raw/tinylm-release/examples/llm_inference/android/apk-distribution/TinyLM-signed.apk)**

To install:
1. Download the APK file on your Android device
2. Open the APK file and allow installation from unknown sources if prompted
3. Follow the on-screen instructions to install

**Note**: This application must be run on a physical Android device to take advantage of the device GPU.

## How to Build the App

### 1. Download the Code

To download the code, clone the git repository using the following command:

```
git clone https://github.com/areu01or00/TinyLM.git
```

After downloading the code, you can import the project into Android Studio and run the app with the following instructions.

### 2. Prerequisites

*   The **[Android Studio](https://developer.android.com/studio)**
    IDE. This app has been tested on Android Studio Hedgehog.

*   A physical Android device with a minimum OS version of SDK 24 (Android 7.0 -
    Nougat) with developer mode enabled.

### 3. Build and Run

To import and build the app:

1. Download [Android Studio](https://developer.android.com/studio) and install.

2. From the Android Studio, select **File > New > Import Project**.

3. Navigate to the app `android` directory and select that directory, for example: `.../TinyLM/examples/llm_inference/android`

4. If Android Studio requests a Gradle Sync, choose **OK**.

5. Build the project by selecting **Build > Make Project**.

   When the build completes, the Android Studio displays a `BUILD SUCCESSFUL` message in the Build Output status panel.

To run the app:

1. Ensure that your Android device is connected to your computer and developer mode is enabled.

2. From Android Studio, run the app by selecting **Run > Run 'app'**.

## How to Use the App

### 1. Select Model

First select a model (e.g. `DEEPSEEK_CPU` for the DeepSeek model) from the model selection screen.

### 2. Download Model

If the model has not been downloaded previously, the app will download it from [LiteRT on Hugging Face](https://huggingface.co/litert-community).

If authentication and license acknowledgment are required to access the model, you will be prompted to sign in with your Hugging Face account and acknowledge the license if necessary.

### 3. Chat with Model

Once the model is downloaded, you can interact with it by entering prompts and receiving responses.

## Reference
For more details, see the [LLM Inference guide for Android](https://developers.google.com/mediapipe/solutions/genai/llm_inference/android).
