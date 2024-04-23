# 🌐 Web Scraping and Data Processing Project 🚀

![Version](https://img.shields.io/badge/version-1.0-blue.svg)
![Python](https://img.shields.io/badge/python-3.10-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## 📋 Overview

This project provides a robust solution for scraping web data and processing it efficiently. It uses a blend of requests for multi-threaded data fetching and playwright for dynamic interactions with web pages, making it ideal for handling complex scraping tasks. The data processing part is finely tuned to work with large datasets efficiently, providing quick insights and outputs in various formats.

## 🌟 Features

- Dynamic Web Scraping: Utilizes playwright to interact with JavaScript-heavy websites dynamically.
- Multi-threaded Requests: Employs requests library in a multi-threaded setup to speed up the data fetching process.
- Efficient Data Processing: Leverages pandas and numpy for data cleaning, manipulation, and aggregation.
- Automated Data Collection: Scripts that automate the collection of data periodically, ensuring fresh data is always available.
- Customizable Outputs: Provides functionality to export data into CSV, JSON, or directly into databases.

## 🔧 Installation

```bash
git clone https://github.com/yourusername/projectname.git
cd projectname
pip install -r requirements.txt
```

## 🚀 Usage

To run the script with default settings:
```bash
python main.py
```
To customize the scraping and processing:
```bash
python main.py --days 10 --pages https://www.tiktok.com/@infinityhoop https://www.tiktok.com/@anotherpage --target_eye 50 20000 150 600000 700 --target_star 30 10000 200 300000 400
```
- --days: Number of days to fetch data for (default: 7).
- --pages: TikTok pages to scrape.
- --target_eye & --target_star: Set targets for different metrics like Posts, Likes, Comments, Plays, and Saves.

## 🎨 How It Works

1. Initialization: Set up the URLs and parameters for the scraping.
2. Web Scraping:
   - playwright: Handles dynamic pages, simulating user interactions to fetch data rendered by JavaScript.
   - requests: Manages multiple threads to fetch data from API endpoints or simpler HTML pages.
3. Data Processing:
   - Data is processed and transformed using pandas, with the results being saved into a detailed Google Sheet, which includes comprehensive analytics on emoji usage, engagement metrics, and more.
4. Output:
   - The final output is a Google Sheet which provides a granular view of data metrics by emoji, showing both actual values and predefined targets.

## 📦 Dependencies

- Python 3.10
- pandas
- numpy
- playwright
- requests

## 🤝 Contributing

Contributions are welcome! Please read the contributing guide to learn how to contribute to our project.

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🎉 Acknowledgments

- Thanks to all the contributors who have helped to build and refine this project.
- Special thanks to open-source projects that made this software possible.

<br><br>

<div align="center">
<div align="center"><p align="center">
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    <a href="mhmmdbdrhmd@gmail.com" style="text-decoration: none;" alt="Email">
        <img src="https://github.com/mhmmdbdrhmd/Data/blob/main/Icons/ICON%20_Black%20-%20GMail.png" width="6%" />
    </a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    <a href="https://github.com/mhmmdbdrhmd" style="text-decoration: none;" alt="GitHub">
        <img src="https://github.com/mhmmdbdrhmd/Data/blob/main/Icons/ICON%20_Black-%20Github.png" width="6%" />
    </a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    <a href="https://www.linkedin.com/in/mohamad-badri-ahmadi-aa2a1a8a?original_referer=https%3A%2F%2Fwww.google.com%2F" style="text-decoration: none;" alt="LinkedIn">
        <img src="https://github.com/mhmmdbdrhmd/Data/blob/main/Icons/ICON%20_Black%20-%20Linkding.png" width="6%" />
    </a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://twitter.com/mhmmdbdrhmd" style="text-decoration: none;" alt="Twitter">
        <img src="https://github.com/mhmmdbdrhmd/Data/blob/main/Icons/ICON%20_Black%20-%20Twitter%20X.png" width="6%"/>
    </a>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</div>
</div>
