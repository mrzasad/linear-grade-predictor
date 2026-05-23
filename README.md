# 📚 Student Study Hours vs. Marks Predictor

A modern Streamlit web application that predicts student scores based on study hours using simple linear regression. This educational tool helps students, teachers, and researchers visualize the relationship between study time and academic performance.

## ✨ Features

- **Interactive Data Analysis**: Upload your own dataset or use the sample data
- **Real-time Predictions**: Slider to predict scores for any number of study hours
- **Comprehensive Visualizations**: Professional charts showing regression analysis
- **Model Evaluation Metrics**: MSE, R-squared, and confidence intervals
- **Detailed Residual Analysis**: View prediction errors for each data point
- **Downloadable Results**: Export predictions as CSV for further analysis
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## 📦 Installation

1. **Clone the repository**:
```bash
git clone https://github.com/your-username/modern.git
cd modern
```

2. **Install the required dependencies**:
```bash
pip install -r requirements.txt
```

3. **Run the Streamlit application**:
```bash
streamlit run app.py
```

## 📝 Requirements

- Python 3.7+
- Streamlit 1.20+
- Pandas 1.5+
- NumPy 1.24+
- scikit-learn 1.2+
- Matplotlib 3.7+

## 🖥️ Usage

1. **Launch the application** by running `streamlit run app.py`
2. **Upload your data** (CSV format with "Hours" and "Scores" columns) or use sample data
3. **Explore the analysis**:
   - View data statistics and visualizations
   - Adjust the slider to predict scores for different study hours
   - Examine detailed prediction results in the expandable section
4. **Download results** using the CSV download button

## 🗂️ Project Structure

```
modern/
├── app.py                # Main Streamlit application
├── requirements.txt      # Python dependencies
├── README.md             # Project documentation
└── sample_data/          # Sample dataset
    └── scores.csv
```

## 🌟 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgements

- [Streamlit](https://streamlit.io/) - For the amazing framework
- [scikit-learn](https://scikit-learn.org/) - For the machine learning implementation
- [Matplotlib](https://matplotlib.org/) - For beautiful visualizations

---

> **Note**: This application is designed for educational purposes to demonstrate simple linear regression concepts. Actual student performance depends on many factors beyond study hours.

---

<img width="1882" height="841" alt="Screenshot 2026-05-18 033440" src="https://github.com/user-attachments/assets/9b2733d2-b400-476a-85ce-1f0fc0a8eb15" />
<img width="1900" height="780" alt="Screenshot 2026-05-18 033557" src="https://github.com/user-attachments/assets/13a5284c-4ee5-4fe9-acc7-a4fa7e706ed1" />
<img width="1835" height="846" alt="Screenshot 2026-05-18 033545" src="https://github.com/user-attachments/assets/9c8fc43a-828d-4d4e-9e8e-39eafe5c3847" />
<img width="1837" height="790" alt="Screenshot 2026-05-18 033527" src="https://github.com/user-attachments/assets/37b9008a-1c3d-48c2-ad6c-597753f9a9ce" />
<img width="1863" height="682" alt="Screenshot 2026-05-18 033506" src="https://github.com/user-attachments/assets/5988cb20-4112-48de-afc9-bb0366d9deee" />


Made with ❤️ for students | Project: modern
