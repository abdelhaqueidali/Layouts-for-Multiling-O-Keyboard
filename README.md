# Custom Layouts for Multiling O Keyboard (MOK)

This repository provides DIY+ layouts for various languages, designed for use with the [Multiling O Keyboard (MOK)](https://play.google.com/store/apps/details?id=kl.ime.oh) on Android.  The primary focus is on providing comprehensive support for the **Amazigh (Berber)** language and its **Tifinagh** script, which often lacks robust keyboard options.  However, layouts for other languages are also included.

**[Download All Layouts and Resources](https://github.com/abdelhaqueidali/Layouts-for-Multiling-O-Keyboard/archive/refs/heads/main.zip)**

**Featured Image:**
![Tifinagh Keyboard Layout Example](https://github.com/abdelhaqueidali/Layouts-for-Multiling-O-Keyboard/blob/main/Layouts%20Images/%E2%B4%B7%E2%B5%94%E2%B5%8E%E2%B5%8D.jpg) </br>(This is a ⴷⵔⵎⵍ layout example.)

## Recommended Layouts

*   **Amazigh (Tifinagh):**  `ⴰⵣⴻⵔⵜⵢ (Azerty)`, `ⴰⵣⴻⵔⵜⵢ (Azerty-Full)`, and `ⴷⵔⵎⵍ` (DRML - a custom, efficient layout).
*   **Arabic:** `Arabic 1`
*   *More layouts are available in the repository.*

## Installation and Setup

### 1. Install Multiling O Keyboard

Make sure you have [Multiling O Keyboard (MOK)](https://play.google.com/store/apps/details?id=kl.ime.oh) installed and set up as your active keyboard on your Android device.

### 2. Add Languages in MOK

Within the MOK settings, add the languages you intend to use.  For example:

*   For Tifinagh script, add **"Tifinagh ⵜⵉⴼⵉⵏⴰⵖ"** (found under Languages/7. Others).
*   For Amazigh using Latin script, add **"Tamaziɣt"** (found under Languages/1. Latin).  It is also be available as "Berber" and "Taqbaylit."

### 3. Importing Individual Layouts (DIY+)

To import a single layout:

1.  **Copy the Layout Code:**  Find the layout you want in the repository (e.g., in a `.txt` file) and copy its entire code.
2.  **Open MOK:**  Bring up the Multiling O Keyboard.
3.  **Access Layout Settings:**  Long-press the spacebar and drag to "Layouts."
4.  **Paste and Apply:**  Tap "DIY+", then tap "Paste" to paste the copied layout code.  Click "Ok."
5.  **Select the Layout:**  The new layout should now be available in your MOK layout selection.

### 4. Importing All Layouts and Settings (Recommended)

For a quick setup, import all layouts and a pre-configured theme at once:

1.  **Copy Settings Code:**  Go to the `settings` folder in this repository and copy the entire contents of the settings file.
2.  **Open MOK Settings:**  Long-press the gear icon on the keyboard and drag to "Settings" (or open the MOK app directly).
3.  **Import Settings:**  Navigate to "Misc." -> "Import|Export".  Select "Settings," then tap "Paste" to paste the copied settings code.
4.  **Apply:**  Click "Ok."
5.  **Customize:**  All layouts and a green theme will be applied. You can now customize other settings (e.g., autocorrection, sound, vibration) to your preferences.

### 5.  Language-Specific Layouts (Important!)

For optimal performance and to avoid conflicts, it's crucial to use the correct layout with its corresponding language setting in MOK:

*   Use **Tifinagh script layouts** only with the **"Tifinagh ⵜⵉⴼⵉⵏⴰⵖ"** language in MOK.
*   Use **Latin script layouts** (for Amazigh) only with the **"Tamaziɣt"** (or "Berber"/"Taqbaylit") language.
*   Similarly, use Arabic layouts with the Arabic language setting, etc.

*Do not mix Latin script layouts with languages using non-Latin scripts, and vice versa.*  This prevents issues with character mapping and input prediction.

## User Dictionary (Amazigh - Tifinagh)

A user dictionary is provided to improve word prediction for Amazigh (Tifinagh).  You'll need the [User Dictionary Manager (UDM)](https://play.google.com/store/apps/details?id=com.usr.dict.mgr) app.

### Importing the Dictionary:

1.  **Install and Prepare UDM:**
    *   Install [User Dictionary Manager (UDM)](https://play.google.com/store/apps/details?id=com.usr.dict.mgr).
    *   Grant UDM storage permissions.
    *   Enable UDM in your Android's "Keyboard list and default" settings (this allows it to access the user dictionary; you *don't* need to set it as your default keyboard).

2.  **Download the Dictionary:** Download `Amazigh (Tifinagh) dictionary.txt` from the `User dictionary` folder in this repository.

3.  **Import into UDM:**
    *   Open UDM.
    *   Tap "Import."
    *   Choose "external - TXT file (one word per line) from location."
    *   Tap "Browse" and select the downloaded `Amazigh (Tifinagh) dictionary.txt` file.
    *   Set "Input file format" to "UDM (pipe separated)."
    *   Set "Import into language" to "Custom."
    *   In the "Custom" text box, enter `tf` (this is a language code for Tifinagh).
    *   Tap "NEXT."

4.  **Wait for Completion:**  The import process may take some time.  *Do not close UDM or allow your phone to kill it in the background.*  This ensures the import completes successfully.

5. **Enable Prediction in MOK:** Ensure "Word prediction" is enabled in your Multiling O Keyboard settings.

## Contributing

Contributions are welcome! If you have improvements to existing layouts, new layouts for other languages, or dictionary updates, please feel free to submit a pull request. Please follow these guidelines:

*   **Clear Naming:**  Name layout files descriptively (e.g., `Amazigh_Tifinagh_DRML.txt`).
*   **Documentation:**  Include a brief comment at the top of the layout file explaining its purpose and any special features.
*   **Language Codes:**  Use consistent language codes (e.g., `tf` for Tifinagh).
*   **Testing:**  Thoroughly test your layouts before submitting.

By following these instructions, you can enjoy a significantly improved typing experience for Amazigh and other languages using the Multiling O Keyboard.
