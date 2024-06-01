# GitHub Visualization

In this project, I use GitHub’s API to request information about Python projects on the site and generate an interactive visualization of the relative popularity of these projects using Plotly. This project provides insights into the popularity and trends of Python projects on GitHub.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Credits](#credits)

## Introduction

The GitHub Visualization project leverages GitHub’s API to gather data about Python projects and visualize their popularity. Using Plotly, I create interactive visualizations that highlight key metrics, helping users understand trends and the relative popularity of different projects.

## Features

- Fetch data from GitHub’s API about Python projects.
- Generate interactive visualizations using Plotly.
- Analyze and compare the popularity of various Python projects.

## Installation

To get started with the GitHub Visualization project, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/github-visualization.git
   ```

2. Navigate to the project directory:

   ```bash
   cd github-visualization
   ```

3. Create a virtual environment:

   ```bash
   python3 -m venv venv
   ```

4. Activate the virtual environment:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

5. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To run the GitHub data fetching script and generate the interactive visualization, use the following command:

```bash
python github_visualization.py
```

The resulting plot will be displayed in your browser, showcasing the relative popularity of Python projects on GitHub.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License.

## Credits

The GitHub Visualization project was created by Alexis Gonzalez. Special thanks to Eric Matthes for his book "Python Crash Course," which provided the foundation for this project.
