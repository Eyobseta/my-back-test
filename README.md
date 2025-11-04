# My BackTest App

![Project Status](https://img.shields.io/badge/status-in%20progress-yellow)
![Language](https://img.shields.io/badge/language-JavaScript-blue)
![Issues](https://img.shields.io/github/issues/Eyobseta/my-back-test)
![Forks](https://img.shields.io/github/forks/Eyobseta/my-back-test)
![Stars](https://img.shields.io/github/stars/Eyobseta/my-back-test)
![License](https://img.shields.io/badge/license-MIT-green)

A **web-based tool for FX traders** to track strategies, manage data, maintain checklists, and organize research. Integrated with brokers via API for seamless trade management.

---

## Features
- Track and manage trading strategies
- Store research and trade data
- Maintain checklists for trades
- API integration with brokers
- Clean, organized UI for ease of use

---

## Project Structure
```
my-back-test/
├─ pages/          # HTML pages
│   ├─ index.html
│   ├─ dashboard.html
│   └─ trade.html
├─ css/            # Stylesheets
│   ├─ main.css
│   └─ dashboard.css
├─ js/             # JavaScript files
│   ├─ app.js
│   ├─ api.js       # Broker API integration
│   └─ utils.js     # Utility functions
├─ assets/         # Images, fonts, icons
│   ├─ images/
│   │   └─ logo.png
│   └─ fonts/
│       └─ roboto.ttf
├─ docs/           # Screenshots, GIFs, diagrams
├─ README.md       # This file
└─ .gitignore      # Git ignore

```
## Getting Started

Follow these steps to set up and run the project locally.

1. Installation
    ```bash
      git clone https://github.com/Eyobseta/my-back-test.git
      cd my-back-test
    ```
2. Open the Project

     - Open pages/index.html in your browser to see the app.

     - Edit files in js/ or css/ to customize functionality and styling.
3. API Setup

    - Configure your broker API in js/api.js.

    - Replace placeholders with your API keys or endpoints:
      ```javascript
          const brokerAPI = "YOUR_BROKER_API_KEY_HERE";
      ```.
4. Screenshots / Demo GIFs

    - Place images or GIFs of your app in the docs/ folder.

    - Embed them in the README for visual demonstration:
          ![Dashboard](docs/dashboard.png)
          ![Trade Checklist](docs/checklist.gif).

## Usage

  - Open HTML pages in the browser.

  - Track strategies, maintain checklists, and view research.

  - API integration enables live broker data and trade execution.

## Contributing

  Contributions are welcome!

  1. Fork the repository

  2. Create a feature branch:
      ```
          git checkout -b feature-name
      ```
     
  3. Commit changes:
      ```
          git commit -m "Add feature"
      ```
  4. Push the branch:
      ```
          git push origin feature-name
      ```
  5. Create a Pull Request  

## Notes

   - Designed for FX traders, but easily extendable for other financial markets.

   - Keep all assets organized in assets/ for scalability.

   - Use descriptive commit messages for version control.

## Optional Enhancements

  - Add animated GIFs to show app usage.

  - Include API documentation or links for collaborators.

  - Add license badges (already included) for clarity.   

## License

This project is licensed under the MIT License:


```
MIT License

Copyright (c) 2025 Eyob Seta

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
