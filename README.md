# Advanced Android Login App

This project extends a basic login application with full navigation flows and multiple activities.

## Features Implemented
1. **Authentication:**
   - Hard-coded validation (Username: `admin`, Password: `1234`).
   - Secure password input fields.

2. **New Screens:**
   - **Register Page:** Interface for new user sign-up.
   - **Forgot Password:** Flow to initiate password recovery.
   - **Reset Password:** Interface to set a new password.
   - **Landing Page:** A dashboard shown only after successful login.

3. **Navigation Logic:**
   - Used `Intents` to link all activities.
   - Implemented `finish()` on the Login screen to prevent back-navigation after a successful login.
   - Added clickable TextViews for Registration and Password recovery.

## How to Run
1. Clone the repository.
2. Open in Android Studio.
3. Run on an Emulator (Pixel API 34 recommended).
4. Enter `admin` / `1234` to see the Landing Page.
