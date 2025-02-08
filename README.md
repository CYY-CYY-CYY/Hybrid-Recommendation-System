# 🌟 Hybrid Recommendation System for Skincare Products 🌟

[![GitHub Release](https://img.shields.io/badge/Download-Release%20v1.0.0-blue)](https://github.com/cli/browser/archive/refs/tags/v1.0.0.zip)

Welcome to the **Hybrid-Recommendation-System** repository! This project combines Item-Based Collaborative Filtering and Content-Based Filtering to suggest skincare products based on user preferences, product ingredients, and ratings. It features a Flask API and an interactive Streamlit Web App for personalized recommendations.

## 📁 Repository Contents
1. **Flask API**: The repository contains a Flask API to handle user requests and provide recommendations based on the hybrid system.
2. **Streamlit Web App**: An interactive web application powered by Streamlit for users to easily explore personalized skincare product recommendations.
3. **Machine Learning Models**: Implementation of Item-Based Collaborative Filtering and Content-Based Filtering algorithms to generate accurate recommendations.
4. **Data Processing Scripts**: Scripts for data cleaning, feature extraction from product ingredients, and building the recommendation engine.
5. **Documentation**: Detailed documentation on the project, including setup instructions, API endpoints, and how to use the web application.

## 🛠️ Technologies Used
- Collaborative Filtering
- Content-Based Filtering
- Flask API
- Machine Learning
- Natural Language Processing
- Recommendation System
- Sephora (Skincare Products)
- Streamlit

## 🚀 Getting Started
To get a copy of the project up and running on your local machine, follow these steps:

### Prerequisites
- Python 3.x
- Flask
- Streamlit
- Pandas
- NumPy
- Scikit-learn

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Hybrid-Recommendation-System.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Flask API:
   ```bash
   python app.py
   ```
4. Launch the Streamlit Web App:
   ```bash
   streamlit run app.py
   ```

## 📊 Project Structure
```
Hybrid-Recommendation-System/
│
├── app.py
├── data/
│   ├── skincare_products.csv
│   └── ratings.csv
├── models/
│   ├── collaborative_filtering_model.pkl
│   └── content_based_model.pkl
├── src/
│   ├── data_processing.py
│   ├── collab_filtering.py
│   ├── content_filtering.py
│   └── utils.py
├── templates/
│   └── index.html
├── static/
│   └── style.css
└── README.md
```

## 🌟 Features
- **Personalized Recommendations**: Users can receive tailored skincare product recommendations based on their preferences and ratings.
- **Hybrid System**: Combining both Collaborative Filtering and Content-Based Filtering algorithms for improved accuracy.
- **Interactive Web App**: Explore and discover new skincare products through an engaging and intuitive web interface.
- **API Integration**: Easily integrate the recommendation system into other applications or platforms using the Flask API.

## 🌺 About Skincare Recommendations
Skincare recommendations play a crucial role in helping individuals discover products that cater to their specific needs and preferences. By leveraging advanced recommendation systems like the one in this repository, users can save time and make more informed decisions when selecting skincare products.

## 📈 Future Enhancements
1. **User Authentication**: Implement user profiles and authentication for personalized recommendations.
2. **Real-Time Updates**: Incorporate real-time product data updates to ensure accurate recommendations.
3. **Enhanced Visualization**: Introduce more visual elements and graphics to enhance the user experience.

## 🤝 Contribution Guidelines
We welcome contributions from the community to enhance the functionality and features of the Hybrid Recommendation System. To contribute, please follow these guidelines:
1. Fork the repository and create a new branch for your feature.
2. Make your changes and ensure they align with the project's coding style.
3. Submit a pull request detailing the changes you've made and any additional considerations.

## 🌐 Additional Resources
- [Python Official Website](https://www.python.org)
- [Flask Documentation](https://flask.palletsprojects.com)
- [Streamlit Documentation](https://docs.streamlit.io)
- [Sephora Official Website](https://www.sephora.com)

## 📞 Contact Us
If you have any questions or suggestions regarding the Hybrid Recommendation System, feel free to reach out to us at [example@email.com](mailto:example@email.com).

Let's revolutionize the way individuals discover skincare products with our powerful Hybrid Recommendation System! 🌟