# Euro 2024 Shot Map 🎯⚽

An interactive web application built with Streamlit that visualizes shot locations from the UEFA Euro 2024 tournament. Filter by team or player to analyze shot patterns and goal conversions on an interactive football pitch.

## 🎥 Demo

**Live App:** [Euro 2024 Shot Map](https://siddharth107-mlops-lab1-streamlit-euro2024app-stetg3.streamlit.app/)

**Video Walkthrough:** [Loom Demo](https://www.loom.com/share/c2353c5da5d34e0e87341f1da557ec69)

## 📸 Screenshots

### Team View - Belgium's Shot Map
![Belgium Shot Map](https://via.placeholder.com/800x400?text=Belgium+Shot+Map)
*Visualization of all shots taken by Belgium during Euro 2024*

### Interactive Pitch Visualization
![Pitch Visualization](https://via.placeholder.com/800x400?text=Interactive+Football+Pitch)
*Goals marked in green, missed shots in hollow circles*

## ✨ Features

- **Team Filtering**: Select any team that participated in Euro 2024
- **Player Filtering**: Drill down to individual player shot maps
- **Interactive Visualization**: 
  - Shot locations marked on a regulation football pitch
  - Goals highlighted in green
  - Missed shots shown as hollow circles
  - Shot size indicates attempt type or distance
- **Real-time Data**: Based on actual Euro 2024 match statistics

## 🛠️ Tech Stack

- **Frontend Framework**: [Streamlit](https://streamlit.io/)
- **Data Processing**: Pandas
- **Visualization**: 
  - [mplsoccer](https://mplsoccer.readthedocs.io/) - Football pitch drawing library
  - Matplotlib - Core plotting functionality
- **Deployment**: Streamlit Cloud

## 📦 Installation

### Prerequisites
- Python 3.8 or higher
- pip package manager

### Local Setup

1. **Clone the repository**
```bash
git clone https://github.com/SIDDHARTH107/MLOps_Lab1_Streamlit.git
cd MLOps_Lab1_Streamlit/Euro2024
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Run the application**
```bash
streamlit run app.py
```

4. **Access the app**
Open your browser and navigate to `http://localhost:8501`

## 📂 Project Structure

```
MLOps_Lab1_Streamlit/
├── Euro2024/
│   ├── app.py                      # Main Streamlit application
│   ├── euros_2024_shot_map.csv    # Euro 2024 shot data
│   ├── requirements.txt            # Python dependencies
│   └── file1.txt                   # Additional notes
└── README.md                       # Project documentation
```

## 📊 Data Source

The shot map data includes:
- Shot coordinates (x, y positions on pitch)
- Player names and team affiliations
- Shot outcomes (goal/miss)
- Match context and timestamps

*Data collected from Euro 2024 tournament matches*

## 🚀 Usage

1. **Select a Team**: Use the dropdown to choose from Euro 2024 participating teams
2. **Filter by Player** (Optional): Narrow down to a specific player's shots
3. **Analyze Patterns**: 
   - Identify shooting zones
   - Compare conversion rates
   - Study team tactics and player positioning

## 🎓 Academic Context

This project was developed as part of **MLOps Lab 1** coursework at Northeastern University, demonstrating:
- Data visualization techniques
- Web application development with Streamlit
- Cloud deployment workflows
- Sports analytics and data storytelling

## 🔧 Dependencies

```txt
mplsoccer
streamlit
pandas
matplotlib
numpy
```

## 🌐 Deployment

The application is deployed on **Streamlit Cloud** with continuous deployment from the GitHub repository.

**Deployment URL**: https://siddharth107-mlops-lab1-streamlit-euro2024app-stetg3.streamlit.app/

### Deployment Configuration
- **Main file**: `Euro2024/app.py`
- **Python version**: 3.13.11
- **Branch**: `main`

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/SIDDHARTH107/MLOps_Lab1_Streamlit/issues).

## 👨‍💻 Author

**Siddharth Hindurao**
- GitHub: [@SIDDHARTH107](https://github.com/SIDDHARTH107)
- University: Northeastern University
- Program: Master's in Data Analytics Engineering

## 📝 License

This project is created for educational purposes as part of MLOps coursework.

## 🙏 Acknowledgments

- **mplsoccer** library for football pitch visualization tools
- **Streamlit** for the intuitive web framework
- UEFA Euro 2024 for providing the tournament data
- Northeastern University MLOps course instructors

## 📈 Future Enhancements

- [ ] Add heatmap visualization for shot density
- [ ] Include expected goals (xG) metrics
- [ ] Compare multiple players/teams side-by-side
- [ ] Add temporal analysis (shots over tournament progression)
- [ ] Export visualization as images
- [ ] Mobile-responsive design improvements

---

**⭐ If you find this project useful, please consider giving it a star!**

*Last Updated: January 2026*
