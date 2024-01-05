# Scriptacide: PCAPdroid Userscript for Easy Script Execution

Scriptacide leverages PCAPdroid to execute scripts and use developer tools conveniently on mobile devices. Unlike traditional methods such as injecting scripts via JavaScript URLs or the JavaScript console, Scriptacide injects at the HTTP request level, allowing for the bypassing of restrictions on requests to external URLs. This unique approach enables the execution of custom scripts on sites like Discord and Google (Note: Be cautious as this may violate terms of service). Scriptacide also includes the hardcoded Eruda Console, facilitating the use of developer tools on mobile platforms.

## Setting up Scriptacide

1. Download the [PCAPdroid app](https://play.google.com/store/apps/details?id=com.emanuelef.remote_capture) from your preferred app store.
2. Open the app and skip the tutorial.
3. Navigate to the in-app settings.
4. Choose "TLS Decryption."
5. Follow the steps displayed on the screen.
6. Go back to the settings.
7. Enable "Block QUIC."
8. Return to the main page of the app.
9. Select the three lines in the top left of the screen.
10. Choose "Decryption Rules."
11. Click "+," then select "App."
12. Search for your preferred browser and select it.
13. Open "PCAPdroid MITM" from the TLS decryption setup process.
14. Choose "Js Injector."
15. Click "+."
16. Paste the following link for the userscript:
   ```
   https://raw.githubusercontent.com/V-0-I-D-JS/Scriptacide/main/src/scriptacide.js
   ```
17. Select "Add."
18. Return to PCAPdroid.
19. Click "Ready."
20. Open your chosen browser.
21. Navigate to a website of your choosing(Note: Not all websites are supported.)
22. Profit
