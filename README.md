# make-money-machine-web

![Screenshot 2025-02-12 at 12-21-34 Money Making Website](https://github.com/user-attachments/assets/aa92f2a7-0cd8-447f-ac20-04ac0e8b379d)

## Overview

This is a fun, interactive web application that simulates earning money online. It's designed to be engaging and easy to use, featuring a dynamic canvas background, a progress bar, editable earnings per hour, and background music.  It serves as a simple, entertaining simulation and doesn't involve actual financial transactions.

## Features

*   **Dynamic Earnings:** Watch your simulated earnings grow in real-time.
*   **Editable Earnings Per Hour:** Customize your earning rate to simulate different income streams.
*   **Progress Bar:** Visually track your progress toward your hourly earning goal.
*   **Interactive Canvas Background:** Enjoy a visually appealing and dynamic background using the HTML5 Canvas API.
*   **Background Music:** Get in the mood with optional background music that can be toggled on/off.
*   **Reset Functionality:** Start fresh with a single click.
*   **Enable Autoplay Instructions:** Clear instructions on how to enable autoplay for background music.

## How to Use

1.  **Start Earning:** Click the "Start Making Money!" button to begin the simulation.
2.  **Adjust Earnings Per Hour:** Enter a new value in the "Earnings Per Hour" input field to change your earning rate.
3.  **Toggle Music:** Click the "🎵 Music: On/Off" button to control the background music.
4.  **Reset:** Click the "🔄 Reset" button to reset your earnings, progress, and multiplier.
5.  **Enable Autoplay:** If the music doesn't start automatically, click anywhere on the page to enable autoplay in your browser.

## Technologies Used

*   **HTML:** Provides the structure of the web page.
*   **CSS:** Styles the web page for a visually appealing user interface.
*   **JavaScript:** Implements the dynamic functionality, including earnings calculation, progress bar updates, music control, and canvas animations.
*   **HTML5 Canvas API:** Used to create the dynamic background.
*   **Audio API:** Used for background music and sound effects.

## Setup and Installation

1.  **Clone the Repository (Optional):** If you're using version control, clone the repository to your local machine:

    ```bash
    git clone https://github.com/blockode-co/make-money-machine-web.git
    ```

2.  **Create Files:** Create the following files in a directory:

    *   `index.html` (the main HTML file)
    *   `styles.css` (the CSS stylesheet)

3.  **Copy Code:** Copy the HTML, CSS, and JavaScript code from the provided files into the corresponding files you created.

4.  **Audio Files:** Replace the placeholder URLs for `clickSound`, `moneySound`, and `backgroundMusic` in the JavaScript code with the actual URLs or paths to your audio files.  You can use free sound effect and music resources online (e.g., Mixkit, FreeSound).

5.  **Open in Browser:** Open the `index.html` file in your web browser.

## Configuration

*   **Audio Files:** Ensure the audio files are accessible and the URLs in the JavaScript code are correct.
*   **Earnings Per Hour:** The default earnings per hour is set to $100. You can change this value directly in the HTML or via the input field in the web application.
*   **Music Autoplay:** Be aware that some browsers may block autoplay. Provide instructions to the user to enable autoplay if needed.

## Known Issues

*   **Autoplay Blocking:** Some browsers block automatic audio playback. Users may need to interact with the page to enable audio.  The application provides a hint to users if autoplay is blocked.
*   **Performance:**  The canvas animations might impact performance on older or less powerful devices.

## Future Enhancements

*   **More Complex Earning Mechanics:** Implement more sophisticated earning models (e.g., investments, passive income).
*   **Visual Upgrades:** Add more advanced canvas animations and visual effects.
*   **User Profiles:** Implement user profiles with saved earnings and settings.
*   **Mobile Responsiveness:**  Ensure the website is fully responsive and works well on mobile devices.
*   **Sound Effects Customization:** Allow users to choose different sound effects.

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to submit a pull request.

## License

This project is open-source and available under the MIT License.  See the `LICENSE` file for more information.
