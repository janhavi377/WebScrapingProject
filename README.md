# WebScrapingProject
This project extracts video and channel data from YouTube using the YouTube Data API.


## ⚠️ Disclaimer

This project uses the official YouTube Data API to collect **publicly available video and channel statistics** from YouTube for educational purposes. No private or sensitive data is collected or shared.
The data analyzed here is from public channels and videos, specifically for research, learning, and visualization purposes.


"A Educational Python project to fetch, analyze, and visualize YouTube channel data using the YouTube Data API."
🧰 Technologies Used :
🐍 Python 3.x
📦 Pandas
📊 Seaborn & Matplotlib
🌐 YouTube Data API v3
🔐 python-dotenv (for secure API key storage)
🧪 Jupyter Notebook (optional)


🚀 Features :
📡 Fetch channel statistics (subscribers, views, total videos)
🎥 Extract video-level details from upload playlist
📈 Analyze most viewed or liked videos
📊 Visualize top videos using bar plots
✅ Clean and convert YouTube API responses into structured DataFrames
🔐 API key handled securely via .env file

Folder Structure :
youtube-data-analysis/
│
├── data/                       # Stores sample or exported CSVs
├── src/                        # Source scripts for API calls and analysis
│   ├── channel_stats.py
│   ├── video_details.py
├── .env                        # API key file (not uploaded)
├── .gitignore                  # Prevents uploading sensitive files
├── requirements.txt            # Dependencies
├── README.md                   # Project documentation
└── notebook.ipynb              # Optional: Jupyter notebook version




