# Desktop Voice Assistant Project

![Project Front Page](path_to_your_front_page_image.jpg)

**Course**: CSE-316 (Artificial Intelligence Lab)  
**Institution**: Green University of Bangladesh  
**Semester**: Spring 2024  
**Author**: MD Dulal Hossain (ID: 213902116)  
**Submission Date**: 04-05-2024  
**Instructor**: Sagufta Sabah Nakshi  

---

## Project Overview

[![Project Video Overview](path_to_thumbnail_image.jpg)](https://www.youtube.com/watch?v=your_video_link "Watch the video overview")

The **Desktop Voice Assistant** is a Python-based project that allows users to interact with their computer using both text and voice commands. It features a Graphical User Interface (GUI) built using Tkinter and integrates **speech recognition** for voice commands, as well as **text-to-speech** responses using pyttsx3. The assistant can perform tasks such as retrieving weather updates, playing music, opening websites, and more. This project aims to make computer interaction more intuitive and accessible, especially for users with disabilities or those seeking hands-free control.

---

## Table of Contents
1. [Motivation](#motivation)
2. [Problem Definition](#problem-definition)
3. [Design Goals and Objectives](#design-goals-and-objectives)
4. [Applications](#applications)
5. [Project Details](#project-details)
6. [Implementation Workflow](#implementation-workflow)
7. [Tools and Libraries](#tools-and-libraries)
8. [Performance Evaluation](#performance-evaluation)
9. [Conclusion](#conclusion)
10. [Future Work](#future-work)

---

## Motivation

The motivation behind this project is to leverage **artificial intelligence** and **natural language processing** (NLP) to create an assistant that simplifies everyday tasks through voice commands. Inspired by the capabilities of popular voice assistants like Siri and Alexa, this desktop assistant aims to bring similar functionality to the desktop environment, enhancing user experience and accessibility.

---

## Problem Definition

The main problem addressed by this project is the need for a more efficient, hands-free way to interact with computers. Traditional input devices like keyboards and mice can be limiting, particularly for individuals with physical disabilities. This voice assistant aims to provide an alternative, user-friendly solution by integrating voice recognition and text-to-speech technologies to perform tasks such as playing music, fetching information, and navigating the web.

---

## Design Goals and Objectives

The design goals for this project are:
- **Intuitive User Interface**: A clean and easy-to-use GUI built using Tkinter.
- **Voice Command Execution**: Allow users to execute tasks such as opening websites, fetching weather data, and playing music.
- **Speech Recognition**: Use the `SpeechRecognition` library to enable hands-free control via voice commands.
- **Text-to-Speech Feedback**: Provide audible responses using the `pyttsx3` library.
- **Error Handling**: Handle errors gracefully to ensure smooth user experience.

---

## Applications

The **Desktop Voice Assistant** can be used in a variety of settings:
- **Home Automation**: Controlling your computer hands-free.
- **Accessibility**: Providing assistance to individuals with physical disabilities by offering voice command control.
- **Information Retrieval**: Fetching real-time data such as weather updates and opening relevant websites.

---

## Project Details

The assistant integrates multiple features:
- **GUI**: Built using Tkinter for both text and voice input.
- **Speech Recognition**: Converts spoken commands into text.
- **Text-to-Speech**: Provides spoken responses.
- **Functional Actions**: Can open websites, play music, retrieve weather information, and check the time.

---

## Implementation Workflow

1. **Initialization**: The assistant greets the user and waits for a command.
2. **Listening for Commands**: Listens for voice commands or accepts text input.
3. **Action Execution**: Executes tasks like retrieving weather information, opening websites, or playing music.
4. **Conversation Handling**: Provides responses to basic questions and performs actions based on voice input.
5. **Error Handling**: Catches errors and provides feedback if a command is not recognized or if there is a system error.
6. **Termination**: The user can close the assistant by giving a quit or shutdown command.

---

## Tools and Libraries

The project uses the following tools and libraries:
- **Tkinter**: For building the graphical user interface.
- **PIL**: For image processing within the GUI.
- **SpeechRecognition**: For capturing and recognizing voice commands.
- **pyttsx3**: For converting text into speech.
- **requests-html**: For web scraping to retrieve real-time data such as weather information.

---

## Performance Evaluation

The assistant was tested in the following environment:
- **PC Configuration**:
  - RAM: 16GB
  - Storage: 512 GB SSD + 1TB HDD
  - Processor: Intel Core i5 10th Gen

### Results
1. **Voice Recognition**: The assistant successfully recognizes and processes various voice commands, including retrieving the weather and opening websites like Wikipedia.
2. **GUI Performance**: The user interface is responsive and handles both voice and text input efficiently.
3. **Functional Accuracy**: Commands like playing music, opening websites, and retrieving weather data were executed accurately.

---

## Conclusion

The **Desktop Voice Assistant** provides a hands-free, intuitive way to interact with your computer. By integrating speech recognition and text-to-speech, it enhances user experience and accessibility. While the project works as intended, there is room for improvement in areas such as error handling and expanding its functionalities.

---

## Future Work

Future improvements could include:
1. **Improved Speech Recognition**: Enhancing the accuracy of the assistant in noisy environments.
2. **Learning from Interactions**: Incorporating machine learning to allow the assistant to adapt to user preferences.
3. **Multilingual Support**: Expanding the assistant's language capabilities to support non-English speakers.
4. **Expanded Features**: Adding more functionalities, such as controlling IoT devices or personalized recommendations.
5. **Accessibility Features**: Enhancing the assistant to cater to users with more diverse needs, such as individuals with disabilities.

---

## References

1. [Python SpeechRecognition Documentation](https://pypi.org/project/SpeechRecognition/)
2. [pyttsx3 Documentation](https://pypi.org/project/pyttsx3/)
3. [Tkinter Documentation](https://docs.python.org/3/library/tkinter.html)
4. [Learn Python](https://www.learnpython.org/)
