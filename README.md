##  🧾 Handwritten Prescription Extractor
A Streamlit-based web app that uses GPT-4o Vision to extract structured medical information from handwritten prescriptions.



##  📸 What It Does
Upload a scanned or photographed prescription and this app will automatically extract:

🧍‍♂️ Patient details (name, age, sex, address)

🗓️ Date and reason for visit / diagnosis

💊 Medications (drug name, dosage, quantity, instructions)

🩺 Physician information (name, license number, PTR number, signature if visible)

##  🚀 Live Demo
![screenshot-tested](https://github.com/user-attachments/assets/98cb3701-16ea-40ad-a123-8e5deff66776)


##  🧠Used
OpenAI GPT-4o Vision

Streamlit

Python libraries: PIL, requests, pyngrok


##  🧪 Model & Limitations
Uses gpt-4o for parsing both text and image input.

OCR accuracy depends on image clarity — poor lighting, blur, or illegible handwriting may degrade results.

The model does not diagnose conditions; it only extracts what's written.

An OpenAI API key is required to use the service.

##  🔐 Security
Your API key is entered manually and is never stored or shared.

API calls are sent directly to OpenAI via HTTPS from your browser session.

##  🙋‍♀️ Contributing
Contributions, improvements, and ideas are welcome!

##  🐞 Report issues via GitHub Issues

📥 Submit Pull Requests for features or bugfixes

##  🌟 Star the repo to support the project!

##  📄 License
This project is licensed under the MIT License.

##  🙏 Thank You
