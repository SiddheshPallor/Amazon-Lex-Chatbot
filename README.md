# 🤖 Amazon Lex Chatbot Project – Step-by-Step Implementation

This project demonstrates the creation of a **serverless chatbot** using **Amazon Lex**, with backend logic handled by **AWS Lambda**. The project is structured in modular steps to clearly explain each feature and implementation phase.

---

## 📌 Project Overview

- **Tech Stack:** Amazon Lex, AWS Lambda
- **Objective:** Build a functional chatbot capable of handling natural language inputs, responding to user queries, and executing backend logic through Lambda.
- **Approach:** Developed in five structured parts, each with its own documentation and setup.

---

## 📁 Project Structure

### 📂 `1_Setting_up_Lex_Chatbot/`
- Created the base Lex chatbot with default intents and sample utterances.
- Configured fallback messages and basic conversation flow.
- Includes screenshots and exported Lex bot configuration.

### 📂 `2_Add_Custom_Slots_to_Lex_Chatbot/`
- Added custom slots (e.g., name, location, preference) to capture specific user information.
- Defined slot prompts and slot type values for guided input.

### 📂 `3_Connect_Lex_with_Lambda/`
- Integrated AWS Lambda to fulfill intents dynamically.
- Created a basic Lambda function to handle the user input and return appropriate responses.
- IAM roles and permissions were configured to allow Lex to invoke Lambda.

### 📂 `4_Save_User_Info_with_Lex/`
- Demonstrated how to capture user input (slot values) and process them in Lambda.
- User info was logged or printed in the Lambda console for validation.
- No database used — focuses on processing and printing data during runtime.

### 📂 `5_Build_a_Chatbot_with_Multiple_Slots/`
- Combined multiple slots in a single intent for more detailed conversations.
- Added user confirmations and slot validation in the chatbot flow.
- Tested full interaction with Lex and Lambda integration.



