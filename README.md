
# 🏠 Smart Home Safety & Comfort System – Android Application

A mobile app developed in **Android Studio** that integrates with a fingerprint-based Arduino locking mechanism. The system provides both **security** and **convenience** for household access management, offering real-time notifications and multiple ways to unlock the door.

## 📱 Features

- 🔒 **Fingerprint-based door unlocking**  
  High-resolution biometric fingerprint recognition for secure access.

- 🟢 **Unlock via in-app button**  
  Remotely unlock the door by pressing a button within the mobile app.

- 🏠 **Indoor button unlocking**  
  A manual button to open the door from inside the house.

- 📡 **Bluetooth connection to circuit**  
  Connect the app to the Arduino lock system via Bluetooth.

- 📊 **Access history logging**  
  Every unlock event is saved to a database with timestamp, user info, and door ID.

## 🚀 Installation & Setup

To install and run the application:

1. **Install Android Studio**  
   Download it from [developer.android.com](https://developer.android.com/studio)

2. **Clone the repository**:
   ```bash
   git clone https://gitlab.upt.ro/dalia.gogoase/licenta_gogoase_dalia.git
   ```

3. **Open the project** in Android Studio:  
   Go to `File > Open` and select the project directory.

4. **Build the project**:
   - Click the **Build** button in Android Studio  
   - Or run `./gradlew build` from the terminal

5. **Run the app**:
   - Connect a physical device via USB  
   - Or start an emulator  
   - Then click **Run** in Android Studio or run `./gradlew installDebug`

## 🚫 Contributions

This project is currently not open to external contributions.

## 👩‍💻 Author

**Dalia Gogoase**  
Smart Home & Embedded Systems Enthusiast
