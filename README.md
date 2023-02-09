# Cohere-Interview-Bot
A chatbot that helps the candidate to prepare for behavioural and technical interview questions by analysing his resume and job description.

## Introduction
This repository contains code for a chatbot that helps job seekers prepare for interviews by analyzing their resume and job description. The chatbot is built using Cohere's language model, which has been fine-tuned (zero-shot) for the specific task of interview preparation.

## Getting Started
To get started, you will need to upload your resume and job description. The chatbot will then analyze the text and generate questions and answers based on your experience and the requirements of the job. It will generate first 3 questions based on the Resume and 7 based on the job role.
![Architecture](https://user-images.githubusercontent.com/111684119/217772574-59ad8041-73fa-4746-a9a8-5acfdb4bd057.png)

## Features
- Generates questions based on your resume and job description
- Provides answers to common interview questions
- Prepare as if chatting with an interviewer !

## Usage
To use the chatbot, simply run [Streamlit](https://cohear.streamlit.app/) and follow the prompts to upload your resume and job description. You can then start chatting with the chatbot to prepare for your interview.

## Future Work
- Add voice based interaction (most of the work done, just stuck!)
- Make it fast - Due to _many_ API calls it is slow right now
- Add question answer source for faster retrieval (Used a machine learning Q&A dataset - but wanted to generalize it for all jobs)
- A better frontend
## Limitations
- Hallucinations - can deviate from the topic !
- Please note that the chatbot is not a substitute for professional interview preparation and is intended for educational and informational purposes only.
Contributing

We welcome contributions to this repository. If you have any suggestions for improvement or bug fixes, please create a pull request or open an issue.

## Contributors
This project has been created by a team in a hackathon and special thanks to [Ibtisam Mohammad](https://github.com/Ibtisam-Mohammad) and [Leandra Pearson](https://www.linkedin.com/in/leandrapearson/) for making it happen. 
