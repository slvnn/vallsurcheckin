# QR Code Generator for Check-In at Vallsur Shopping Center

## Overview
This app generates a dynamic QR code that allows users to **Check In at Vallsur Shopping Center** without having to physically go there. The QR code updates every hour, providing a new check-in link with the current date and time.

## Features:
- Generates a QR code that changes every hour.
- The QR code works like the one in the mall.

## How It Works
- The QR code points to a URL that contains a string of data formatted as:

```
vallsur;event;6507;date;[DAY][MONTH][YEAR][HOUR]
```

- `DAY`, `MONTH`, `YEAR`, and `HOUR` are dynamically updated every hour based on the current time and date.
- The QR code refreshes and points to the updated string as the hour changes.

## How to Use
1. Visit the website.
2. Scan the QR code with the Vallsur APP.
3. 20 points will be added to your balance

## Technologies Used
- HTML, CSS, JavaScript
- QRCode.js for generating QR codes

## Hosting
This app is hosted on **GitHub Pages** and is accessible from the following URL:  
[Vallsur Check In](https://slvnn.github.io/vallsurcheckin/)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
