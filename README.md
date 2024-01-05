# Scriptacide
## A PCAPdroid userscript for running scripts easily

Scriptacide uses PCAPdroid to execute scripts and use developer tools easily on mobile. Instead of injecting using regular methods such as JavaScript urls or the JavaScript console, Scriptacide injects at the http request level. This allows for bypassing restrictions on requests to external urls. Because of this, you can run custom scripts on sites like discord and google (Do not do this. This breaks TOS.) Scriptacide also comes with Console eruda hardcoded so you can use developer tools on mobile.

## Setting up Scriptacide
1. Download the [PCAPdroid app](https://play.google.com/store/apps/details?id=com.emanuelef.remote_capture) from your appstore of choice
2. Open the app and skip the tutorial
3. Open the in app settings.
4. Select "TLS decryption"
5. Follow the steps shown on screen
6. Go back to the settings
7. Enable "Block QUIC"
8. Go back to the main page of the app
9. Select the three lines in the top left of the screen
10. Select "Decryption rules"
11. Click "+", then app
12. Search for your browser of choice and select it
13. Now open the "PCAPdroid mitm" from the TLS decryption setup process.
14. Select "Js injector"
15. Click "+"
16. paste in the following permalink for the userscript:
