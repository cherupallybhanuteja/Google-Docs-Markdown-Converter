# Google Docs Markdown Converter

## 📌 Description
This Python script converts **Markdown-formatted meeting notes** into a **well-structured Google Doc** using the **Google Docs API**.

## ⚡ Features
✔ Converts Markdown into **proper Google Docs styling (H1, H2, H3)**  
✔ Maintains **bullet points, checkboxes (`☐`), and mentions (`@name`)**  
✔ Automatically **creates and updates a Google Doc**  

## 🚀 Setup Instructions
### **1️⃣ Enable Google Docs API**
- Go to [Google Cloud Console](https://console.cloud.google.com/)
- Create a **new project** or use an existing one.
- Enable **Google Docs API** and **Google Drive API**.
- Create a **Service Account** and generate a **JSON key file**.

### **2️⃣ Upload JSON Key File to Google Colab**
- In Google Colab, run:
  ```python
  from google.colab import files
  files.upload()
  Select the downloaded JSON key file.

### **3️⃣ Install Dependencies**  
Run this in a Colab cell:  
```sh
!pip install --upgrade google-auth google-auth-oauthlib google-auth-httplib2 google-api-python-client gspread

### **4️⃣ Run the Notebook**  
- Open **Google_Docs_Markdown_Converter.ipynb**  
- Execute the cells in order.

## 🔗 **How to Run**  
📌 **Follow these steps to execute the script in Google Colab:**  
1️⃣ **Upload the JSON key file** to Google Colab.  
2️⃣ **Run the Python script**.  
3️⃣ **Open the generated Google Doc link**.  
4️⃣ **Verify that all Markdown content is formatted correctly**.  

