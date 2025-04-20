# Analyzer

Here’s a professional **README.md** file for your **Website Design Analyzer** project. You can copy and paste this into your GitHub repository or project documentation:

---

# **🌐 Website Design Analyzer**  
**AI-Powered Design Feedback & Code Generation Tool**  

# Demo Screenshot
![Screenshot 2025-04-20 060202](https://github.com/user-attachments/assets/b28a182d-3564-4f3c-b07b-efa99a51c845)
![Screenshot 2025-04-20 060238](https://github.com/user-attachments/assets/a26a41ba-72ed-4cb5-8cf2-c6ffd1497b04)
![Screenshot 2025-04-20 060304](https://github.com/user-attachments/assets/a90e8a51-167b-41eb-a242-6a8e8bbf4938)


## **🚀 Features**  
✅ **AI-Powered Design Analysis** – Get instant feedback on colors, typography, and layout.  
✅ **Multi-Tech Code Generation** – Convert designs into **React, HTML/CSS, Vue, or Next.js** code.  
✅ **Custom Prompt Support** – Tailor code output with specific instructions.  
✅ **Interactive Screenshot Preview** – View and download website snapshots.  
✅ **Typewriter Effect** – Animated code display for better readability.  

---

## **🛠️ Tech Stack**  
| **Frontend** | **Backend** | **AI & Tools** |  
|--------------|-------------|----------------|  
| React.js     | Flask (Python) | Google Gemini AI |  
| Axios        | Playwright  | CSS3/HTML5     |  

---

## **📥 Installation**  

### **1. Backend Setup**  
```bash
# Clone the repository
git clone https://github.com/yourusername/website-design-analyzer.git
cd website-design-analyzer/backend

# Install dependencies
pip install flask flask-cors playwright google-generativeai python-dotenv

# Install Playwright browsers
playwright install

# Set up environment variables (create `.env` file)
echo "GEMINI_API_KEY=your_api_key_here" > .env

# Run the Flask server
python app.py
```

### **2. Frontend Setup**  
```bash
cd ../frontend

# Install dependencies
npm install axios react react-dom

# Start the React app
npm start
```

---

## **🎯 How It Works**  
1. **Enter a URL** (e.g., `https://example.com`).  
2. **Get AI Analysis** – Score, design suggestions, and improvements.  
3. **Generate Code** – Pick a tech stack (React, Vue, etc.) and customize prompts.  
4. **Download/Export** – Copy code or download the screenshot.  

---

## **📷 Demo**  
*(Add GIF/video or screenshots here showing the workflow.)*  

---

## **🚧 Challenges & Solutions**  
| **Challenge**               | **Solution**                          |  
|-----------------------------|---------------------------------------|  
| AI providing inconsistent code | Fine-tuned prompts & output formatting |  
| CORS errors                 | Configured Flask-CORS properly        |  
| Dynamic site screenshots    | Used Playwright for full-page capture |  

---

## **📂 Project Structure**  
```
website-design-analyzer/  
├── backend/  
│   ├── app.py               # Flask server  
│   ├── .env                 # API keys  
│   └── screenshots/         # Captured images  
└── frontend/  
    ├── src/  
    │   ├── App.jsx          # Main React component  
    │   └── styles.css       # Styling  
    └── package.json         # Frontend dependencies  
```

---

## **🔮 Future Improvements**  
- [ ] **Figma Plugin** – Directly import designs.  
- [ ] **Mobile App** – React Native version.  
- [ ] **Auth & Projects** – Save user history.  

---

## **🙏 Credits**  
- **Google Gemini API** – For AI analysis & code generation.  
- **Playwright** – Reliable website screenshots.  

---

## **📜 License**  
MIT © [Your Name]  

---

### **🔗 Links**  
- [Live Demo](#) *(Add when deployed)*  
- [Report Issues](https://github.com/yourusername/website-design-analyzer/issues)  

---

This README provides a **clear, structured overview** of your project. Customize it with:  
- **Real screenshots/GIFs**  
- **Deployment guide** (if hosted on Vercel/Netlify)  
- **Detailed API docs** (if applicable)  

Let me know if you'd like any modifications! 🚀
