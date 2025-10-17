# 🎓 SOP Generator App

An AI-powered **Statement of Purpose (SOP) Generator** designed to help students applying abroad (especially to Germany) create personalized, professional SOPs effortlessly.  
The system uses **OpenAI GPT models**, **Natural Language Processing (NLP)**, and **Streamlit** for an intuitive and interactive user experience.

---

##Video link 

▶️ [Watch the demo video on Loom]([https://www.loom.com/share/abcdef123456](https://www.loom.com/share/624bf1ef3ae648a79718a6b9fc729282?sid=873b577f-8d68-416c-bab0-66cd9eb47e58))


## 🚀 Features

- 🧠 **AI-Based SOP Generation**  
  Uses OpenAI’s GPT API to generate personalized and coherent SOPs tailored to the user’s input and resume.

- 📄 **Resume Upload & Data Extraction**  
  Automatically extracts relevant details from uploaded resumes using SpaCy and PyPDF2.

- 🏫 **University & Program Customization**  
  Users can input their target university and program to make the SOP more specific and impactful.

- 🔧 **Adjustable Creativity (Temperature Control)**  
  Lets users choose the tone and creativity level of their SOPs.

- ☁️ **Firebase Integration**  
  Provides user authentication and secure data storage for user details.

- 📑 **Downloadable Word Document**  
  The final SOP can be downloaded in Word format (`.docx`) for easy submission or editing.

- ⚡ **Asynchronous Performance**  
  Uses Python `asyncio` and `aiohttp` to optimize response time and API handling.

---

## 🛠️ Technologies Used

- **Frontend & UI:** Streamlit  
- **AI Model:** OpenAI GPT-3  
- **Backend & APIs:** Python, REST APIs  
- **NLP Tools:** SpaCy, PyPDF2, python-docx  
- **Database & Auth:** Firebase  
- **Other Libraries:** BeautifulSoup, Requests, AsyncIO, AIOHTTP, dotenv  

---

## 📦 Installation

To run this project locally:

```bash
# Clone the repository
git clone https://github.com/YourUsername/SOP-GENERATOR.git

# Navigate to the project directory
cd SOP-GENERATOR

# Install the dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run generator_with_diff.py
