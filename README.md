# 🌾 Crop Price Prediction Using Random Forest

This project applies supervised machine learning techniques—specifically **Random Forest** and **Decision Trees**—to predict agricultural crop prices using historical data.

## 📌 Objective

The goal is to build a predictive system that accurately forecasts crop prices by analyzing a dataset spanning five years. The project considers external influencing factors such as:
- Market demand
- Government policies
- Geopolitical events
- Meteorological conditions (rainfall, temperature)

## 🧠 Machine Learning Techniques

- **Algorithms Used**: Random Forest, Decision Tree
- **Preprocessing**: Data cleaning and feature engineering using a custom preprocessing pipeline
- **Model Storage**: Serialized using `joblib` as `.pkl` files

## 📂 Project Structure

```
Crop-Price-Prediction-Using-Random-Forest/
├── README.md
├── .gitignore
└── src/
    ├── app.py               # Application entry point
    ├── requirements.txt     # Python dependencies
    ├── preprocessor.pkl     # Preprocessing pipeline
    ├── *.pkl                # Trained models for different crops
```

## 🛠️ How to Run

1. **Install requirements**:
   ```bash
   pip install -r requirements.txt
   ```

2. **Run the app**:
   ```bash
   python src/app.py
   ```

## 📽 Demo & Resources

- [📄 Research Paper](https://internationalpubls.com/index.php/cana/article/view/762)
- [📹 Project Demo (YouTube)](https://www.youtube.com/watch?v=AkiO8RtKaps)

## 🤝 Contributions

Developed as part of an academic research initiative focused on enhancing predictive tools in agriculture.

## 📃 License

This project is for educational and research use.
