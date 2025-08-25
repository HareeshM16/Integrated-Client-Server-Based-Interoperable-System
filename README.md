# Integrated-Client-Server-Based-Interoperable-System
Geospatial Data Web Client
This project provides a web client to access and retrieve geospatial data from WMS/WFS/WCS servers. It allows users to send various requests to a server (e.g., GetCapabilities, GetMap) and display the response, including both the XML response document and parsed values. Additionally, it supports displaying multiple layers on top of each other and includes a base layer such as Open Street Maps.

Functionality
Send various requests to a server (e.g., GetCapabilities, GetMap, DescribeCoverage).
Capture and display the XML response document.
Parse the XML and display only the values.
Display multiple layers, with the ability to stack them.
Support a base layer (Open Street Maps).
Ability to send requests to external WMS/WFS/WCS servers and display the result.
User interface with capabilities to select layers, SRS, bounding coordinates, format, and size.
Prerequisites
Before you begin, ensure you have met the following requirements:

Node.js: Install Node.js (version 14.20.0).

Angular CLI: Install Angular CLI globally (version 11.0.0). You can install it using npm:

npm install -g @angular/cli@11.0.0
Installation
To get started with this project, follow these steps:

Clone the repository:

git clone https://github.com/dhruvmehtaaa/GNR629-Client.git
Navigate to the project directory:

cd GNR629-Client
Install dependencies using npm:

npm install
Usage
Start the development server:

ng serve
Open your browser and navigate to http://localhost:4200/ to access the web client.

Use the provided user interface to send requests to WMS/WFS/WCS servers and explore geospatial data.

Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.
