# Insurance Premium Prediction

A simple web application to predict insurance premiums based on user-provided data. This project uses a machine learning model to estimate the insurance cost.

---

## 📜 Description

This project is a web application that predicts insurance premiums. Users can input their information, and the application will use a pre-trained machine learning model to provide an estimated insurance premium. The application is containerized using Docker for easy deployment.

---

## ✨ Features

* **Premium Prediction:** Get an estimate of your insurance premium.
* **Web Interface:** Easy-to-use web interface for user input.
* **Dockerized:** The application is containerized for easy setup and deployment.

---

## 🛠️ Technologies Used

* **Python:** The core programming language for the application.
* **Docker:** For containerizing the application.
* **Scikit-learn:** For building the machine learning model.
* **Pandas:** For data manipulation and analysis.
* **Flask/FastAPI:** (Assumed, based on `app.py`) For creating the web application.

---

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

* Python 3.x
* Docker

### Installation

1.  **Clone the repo**
    ```sh
    git clone [https://github.com/rakesh15092002/Insurance_Premium_Prediction.git](https://github.com/rakesh15092002/Insurance_Premium_Prediction.git)
    ```
2.  **Navigate to the project directory**
    ```sh
    cd Insurance_Premium_Prediction
    ```
3.  **Install Python packages**
    ```sh
    pip install -r requirements.txt
    ```

---

## ▶️ Usage

### Running the application with Python

1.  **Run the application**
    ```sh
    python app.py
    ```
2.  Open your browser and go to `http://localhost:5000` (or the port specified in the application).

### Running the application with Docker

1.  **Build the Docker image**
    ```sh
    docker build -t insurance-premium-prediction .
    ```
2.  **Run the Docker container**
    ```sh
    docker run -p 5000:5000 insurance-premium-prediction
    ```
3.  Open your browser and go to `http://localhost:5000`.

---

## 📂 File Structure
