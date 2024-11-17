# DeepChef

DeepChef is an innovative recipe recommendation system designed to assist users in finding the most relevant and visually appealing recipes based on their input. By leveraging advanced image processing techniques and a comprehensive dataset of recipe images, DeepChef ensures a seamless and engaging user experience.

## 📜 **Project Overview**

The core idea behind DeepChef is to provide accurate recipe recommendations by analyzing and comparing dish images. The project includes web scraping to gather data, image encoding for feature extraction, and a Django web application for user interaction.

### **Key Features:**
- **Comprehensive Dataset:** 
  - 3,360 images of various dishes collected from the Food.com website.
  - 336 recipes, including detailed ingredients and cooking instructions.
- **Data Collection & Cleaning:** 
  - Web scraping was performed using Selenium and BeautifulSoup.
  - Collected recipe data was meticulously cleaned using Python.
- **Image Encoding:** 
  - DenseNet 201, a state-of-the-art convolutional neural network, was used for efficient image feature extraction.
- **Recipe Recommendation:** 
  - Cosine Similarity was employed to match and recommend the top five similar recipes based on input images with 90% accuracy.
- **User-Friendly Interface:** 
  - A Django-based web application provides an intuitive platform for users to search and explore recommended recipes effortlessly.

## 🚀 **Technologies Used**

| Skill                   | Technology               |
|-------------------------|--------------------------|
| **Web Scraping**        | Selenium, BeautifulSoup  |
| **Data Cleaning**       | Python (Pandas, NumPy)   |
| **Image Encoding**      | DenseNet 201 (Keras, TensorFlow) |
| **Similarity Search**   | Cosine Similarity        |
| **Web Development**     | Django                   |

## 📂 **Dataset Details**
- **Images:** 3,360 food images categorized by dish type.
- **Recipes:** 336 unique recipes including title, ingredients, instructions, and image URL.

## **Prerequisites:**
- Python 3.11 or above
- Git
- Virtual environment setup tools (`venv` or `conda`)
- Web drivers for Selenium (e.g., ChromeDriver)

## 📈 **Performance Metrics**

- **Image Matching Accuracy:** Achieved an efficiency rate of 90% using cosine similarity with DenseNet 201 encodings.

## 🤖 **Skills Demonstrated**

- Web Scraping, Data Processing, Image Processing, Web Development

## 💾 **Large Data Handling**

- The `image_data` directory is excluded from the repository due to its large size. You can download the dataset separately from the provided link or contact the repository owner for access.
[GoogleDrive](https://drive.google.com/drive/folders/1MuQO6Iyhp9D1YN29uJXdz4AcL8ysNfJr?usp=sharing)

## 🙌 **Contributing**

Contributions, issues, and feature requests are welcome! Feel free to fork the repository and submit a pull request.

## 👥 **Author**

- **Aditi Singh** - [LinkedIn](https://www.linkedin.com/in/aditi-singh21/)
