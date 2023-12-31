# Text-to-voice-convertor
![Screenshot 2023-12-31 192011](https://github.com/shuklatushar12219829/Text-to-voice-convertor/assets/115138208/1956072f-05f1-42f0-8aef-9e3e0f6f988d)

Link - https://timely-bavarois-eaf50d.netlify.app
 
Description
The HTML structure includes a textarea for input and a button to trigger text-to-speech conversion.
External styles and scripts are linked for styling and functionality.

The CSS file provides styles for layout and appearance, centering the content on the page.

The JavaScript file adds interactivity to the HTML document.
It waits for the DOM content to be fully loaded (DOMContentLoaded) before executing the script.
It gets references to the textarea and button elements.
When the button is clicked, it checks if there is text in the textarea. If yes, it calls the convertToSpeech function.
The convertToSpeech function creates a new instance of SpeechSynthesisUtterance, which represents a speech request.
The text parameter passed to SpeechSynthesisUtterance is the text to be converted to speech.
The speak method of speechSynthesis is then called with the created SpeechSynthesisUtterance to initiate the speech synthesis.
