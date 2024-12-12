# 🌾 Crop Detector/Recommendation System

A **machine learning-based web application** designed to recommend the most suitable crop to grow based on soil and environmental factors. This project leverages a **RandomForestClassifier** model, achieving an impressive **accuracy of 99.31%**. Developed in **PyCharm**, the project integrates machine learning with a web interface using **Flask**, providing a seamless and user-friendly experience.

---

## 🚀 Features

- **Highly Accurate ML Model**: Built with a RandomForestClassifier to provide precise crop recommendations.  
- **Integrated Web Application**: Developed using Flask, HTML, and CSS for a clean and simple interface.  
- **User-Friendly Inputs**: Accepts seven critical input factors and outputs the most suitable crop.  

---

## 🔧 Tech Stack

- **Machine Learning**: RandomForestClassifier, Scikit-learn, Pandas, NumPy  
- **Backend**: Flask  
- **Frontend**: HTML, CSS  
- **Development Environment**: PyCharm  

---

## 📊 Inputs

The system requires the following seven factors as input:  

1. **Nitrogen (N)**: Amount of nitrogen in the soil.  
2. **Phosphorus (P)**: Amount of phosphorus in the soil.  
3. **Potassium (K)**: Amount of potassium in the soil.  
4. **Temperature**: Current temperature of the environment (in °C).  
5. **Humidity**: Humidity level of the environment (in %).  
6. **pH**: pH level of the soil.  
7. **Rainfall**: Average rainfall (in mm).  

---

## 🎯 Output

Based on the provided inputs, the application predicts the **most suitable crop** for the given conditions. This helps farmers make informed decisions to maximize yield and sustainability.

---

## 🖥️ How to Run

Follow these steps to set up and run the project on your local machine:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/crop-detector.git
   cd crop-detector
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Flask application:
   ```bash
   python app.py
   ```

4. Open your browser and navigate to `http://127.0.0.1:5000`.

---

## 📊 Model Accuracy

- The **RandomForestClassifier** achieved an outstanding **accuracy of 99.31%** during testing, making it highly reliable for predicting crop recommendations.

---

## 📂 Project Structure

```
crop-detector/
├── static/
│   ├── style.css           # CSS for styling the web interface
│   └── farm.jpg            # Placeholder image
├── templates/
│   └── index.html          # Main HTML file
├── app.py                  # Flask application
├── model.py                # Machine learning model
├── Crop_recommendation.csv # Dataset used for training and testing
├── requirements.txt        # Dependencies
└── README.md               # Project documentation
```

---

## 🌐 Demo

To enhance your `README.md`, consider adding screenshots or a hosted demo link (if applicable). Place the images in the `static` folder and reference them here using markdown syntax:

```markdown
![Web Interface Screenshot](static/demo_screenshot.png)
```

---

## 🌱 Dataset

The model is trained on a dataset containing environmental and soil factors corresponding to various crops. The dataset includes:

- **Columns**: Nitrogen, Phosphorus, Potassium, Temperature, Humidity, pH, Rainfall, and Crop Name.
- **Rows**: Multiple entries covering diverse agricultural conditions.

---

## 🏆 Future Enhancements

- **Integration with Real-Time Weather APIs**: Use live weather data for dynamic predictions.
- **Improved User Interface**: Enhance the design with frameworks like Bootstrap or React.
- **Multilingual Support**: Add support for multiple languages to help farmers worldwide.
- **Mobile-Friendly Application**: Adapt the UI for mobile devices.

---

## 🔧 Installation Requirements

- **Python**: Version 3.7 or higher  
- **Libraries**: Listed in `requirements.txt` (install via `pip install -r requirements.txt`)  

---

## 📖 License

This project is licensed under the [MIT License](LICENSE). Feel free to modify and use it as per your requirements.

---

## 📚 Acknowledgements

- The **RandomForestClassifier** model was trained using Scikit-learn.  
- Dataset sourced from [XYZ source or mention "self-collected data"].  
- Inspired by the goal of improving agricultural decision-making through technology.  

---

Feel free to customize the placeholders (e.g., `your-username`, dataset source, etc.) to match your project specifics. Let me know if you'd like help refining further!
