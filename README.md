![Logo](https://drive.google.com/uc?id=16kSn_U1snzH94P8y2_ZCDf2bxJaDLlhh)

# ChatGPT - Android App

ChatGPT Android App is a project developed for the "Code for Life: Hackathon for everyday solutions" organized by VIT University. This innovative app utilizes the power of the OpenAI GPT-3.5 model to provide natural language conversation capabilities. The app enables users to have interactive and dynamic conversations with an AI chatbot, offering a wide range of practical applications.


## Authors

- [@Oeyshik Das](https://github.com/Oeyshik/Django-CRM)

- [@Pratyaksh Saxena](https://github.com/pratyakshhhh)

- [@Shivam Singh](https://github.com/I-ShivamSingh)
## Tech Stack

Java 

Kotlin




## Features

- **Natural Language Conversations:** Engage in lifelike conversations with the AI chatbot powered by GPT-3.5.
- **User-Friendly Interface:** The app offers a simple and intuitive user interface, making interactions seamless and enjoyable.
- **Versatile Applications:** From answering questions to providing suggestions, the app can assist users in various scenarios.
- **Hackathon Winning Project:** ChatGpt Android App emerged as the winner of the "Best Project" award in the hackathon.



## How to Use

- Download and install the ChatGpt Android App from the provided link.
- Launch the app and start a conversation by typing.
- The AI chatbot will respond with contextually relevant answers and engage in interactive dialogue.
- Explore the various use cases and functionalities of the app.


## Using the ChatGPT API

1) Prerequisites
- An OpenAI account
- Access to the GPT-3 API (You may need to join a waitlist or have API access granted)

2) Installation
- Install the OpenAI Python library using pip:
  ```bash
  pip install openai
  ```
- Import the library into your Python script:
  ```bash
  import openai
  ```
- Set your OpenAI API key as an environment variable:
  ```bash
  export OPENAI_API_KEY=your-api-key
  ```
- Making API Requests
  ```bash
  import openai
  
  openai.api_key = "your-api-key"
  
  response = openai.Completion.create(
  engine="text-davinci-003",  # Use the appropriate engine
  prompt="Translate the following English text to French: 'Hello, how are you?'",
  max_tokens=50)
  
  print(response.choices[0].text.strip())
  ```

3) Installation of Android Studio

```bash
  https://developer.android.com/studio
```



    
## Screenshots

![App Screenshot](https://drive.google.com/uc?id=1NsJFrg3g46S0eiqrSmfotjYTwPzht4ng)


![App Screenshot](https://drive.google.com/uc?id=1f7ImTAGbyEpr-4DadH_iW6uCY_1moSrB)


![App Screenshot](https://drive.google.com/uc?id=1yPZIvtX0or3V4vD0NiIf4tnfsuMYMlnC)


![App Screenshot](https://drive.google.com/uc?id=1skVOupg3CwVWPbT3EzLHEdR3Wn8Kw1ZX)


![App Screenshot](https://drive.google.com/uc?id=1_S5HK_7Cm-NAMh_hG2tL8-t7WJdsyhBa)


![App Screenshot](https://drive.google.com/uc?id=1jDYiLrISQlnmdbsdCW-cmtx3EdjzCH_6)




## Future Enhancements

- Integration with additional AI models for enhanced capabilities.
- Customization options for user interactions.
- Improved user feedback mechanisms.


## Acknowledgements

We would like to express our gratitude to the organizers of the "Code for Life: Hackathon for everyday solutions" for providing us with the opportunity to develop and showcase our project. We also extend our thanks to OpenAI for their GPT-3.5 model, which powers the intelligent conversations in our app.

