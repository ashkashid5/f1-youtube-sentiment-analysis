# F1 YouTube Sentiment Analysis (Mini Project)

I analyze YouTube videos related to Formula 1 to measure driver mentions, sentiment, and engagement using the YouTube Data API and NLP.

## Objective
- Analyze driver mentions across selected videos
- Estimate sentiment of comments
- Compare sentiment with engagement metrics (views/likes/comments)

## Files
- `main.ipynb` — pipeline notebook
- `Race_Schedule.csv` — input reference
- `output_f1_video_summary.csv` — video summary output
- `output_f1_driver_mentions.csv` — driver mentions output
- `output_f1_driver_sentiment_engagement.csv` — sentiment + engagement output
- `Mini Project Report.pdf` — report (optional)

## Setup & Run
1) Create venv:
   - Windows: `py -m venv .venv`
   - Mac/Linux: `python3 -m venv .venv`

2) Install dependencies:
   - `pip install -r requirements.txt`

3) Add API key:
   - Create `.env` (see `.env.example`)

4) Run:
   - Open `main.ipynb` and Run All cells

## Notes
- API quotas may limit comment/video pulls depending on your usage.
