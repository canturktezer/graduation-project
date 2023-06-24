Translation and Interpretation System

The Translation and Interpretation System is a project aimed at providing instant speech-to-speech and speech-to-text translation to users. The system allows for seamless communication across different languages

Features

The Translation and Interpretation System offers the following features:

Text-to-text translaiton: Users have the ability to input text in their preferred language, and the system will translate their messages to the desired language of other users.

Speech-to-text translation: Users can speak in one language, and the system will transcribe their speech into text, making it easier to communicate across language barriers.

Support for multiple languages: The system initially supports five languages but has expanded to include a total of 15 languages.

Integration with Google Cloud: The project utilizes Google Cloud's translation API technology, which offers advanced neural machine translation for accurate and efficient translations.

Technologies Used

The Translation and Interpretation System incorporates the following technologies:

JavaScript: The back-end of the system is developed using JavaScript.

Google Cloud: The project heavily relies on Google Cloud's translation API technology for seamless and accurate translations.

Note: There was translate folder in src file but i deleted it. To utilize the translation service, you will need to provide the necessary credentials. Please follow these steps:

1. Create a service account in the Google Cloud Console.
2. Generate a JSON key file for the service account.
3. Rename the JSON key file to 'google.json'.
4. Place the 'google.json' file in the 'src/translate' directory.

Please ensure that the 'google.json' file is kept secure and not included in the version control of this project. It contains sensitive credentials required for accessing the translation service.
