# GeoNames API Integration Project

This project is a frontend + backend application demonstrating the use of selected APIs from [GeoNames.org](http://www.geonames.org/).

## 🌍 Features

- 🔍 **Find Nearby Place Name**: Get the nearest populated location using latitude and longitude.
- 🏳️ **Country Info**: Fetch country data such as population, area, etc.
- 📌 **Search**: Find places by name or keyword.

## 🧰 Technologies Used

- HTML5
- CSS3
- JavaScript / jQuery
- PHP
- JSONP (as a fallback for server-side cURL limitations)

## 🚀 Live Demo

[Click to view the live site](http://ppeliance.space)

## 🛠️ Setup Instructions

To run locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
Upload to a PHP-enabled server (e.g. InfinityFree, FreeHostia, etc.)

Ensure the following files are included:

index.html (or index.php)

api.php

app.js

style.css

favicon.png

⚠️ Hosting Notes
Some free hosting services like FreeHostia may block cURL in the free tier. In this case, the application includes a fallback using JSONP to fetch data from GeoNames directly in the browser.

📂 Project Structure
pgsql
Copy
Edit
/
│
├── index.html / index.php
├── api.php
├── app.js
├── style.css
├── favicon.png
└── README.md
👤 Author
Pelumi Otegbola
Email: ppeliance@gmail.com
GitHub: pellypepper
