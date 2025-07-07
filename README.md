# 🎬 YouTube Transcript Backend

A lightweight, Dockerized backend service to fetch YouTube video transcripts using Python. Perfect for AI apps, summarizers, or personal projects that need video content in text form.

## 📂 Project Structure

```

youtube-transcript/
├── .dockerignore
├── .gitignore
├── .python-version
├── Dockerfile
├── README.md
├── main.py
├── pyproject.toml
├── requirements.txt
└── uv.lock

````

## 🛠️ Getting Started

### 🔧 Prerequisites

Make sure you have:
- Python 3.10+
- Docker installed (optional but recommended)

### ⚙️ Installation (Local)

```bash
# Clone the repo
git clone https://github.com/smartcraze/youtube-transcript.git
cd youtube-transcript

# Install dependencies
pip install -r requirements.txt

# Run the app
python main.py
````

### 🐳 Run with Docker

```bash
# Build the Docker image
docker build -t youtube-transcript .

# Run the container
docker run -p 8000:8000 youtube-transcript
```

### Example Request (if using FastAPI)

```bash
GET /transcript?video_id=VIDEO_ID_HERE
```

## 📚 Tech Stack

* **Python**
* **[youtube-transcript-api](https://pypi.org/project/youtube-transcript-api/)**
* **Docker**

