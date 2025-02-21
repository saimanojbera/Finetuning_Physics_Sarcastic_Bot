# Sarcastic Astronomy Bot

## Overview
This project implements a **fine-tuned AI chatbot** designed to provide **sarcastic yet scientifically accurate** answers to astronomy-related questions. The model injects humor and wit into astronomical discussions, making learning about space and celestial phenomena more engaging and entertaining.

## Features
- **Fine-tuned GPT-3.5 Model:** Trained to respond with sarcasm while maintaining scientific accuracy in astronomy.
- **Engaging and Humorous Responses:** Turns complex space topics into fun, digestible explanations.
- **Handles a Wide Range of Astronomy Questions:** Covers black holes, wormholes, cosmic energy, planetary survival, and more.
- **Dataset-Based Training:** Uses curated sarcastic astronomy dialogues for improved consistency in personality.

---

## Project Components

### 1. **Fine-Tuning Process** (`Finetuned_Physics_Sarcasticbot.ipynb`)
- Model: `ft:gpt-3.5-turbo-0125:personal::B1PfZKHk`
- Trained using `physics_train.jsonl` (sarcastic astronomy question-answer pairs).
- Evaluated using `Physics_test.jsonl`.

### 2. **Training Data** (`physics_train.jsonl` & `Physics_test.jsonl`)
- Contains multiple sarcastic responses to common astronomy queries.
- Designed to balance humor with accurate explanations.

### 3. **Playground Interactions & Testing** (`Playground_Interactions_Sarcastic_bot.docx`)
- Includes sample user queries and model-generated responses.
- Compares outputs before and after fine-tuning.
- Example questions include:
  - *What is a black hole?*
  - *Can humans survive on Mars?*
  - *When will Earth explode?*
  - *Does Pluto live?*

---

## Installation & Setup

### **Prerequisites**
- Python 3.8+
- Jupyter Notebook
- Required Libraries:
  ```bash
  pip install openai pandas jsonlines
  ```

### **Running the Project**
1. **Fine-tune the model:**
   - Train the model using `physics_train.jsonl`.
   - Use OpenAI’s fine-tuning API to adjust responses.
2. **Test the model:**
   - Run queries from `Physics_test.jsonl` to evaluate sarcasm & accuracy.
3. **Deploy the chatbot:**
   - Integrate with a messaging platform or web API.

---

## Example Query Flow
### **User Query:**
> "What is a black hole?"

### **Model Response:**
> "Oh, just a friendly little void that eats everything in sight, including your hopes and dreams. You know, no big deal."

---

## Future Enhancements
- **Adjustable Sarcasm Level:** Let users toggle between mild and extreme sarcasm.
- **Voice-Based Interaction:** Convert into a voice assistant for educational use.
- **Multi-Turn Conversations:** Improve coherence in longer discussions.

---

## License
This project is for educational and research purposes. Use responsibly!

---

## Contact
For inquiries or contributions, feel free to reach out!