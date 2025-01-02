# Auto-Reply AI Chatbot
# Naruto: The Roasting Virtual Assistant

Naruto is a virtual assistant designed to automate interactions with a chat application, analyze chat history, and generate humorous, roast-style responses using OpenAI's GPT-3.5-turbo model. This project leverages Python libraries for seamless automation and clipboard operations, offering an entertaining experience by delivering witty comebacks based on chat conversations.

---

## **Features**

### 1. Automated Chat Interaction
- Automates mouse and keyboard operations using **pyautogui** to interact with the chat application without manual intervention.

### 2. Chat History Analysis
- Copies and analyzes chat history to determine if the last message was sent by a specific user (e.g., "Rohan Das").

### 3. Humorous Response Generation
- Integrates with OpenAI's **GPT-3.5-turbo** model to generate funny, roast-style responses tailored to the analyzed chat history.

### 4. Clipboard Operations
- Utilizes **pyperclip** to copy chat history and paste the generated responses, ensuring smooth retrieval and insertion of messages.

---

## **Workflow**

### **1. Initialization and Setup**
- Launch the chat application by clicking on the Chrome icon.
- Wait for a brief period to ensure the application is ready for interaction.

### **2. Chat History Retrieval**
- Periodically select and copy chat history by dragging the mouse over the chat area and using the copy shortcut.
- Retrieve the copied text from the clipboard.

### **3. Message Analysis**
- Analyze the retrieved chat history to check if the last message is from a specific user (e.g., "Rohan Das").
- If the message matches the target user, send the chat history to OpenAI's **GPT-3.5-turbo** for humorous response generation.

### **4. Response Generation and Sending**
- Copy the generated response to the clipboard.
- Click on the chat input area and paste the response.
- Press 'Enter' to send the message.

---

## **Libraries Used**

1. **pyautogui**: Automates mouse and keyboard interactions.
2. **time**: Adds delays between operations for smooth automation.
3. **pyperclip**: Handles clipboard operations for text copying and pasting.
4. **openai**: Integrates with OpenAI's GPT-3.5-turbo for generating roast-style responses.

---

## **How Naruto Works**

1. **Launch and Setup**
   - Naruto opens the chat application and waits for it to load.

2. **Chat History Analysis**
   - Copies the chat history periodically and checks if a target user has sent the last message.

3. **Roast Creation**
   - Analyzes the chat history and generates a witty comeback using OpenAI's GPT-3.5-turbo.

4. **Send Response**
   - Inserts the humorous response into the chat and sends it.

---

Naruto ensures a fun and interactive way to lighten up your chats with automated humor. Perfect for sparking laughter and keeping conversations engaging! 🚀

