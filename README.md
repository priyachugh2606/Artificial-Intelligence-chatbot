# 🤖 Java AI Chatbot (with GUI + Rule-Based NLP)

This is a simple AI Chatbot built using **Java Swing** for GUI and a **rule-based Natural Language Processing engine**. The chatbot can answer predefined FAQs and can be trained with new responses.

## 🎯 Features

- 🧠 **Rule-based NLP Engine**: Matches user input to common questions.
- 💬 **Interactive Chat UI** using Java Swing (`JFrame`, `JTextArea`, `JTextField`, etc.)
- 🔄 **Trainable Bot**: Easily extend the bot's knowledge by updating the rule set.
- 🔠 **Basic Text Preprocessing**: Cleans and normalizes user input using a custom `NLPProcessor`.

---

## 🖥️ Technologies Used

- Java (JDK 8+)
- Java Swing (GUI Framework)
- Core Java OOP (Classes, Maps, Events)

---

## 📦 Project Structure

```java
NLPProcessor     // Cleans and normalizes text input
FAQEngine        // Contains rules and logic to fetch answers or train new ones
ChatGUI          // Main class with Java Swing GUI for chat interaction
