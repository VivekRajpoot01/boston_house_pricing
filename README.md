# Boston House Pricing Prediction

## Overview
This project predicts house prices in Boston using multiple regression techniques. The model is trained on the **Boston Housing Dataset** and deployed as a web application, allowing users to input features and get price predictions.

## Live Demo
[Click here to access the live project](https://boston-house-pricing2.onrender.com/)

## Tech Stack
- **Programming Language:** Python
- **Libraries:** Scikit-Learn, Pandas, NumPy, Matplotlib
- **Framework:** Flask
- **Deployment:** Render
- **Containerization:** Docker

## Features
- Predicts house prices based on user inputs.
- Uses a trained **regression model** for accurate predictions.
- Web-based interface for easy access to predictions.
- Dockerized for seamless deployment.

## Installation
To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/VivekRajpoot01/boston-house-pricing.git
   cd boston-house-pricing
   ```
2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Flask app:
   ```bash
   python app.py
   ```
5. Open your browser and go to `http://127.0.0.1:5000/`.

## Deployment
The project is deployed on Render. To deploy your own version:
- Use **Docker** to containerize the app.
- Push the image to a container registry.
- Deploy it on **Render**, **Koyeb**, or any cloud provider.

## Contributing
Feel free to open issues and submit pull requests to improve the project!

## License
This project is licensed under the **MIT License**.

## Author
[Vivek Rajpoot](https://github.com/VivekRajpoot01)
