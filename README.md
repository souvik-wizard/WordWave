# WhatsApp Web Translation Chrome Extension
This Chrome extension adds a Translate button to WhatsApp Web, enabling users to translate incoming and outgoing messages directly within the chat interface. Users can also translate the input message before sending it, making it easy to communicate across language barriers.

## Features
- Message Translation: Hover over any message to reveal a Translate button. Clicking it translates that message's text to the preferred language.
- Input Field Translation: Translate any message in the input field and send it in the chosen language.
- Multiple Language Support: Set your preferred language from the dropdown, which will be used for all translations. (You can change further it if you want)
## Demo
Include a GIF or screenshot of the extension in action.

## Installation
- Clone the repository:

```bash
git clone https://github.com/souvik-wizard/MessageTranslator-Chrome_Extension.git
```
- Add your API key
  - First, go to [Rapid Api](https://rapidapi.com/) and create a account.
  - Then go to [Microsoft API](https://rapidapi.com/apiship-apiship-default/api/microsoft-translator-text-api3/), select Basic plan, click Start Free Plan and then hit Subscribe.
  - You will be redirected to the API dashboard where you find the 'X-RapidAPI-Key'.
  - Copy the key and paste your API key into the files mentioned below.
  - ```bash
    /background/background.js
    /popup/popup.js
    
    const apiKey = "ENTER YOUR API KEY HERE";
    ```
  
- Navigate to the Extensions page in Chrome by typing chrome://extensions in the address bar.

- Enable Developer Mode by toggling the switch in the upper right corner.

- Click on 'Load unpacked' and select the folder where you cloned this repository.

- The extension should now appear in your list of extensions.

- Click on it and pin it for faster access. (Optional)

  ## Usage

- Open the extension by clicking on it and then click on 'Get Started' button and you will be directly redirected [WhatsApp Web](https://web.whatsapp.com/) or manually open [WhatsApp Web](https://web.whatsapp.com/) and log in with your account.
- After getting redirected to [WhatsApp Web](https://web.whatsapp.com/) click on the extension and select your preferred language from the dropdown and hit save.
- Now open any chat.
- Hover over any incoming or outgoing message. A Translate button will appear below the message.
- Click the Translate button to translate that specific message to the preferred language.
- To translate the message in the input field before sending it, type a message you want to translate and then click the Translate button that appears in the right corner of the input field.

## Contributing
I welcome contributions! Fork the Repository if you'd like to contribute. :)
