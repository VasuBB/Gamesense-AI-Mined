# Gameplay Analyzer 🎮

An advanced gameplay analysis tool that processes Valorant gameplay videos to provide comprehensive insights, statistics, and visualizations.


![Image Description](https://res.cloudinary.com/dogfmhpfc/image/upload/v1738416201/Blank_diagram_1_ytcaui.png)



## 🌟 Features

### 1. Real-time Game Analysis
- Live health and ammo monitoring
- Real-time kill detection and analysis
- Dynamic performance metrics visualization
- Player position tracking

### 2. Post-Game Statistics
- Detailed match summary
- Kill/Death analysis
- Round-by-round breakdown
- Player performance metrics
- Weapon usage statistics

### 3. AI-Powered Analysis
- Natural language interaction with game data
- AI-generated match summaries
- Intelligent highlight detection
- Context-aware gameplay insights

### 4. Visual Analytics
- Player movement heatmaps
- Interactive data visualizations
- Custom highlight reel generation
- Round performance graphs

### 5. Player Insights
- Weapon efficiency analysis
- Position and movement patterns
- Engagement behavior analysis
- Health management tracking

## 🔧 Technical Requirements

- Python 3.8+
- OpenCV
- PyTorch
- Streamlit
- EasyOCR
- Moviepy
- Google GenerativeAI
- LangChain
- YOLO (Ultralytics)

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/valorant-gameplay-analyzer.git
cd valorant-gameplay-analyzer
```

2. Install necessary required packages

3. Set up API keys:
```python
GOOGLE_API_KEY=your_google_api_key
GROQ_API_KEY=your_groq_api_key
```

## 🚀 Usage

1. Start the Streamlit application:
```bash
streamlit run stream.py --server.enableXsrfProtection false
```

2. Navigate to different analysis modules:
   - Real-time Inference
   - Overall Statistics
   - User Chatbot
   - Highlight Generator
   - Heatmap Generation

3. Upload your gameplay video and map (if required) to begin analysis.

## 📊 Available Analysis Modules

### Real-time Inference
- Live gameplay monitoring
- Kill detection
- Health and ammo tracking
- Real-time performance metrics

### Overall Statistics
- Match summary
- Player performance metrics
- Round analysis
- Kill/Death statistics

### AI Chatbot
- Query match data
- Get specific gameplay insights
- Analyze specific moments
- Strategic recommendations

### Highlight Generator
- Automatic highlight detection
- Custom highlight compilation
- Important moment identification
- Transition effects

### Heatmap Generation
- Player position visualization
- Movement pattern analysis
- Strategic position insights
- Map control analysis

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- YOLO model for object detection
- Streamlit for the web interface
- Google's Generative AI for gameplay analysis
- LangChain for natural language processing
- OpenCV for video processing

## Note

This tool is designed for educational and analytical purposes. It is not affiliated with Riot Games or Valorant.
