# 💥 Mood-Roastify-Me

**Mood-Roastify-Me** is an interactive web application that generates playful **roasts** or heartfelt **compliments** based on user input and mood. Leveraging **natural language processing**, sentiment analysis, and text-to-speech, the app creates a fun, engaging experience with GIF reactions, voice feedback, and a history log for all interactions.

## 🔹 Features

* **Roast or Compliment Mode:** Switch between playful roasts or uplifting compliments.
* **Mood-Based Responses:** Customize the intensity of the roast or sweetness using a mood slider (-1 grumpy to +1 happy).
* **Mirror Mode:** Generate a roast using your own input text for added sass.
* **Voice Feedback:** Hear your roast or compliment via **Text-to-Speech (TTS)**.
* **Random Surprise:** Get a surprise roast or compliment for unpredictable fun.
* **Interactive GIF Reactions:** Each response comes with a relevant GIF to enhance the experience.
* **History Tracking:** Keep a record of all your roasts and compliments in-app.
* **Responsive Streamlit Interface:** Clean layout optimized for desktop and mobile.

## 🔹 Tech Stack

| Component                   | Details / Libraries Used                            |
| --------------------------- | --------------------------------------------------- |
| Frontend & Web Interface    | **Streamlit**                                       |
| Natural Language Processing | **TextBlob**, **Custom Roast & Compliment Engines** |
| Sentiment Analysis          | Mood-based response adjustment                      |
| Voice Output                | **gTTS (Google Text-to-Speech)**                    |
| Multimedia                  | GIFs via external links                             |
| Logging & History           | Python `datetime` and session state management      |

## 🔹 How to Use

1. **Launch the App** using Streamlit:

```bash
streamlit run app.py
```

2. **Set Your Mood:** Use the slider to indicate your current mood.
3. **Select Mode:** Roast or Compliment.
4. **Enter Text:** Optionally type something to roast (Mirror Mode).
5. **Get Response:** Click the “🔥 Roast Me!” or “💖 Compliment Me!” button.
6. **Hear It:** The response will be read aloud using TTS.
7. **View GIF:** Enjoy a GIF reaction to your roast or compliment.
8. **Check History:** Scroll down to view previous interactions.

## 🔹 Future Enhancements

* Add **AI-powered NLP** for more contextual roasts and compliments.
* Support **multi-language** roasts and compliments.
* Add **user authentication** to save personalized histories.
* Integrate **animated reactions** beyond GIFs for richer UX.
