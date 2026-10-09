# 🥗 MacroSnap – AI-Powered Food Nutrition Tracker

**MacroSnap** is an AI-powered food nutrition tracking application that helps users understand the nutritional information of their meals by simply uploading or capturing a food image.

Snap your food, track its nutrition, and get useful insights with AI!

## ✨ Features

* 📸 **Food Image Analysis:** Upload a food image for AI-powered analysis.
* 🥗 **Nutrition Tracking:** Get estimated nutritional information for your meal.
* 🤖 **AI-Powered Insights:** Uses Google Gemini to analyze food images and provide nutrition details.
* 📱 **Simple Interface:** Easy-to-use application built with Streamlit.
* 💬 **Results Sharing:** Designed to help users share their food nutrition results through messaging integrations, when configured.

## 🛠️ Technologies Used

* Python
* Streamlit
* Google Gemini API
* Google Gen AI SDK
* Twilio API (if messaging integration is enabled)

## 📂 Project Structure

```text
MacroSnap/
├── app.py
├── requirements.txt
├── .streamlit/
│   └── secrets.toml.example
├── .gitignore
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd macrosnap
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

### 3. Activate the Virtual Environment

**Windows PowerShell:**

```powershell
.\venv\Scripts\Activate.ps1
```

### 4. Install Dependencies

```bash
python -m pip install -r requirements.txt
```

### 5. Configure API Keys

Create a `.streamlit/secrets.toml` file and add the API keys required by your application.

Example:

```toml
GEMINI_API_KEY = "your-gemini-api-key"

# Add Twilio credentials here if your app uses Twilio
```

Keep your real API keys private. Never upload your actual `secrets.toml` file or other secret credentials to GitHub.

### 6. Run the Application

```bash
streamlit run app.py
```

The application will open in your browser.

## 🔐 Security

* Store API keys in Streamlit secrets.
* Keep `.env`, `secrets.toml`, and other credential files out of GitHub.
* Never share API keys or authentication tokens publicly.

## ⚠️ Disclaimer

MacroSnap provides AI-generated nutritional estimates for informational purposes only. Actual nutritional values may vary depending on ingredients, portion sizes, and preparation methods. It is not a substitute for professional dietary advice.

## 🚀 Future Enhancements

* Save daily food and nutrition history.
* Display daily nutrition summaries.
* Improve food recognition accuracy.
* Add more nutrition visualization features.
* Enhance messaging integration.

## 👨‍💻 Author

**Sathwik**

Built with Python, Streamlit, and Google Gemini AI.

---

⭐ If you find MacroSnap useful, consider starring the repository on GitHub!
