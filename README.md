# GST E-Billing App

Android GST E-Billing Project is a GST billing solution. The system enables you to **add products and items**, create **customers** and **users**, and generate as many **invoices**, **receipts**, and **quotes** as you want. The system provides some other **awesome features** which include instant **invoice calculations** for **items**, **quantity**, **Taxes** / **VAT** and **total** without any extra effort. I built this app in Android Studio using **SQLite database** and **Java**.

## Features
* Easy Layout
* Generate Invoices and receipts PDF Support
* Unique bill numbers
* Functionality to create invoice items each time or choose from database
* Functionality to choose TAX
* Generate downloadable PDF files
* And lot more...

## Technology, Tools, and Plugins Used
* Android Studio
* Java
* Windows 10

## Steps to Run the App on a Mobile Device

### Prerequisites
1. **Android Studio** installed on your computer.
2. **USB Debugging** enabled on your Android device.
3. **Android Device** with a minimum Android version that supports your app.

### Steps

1. **Clone the Repository**
    ```sh
    git clone https://github.com/umarfarookrizwan/Billing-App.git
    cd Billing-App
    ```

2. **Open the Project in Android Studio**
    - Launch Android Studio.
    - Click on `Open an existing Android Studio project`.
    - Navigate to the cloned repository and select it.

3. **Build the Project**
    - Once the project is loaded, click on `Build` in the top menu.
    - Select `Make Project` to ensure everything is set up correctly and there are no build errors.

4. **Connect Your Android Device**
    - Connect your Android device to your computer via USB.
    - Ensure USB Debugging is enabled on your device. You can enable it by going to `Settings > About phone > Tap on "Build number" seven times to enable Developer options > Developer options > USB Debugging`.

5. **Run the App**
    - In Android Studio, click on the `Run` button (green play button) or press `Shift + F10`.
    - Select your connected device from the list of available devices.
    - Click `OK` to start the installation process.

6. **Install the App via APK (Alternative Method)**
    - If you prefer to install the APK file directly, you can build the APK by navigating to `Build > Build Bundle(s) / APK(s) > Build APK(s)`.
    - Once the build is complete, locate the APK file in the `app/build/outputs/apk/debug` directory.
    - Transfer the APK file to your Android device and open it to install the app.

### Troubleshooting
- **Build Errors**: Ensure all dependencies are installed and up to date.
- **Device Not Recognized**: Make sure USB Debugging is enabled and the appropriate drivers are installed on your computer.
- **App Crashes**: Check the Logcat in Android Studio for error messages and debug accordingly.

By following these steps, you should be able to successfully run the GST E-Billing App on your mobile device. If you encounter any issues, feel free to open an issue on this repository. Happy billing!
