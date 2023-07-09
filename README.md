# 🎉 TikTok Analytics Project 🎉

[![Open In Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/vivek7208/TikTokAnalytics/blob/master/Tiktok%20Analytics%20Test.ipynb)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![Preview in nbviewer](https://img.shields.io/badge/render-nbviewer-orange.svg)](https://nbviewer.jupyter.org/github/vivek7208/TikTokAnalytics/blob/master/Tiktok%20Analytics%20Test.ipynb)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vivek7208/TikTokAnalytics/blob/master/Tiktok%20Analytics%20Test.ipynb)

This repository contains a Python-based project 🐍 designed to interact with the TikTok API, perform analytics on user data 📊, and present the results in an interactive web-based dashboard 💻. It includes a Jupyter notebook for testing 🧪, Python modules containing the core functionality and helper functions, and a Streamlit application script that serves as the entry point to the application.


## 📝 Table of Contents

- [About](#about) 📖
- [Features](#features) ✨
- [Installation](#installation) 🛠️
- [Usage](#usage) 🚀
- [Contributing](#contributing) 🤝
- [License](#license) 📜

## 📖 About

This project provides a comprehensive tool for understanding and analyzing user engagement and content performance on TikTok 📹. Using the TikTok API, it fetches data related to specific users and their videos, including view counts, shares, and more. Subsequent analysis of this data can provide valuable insights into user behavior and content performance, which are integral for content creators, marketers, and researchers.

The project employs the Streamlit library to present these insights in an easy-to-understand, user-friendly dashboard that allows for efficient data interpretation. The project is modular, with separate components for API interaction (`tiktok.py`), helper functions (`helpers.py`), and the main application (`app.py`). Additionally, it contains a Jupyter notebook (`Tiktok Analytics Test.ipynb`) that was used for testing purposes during development.

## ✨ Features

- **🌐 TikTok API Interaction**: The `TikTokAPI` class in `tiktok.py` provides methods for performing various operations with the TikTok API. These include obtaining information about a user, fetching user videos, and retrieving analytics related to these videos.

- **🧰 Helper Functions**: The `helpers.py` module contains various utility functions that assist in performing common tasks throughout the project. This includes functions for parsing dates, creating video objects from JSON responses, and calculating percent increases.

- **🖥️ Web-based Dashboard**: The `app.py` script uses the Streamlit library to create a web application that displays the analytics data. It imports the `TikTokAPI` class and the helper functions, and then uses them to fetch, analyze, and present the data.

- **🔬 Jupyter Notebook for Testing**: The `Tiktok Analytics Test.ipynb` is a Jupyter notebook used for testing the functionality of the project during development. It allows for interactive execution of code and immediate viewing of results, which facilitates testing and debugging.

## 🛠️ Installation

Before installing, ensure that you have Python 🐍 and pip installed on your system. Once these prerequisites are met, you can install the project by cloning this repository and installing the required dependencies.

```bash
git clone https://github.com/vivek7208/TikTok_Analytics.git
cd TikTok_Analytics
```

## 🚀 Usage

After installing, you can run the application by executing the `app.py` script.

```bash
streamlit run app.py
```

This will start the Streamlit server, and you can access the dashboard by navigating to the displayed URL in your web browser 🌐.

## 🤝 Contributing

We welcome contributions from the community 👏. If you'd like to contribute, please fork the repository and make your changes, then create a pull request against this repository.

## 📜 License

This project is licensed under the MIT License.
