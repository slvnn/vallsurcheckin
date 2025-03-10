# QR Code Generator for Check-In at Vallsur Shopping Center

## Overview
This app generates a dynamic QR code that allows users to **Check In at Vallsur Shopping Center** without having to physically go there. The QR code updates every hour, providing a new check-in link with the current date and time.

## Features:
- Generates a QR code that changes every hour.
- The QR code links to a dynamic URL containing the current date and hour.
- Simple and responsive design, suitable for both mobile and desktop devices.

## How It Works
- The QR code points to a URL that contains a string of data formatted as:

vallsur;event;6507;date;[DAY][MONTH][YEAR][HOUR]

- `DAY`, `MONTH`, `YEAR`, and `HOUR` are dynamically updated every hour based on the current time and date.
- The QR code refreshes and points to the updated string as the hour changes.

## How to Use
1. Visit the website.
2. Scan the QR code with your phone.
3. The QR code will take you to a dynamic link for checking in at the shopping center.

## Technologies Used
- HTML, CSS, JavaScript
- QRCode.js for generating QR codes

## Hosting
This app is hosted on **GitHub Pages** and is accessible from the following URL:  
[Your GitHub Pages URL](https://yourusername.github.io/dynamic-qrcode/)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
