
# 🥄 Smart Spoon: AI-Powered Food Analysis & Dietary Recommendations

## Introduction

**Smart Spoon** is an AI-driven application that analyzes food images to provide personalized dietary recommendations. By leveraging computer vision and user demographic data, it offers insights into the nutritional aspects of various dishes, catering especially to individuals with specific health conditions like hypertension or kidney disease.

---

## Overview

This project is built using:

* **Python**: Core programming language for the application logic.
* **NumPy & Pandas**: For data manipulation and analysis.
* **Pillow (PIL)**: For image processing tasks.
* **Google Colab**: To facilitate user interaction and file handling.

Key Features:

* Upload or capture food images for analysis.
* Identify dishes based on color profiles.
* Provide dietary recommendations based on user demographics and health conditions.
* Suggest taste improvements based on user feedback.

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/smart-spoon.git
cd smart-spoon
```

### 2. Set Up a Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

*Note: If you're using Google Colab, many of these dependencies are pre-installed.*

---

## Setup

1. **Open the Notebook**: Launch the `smart_spoon.ipynb` notebook in Google Colab or your local Jupyter environment.

2. **Run the Cells**: Execute each cell sequentially to initialize the application.

3. **Provide Inputs**:

   * Upload or capture a food image when prompted.
   * Enter your age, gender, frequency of restaurant visits, and any medical conditions.

---

## Upload Files (Optional)

If you have an Excel or CSV file containing user demographic data, you can upload it when prompted. The file should contain the following columns:

* `Age`
* `Gender`
* `Medical Condition`
* `Restaurant Frequency`

The application will analyze this data to provide aggregated insights.

---

## How to Run the Application

After setting up:

1. **Start the Application**: Run the `smart_spoon_system()` function.

2. **Interact**:

   * Choose to upload or capture a food image.
   * Provide the requested demographic information.
   * Review the identified dish and its nutritional details.
   * Offer feedback on the taste, and receive suggestions for improvement.

---

## Output

Upon completion, the application will display:

* The uploaded food image.
* Identified dish name.
* Main ingredients.
* Typical salt content and spice level.
* Personalized dietary recommendations.
* Taste improvement suggestions based on your feedback.

---

## Acknowledgments

* **OpenAI**: For providing the foundational language models.
* **Google Colab**: For facilitating an interactive development environment.
* **Pandas & NumPy**: For efficient data handling and analysis.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## About

Developed by [Somesh-Gowda](https://github.com/Somesh-Gowda), this project aims to combine AI and nutrition to promote healthier eating habits.


