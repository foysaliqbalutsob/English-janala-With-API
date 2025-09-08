# 📘 English Janala  

An interactive web platform to **learn English vocabulary** with lessons, search functionality, pronunciation, and detailed word meanings.  

## 🚀 Features  

- **Lesson-based Learning**  
  - Fetches lessons dynamically from API.  
  - Each lesson contains a list of vocabulary words.  

- **Word Details Modal**  
  - Shows meaning, pronunciation, example sentence, and synonyms.  

- **Word Pronunciation**  
  - Uses **Web Speech API** to pronounce selected words aloud.  

- **Search Functionality**  
  - Search any word across all lessons.  

- **Spinner Loading State**  
  - Displays a spinner while fetching data from the API.  

- **Responsive Design**  
  - Built with **Tailwind CSS** + **DaisyUI** for modern UI.  

---

## 🌐 APIs Used  

The app uses **Programming Hero Open API**:  

- **Get All Lessons**  
  ```http
  GET https://openapi.programming-hero.com/api/levels/all
  ```  

- **Get Words by Lesson ID**  
  ```http
  GET https://openapi.programming-hero.com/api/level/{id}
  ```  
  Example: `/api/level/1` → Fetches words for Lesson 1.  

- **Get Word Details by ID**  
  ```http
  GET https://openapi.programming-hero.com/api/word/{id}
  ```  

- **Get All Words (for Search)**  
  ```http
  GET https://openapi.programming-hero.com/api/words/all
  ```  

---

## 🛠️ Tech Stack  

- **Frontend**: HTML, CSS, Tailwind CSS, DaisyUI  
- **JavaScript**: Vanilla JS for DOM manipulation and API calls  
- **API**: Programming Hero Vocabulary API  
- **Browser API**: Web Speech API (for pronunciation)  

---

## 📂 Project Structure  

```
.
├── index.html        # Main HTML file
├── script/
│   └── index.js      # Core logic & API integration
├── style/
│   └── style.css     # Custom styles
├── assets/           # Images, logos, icons
└── README.md         # Project documentation
```

---

## ▶️ How to Run  

1. Clone this repository  
   ```bash
   git clone https://github.com/your-username/english-janala.git
   cd english-janala
   ```  

2. Open `index.html` in your browser.  

3. Make sure you are connected to the internet (for API, Tailwind, DaisyUI, and FontAwesome).  
