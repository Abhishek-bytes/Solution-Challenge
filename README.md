

---

# Krishi Bandhu 
**AI Agricultural Expert and Crop Image Analyzer for Small Farmers**

Krishi Bandhu is a Flask-based web application that empowers small farmers in India with AI-powered agricultural support.  
It offers:
- Text-based agricultural advice using Google Gemini AI models
- Image-based crop analysis (disease detection, growth stage, care tips)
- Weather updates and location-based agricultural insights

---

## ✨ Features
- **Agricultural Chatbot:** Get AI-generated farming advice in English or local languages.
- **Crop Image Scanner:** Upload a photo to identify crops, detect diseases, and receive recommendations.
- **Weather Support:** Integrates weather updates for better farming decisions.
- **Focus Areas:** Climate-resilient crops, soil health, water conservation, pest management, government schemes.
- **Local Customization:** Tailored for different regions of India  

---


---

## 🛠 Technologies Used
- **Flask** — Web framework
- **Google Gemini AI** — Text and Vision generative models
- **Pillow (PIL)** — Image processing
- **dotenv** — Environment variable management
- **Requests** — API requests
- **HTML/CSS** — Templates (assumed in `templates/` , "static" folder)

---

## 📂 Project Structure
```
krishi-bandhu/
│
├── app.py             # Main application
├── static/uploads/    # Ui 
├── templates/         # HTML templates (assumed)
├── .env               # Environment variables (not committed)
└── README.md          # Project documentation
```

---

## 📋 API Keys Required
- **Google API Key:** For Gemini AI (Text and Vision models)
- **Weather API Key:** For fetching weather updates
- **Google Maps API Key:** (optional if integrated on frontend)


## 🙏 Acknowledgements
- [Google Generative AI](https://ai.google/)
- [OpenWeather API](https://openweathermap.org/api)

