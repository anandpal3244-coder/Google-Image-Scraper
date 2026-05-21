# 🖼️ Google Image Scraping Project (Jupyter Notebook)

## 📌 Project Overview
This project is a Python-based web scraping tool developed in a Jupyter Notebook to extract images from Google Images based on a user-defined search query. The scraped images are automatically downloaded and stored locally for further analysis or machine learning datasets.

---

## 🎯 Objective
The main goal of this project is to automate the process of collecting image datasets from Google Images using Python for tasks such as:
- Data collection for Machine Learning models
- Dataset creation for Computer Vision projects
- Research and analysis purposes

---

## ⚙️ Technologies Used
- Python 🐍
- Jupyter Notebook 📓
- Selenium 🤖
- BeautifulSoup (if used)
- Requests
- WebDriver Manager
- Google Chrome Driver

---

## 📂 Project Structure
│__ Google-Image-Scraper/
├── google_image_scraper.ipynb # Main Jupyter Notebook
├── images
└── README.md # Project documentation


---

## 🚀 Features
- Search images on Google automatically
- Extract multiple image URLs from search results
- Download images in bulk
- Save images into a local directory
- Fully automated scraping workflow

---

## ▶️ How to Run the Project

### 1️⃣ Install Dependencies
Run this command in your terminal:

```bash
pip install -r requirements.txt

2️⃣ Open Jupyter Notebook
jupyter notebook

Open:

google_image_scraper.ipynb

3️⃣ Run All Cells
Enter your search keyword
Specify number of images
Execute all cells
Images will be saved in the images/ folder

📸 Output Example

After running the notebook, images will be downloaded like:

images/
 ├── image1.jpg
 ├── image2.jpg
 ├── image3.jpg

⚠️ Challenges Faced
Handling dynamic loading of Google Images
Avoiding duplicate image URLs
Managing Selenium wait times
Fixing "0 images downloaded" issue (if applicable)

📈 Future Improvements
Add GUI using Streamlit or Flask
Improve scraping speed with async methods
Add multiple keyword scraping
Store image metadata in CSV/Database
Build dataset labeling system

👨‍💻 Author

Anand Kumar
Data Analyst | Python Developer | Aspiring ML Engineer


