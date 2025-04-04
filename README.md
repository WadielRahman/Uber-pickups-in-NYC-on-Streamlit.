# 🚖 Uber Pickups in NYC

A **Streamlit** app that visualizes Uber pickups in **New York City** using real-world data. This interactive dashboard allows users to explore pickup patterns by hour and visualize them on a map.

## 📌 Features
- 📊 **Histogram** of Uber pickups by hour
- 🗺️ **Interactive Map** of pickups at a selected hour
- ✅ **Toggle Raw Data** to inspect the dataset
- 🎛 **Slider** to filter pickups by hour

## 🛠️ Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/uber-pickups-nyc.git
   cd uber-pickups-nyc
   ```
2. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```sh
   streamlit run app.py
   ```

## 📂 Project Structure
```
├── app.py             # Main Streamlit app
├── requirements.txt   # Dependencies
├── README.md          # Project documentation
```

## 📊 Data Source
The dataset used in this project is from [Streamlit's demo Uber dataset](https://s3-us-west-2.amazonaws.com/streamlit-demo-data/uber-raw-data-sep14.csv.gz).

## 🎯 Future Improvements
- Add **date filtering** to explore different days.
- Use **Plotly/Altair** for interactive visualizations.
- Optimize performance for larger datasets.

## 🤝 Contributing
Pull requests are welcome! Feel free to open an issue for suggestions.

## 📜 License
This project is open-source under the MIT License.

---
🚀 **Built with Streamlit & ❤️**

