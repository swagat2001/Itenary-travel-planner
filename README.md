# 🌍 AI-Powered Travel Planner 🚀  

## 📌 Overview  
The **AI-Powered Travel Planner** is an **agent-driven** trip planning tool that provides a **3-day itinerary**, **budget recommendations**, and **real-time travel insights** using **LLMs (Google Gemini-1.5-Flash)** and **Serper API for live search results**.  

This project leverages **CrewAI** to create **intelligent agents** that gather travel information, optimize budgets, and generate a travel itinerary—all through a **Streamlit-based web interface**.  

---

## 🔧 Technologies Used  

- **Python** 🐍 (Backend)  
- **Streamlit** 📊 (Frontend UI)  
- **CrewAI** 🤖 (AI Agent Orchestration)  
- **Serper API** 🌍 (Real-time Travel Search)  
- **Google Gemini API** 🔥 (AI Language Model)  
- **Ngrok** 🌎 (Public Web Access)  

---

## 📜 Features  

✅ **Real-time Travel Research** (Tourist spots, weather, transport)  
✅ **Budget Planning** (Hotels, flights, expenses breakdown)  
✅ **3-Day Itinerary Generation** (AI-powered recommendations)  
✅ **Interactive Web UI** (Streamlit-based)  
✅ **AI-Powered Agents** (CrewAI for research & planning)  
✅ **Public Access via Ngrok**  

---

## 📂 Project Structure  

```
📦 Travel-Planner  
 ┣ 📜 app.py (Main Application)  
 ┣ 📜 requirements.txt (Dependencies)  
 ┣ 📜 README.md (Project Documentation)  
 ┗ 📜 .gitignore (Ignore Unnecessary Files)  
```

---

## 🛠 How It Works  

### **1️⃣ Web Interface (Streamlit)**  
- Users enter a **destination & budget**.  
- Click **"Generate Itinerary"** to start the planning process.  

### **2️⃣ AI Agents (CrewAI)**  
- **Travel Researcher Agent** → Fetches **tourist attractions, weather, transport**.  
- **Budget Planner Agent** → Finds **hotels, flights, cost estimates**.  
- **Itinerary Planner Agent** → Combines all data into a **3-day travel plan**.  

### **3️⃣ Real-time Search (Serper API)**  
- Fetches **live travel info** (flights, hotels, places to visit).  

### **4️⃣ AI Model (Gemini-1.5-Flash)**  
- Generates **natural language responses** for itinerary planning.  

---

## 🔌 Installation & Setup  

### **1️⃣ Install Dependencies**  
```bash
pip install streamlit crewai crewai-tools pyngrok
```

### **2️⃣ Set Up API Keys**  
```python
import os
os.environ["GOOGLE_API_KEY"] = "your-gemini-key"
os.environ["SERPER_API_KEY"] = "your-serper-key"
```

### **3️⃣ Run the App**  
```bash
streamlit run app.py
```

### **4️⃣ Share Publicly (Using Ngrok)**  
```bash
ngrok authtoken your-ngrok-token
ngrok http 5000
```

---

## 🌍 Alternative APIs You Can Use  

🔹 **For Travel Research:**  
- **Google Places API** – Fetch tourist spots, hotels, restaurants.  
- **Skyscanner API** – Find and compare flights.  

🔹 **For Budget Planning:**  
- **Booking.com API** – Hotel prices & availability.  
- **Amadeus API** – Flights, hotels, & transport booking.  

🔹 **For Weather Forecasts:**  
- **OpenWeather API** – Fetch real-time weather data.  

🔹 **For AI Models:**  
- **GPT-4 / GPT-3.5 (OpenAI)** – Advanced LLM-based text generation.  
- **Claude (Anthropic)** – Great for AI-based recommendations.  

---

## 📌 Future Improvements  

🔹 **Multi-day customizable itineraries**  
🔹 **Flight booking & price comparison integration**  
🔹 **Google Maps API for better navigation**  
🔹 **Enhanced UX/UI for improved interactivity**  

---

## 📖 Read Our Full Article on Medium  

We have published a detailed **guide & walkthrough** of this project. Read it on **Medium**:  
👉 [**Read Here (Demo Link)**](https://medium.com/@your-username/travel-planner-ai-demo)  

📌 *(This is a placeholder; update with the actual link after publishing the article.)*  

---

## 🎯 License  

This project is **open-source** and available under the **MIT License**. Feel free to modify and use it.  

---

## 🎉 Final Thoughts  

The **AI-Powered Travel Planner** is a **cutting-edge AI tool** for effortless trip planning. 🚀 With more integrations, it can become a **fully functional AI travel assistant**. 🌍  

---

## 💬 Have Questions?  

🔹 Open an **Issue** on GitHub  
🔹 Reach out on **Medium**  

🚀 **Happy Traveling!** ✈️🌍
