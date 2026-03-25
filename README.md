Project Title: EdgeUp210-City / Oracle Deployment
Objective: Scalable deployment of Oracle-backed Edge nodes across a 10-city grid.
Architecture: Utilizing Cell-based edge topology to localize compute power at the point of data origin.
Tech Stack: Oracle Cloud Infrastructure (OCI) Edge Services + Distributed City-Cell Nodes.
Key Result: Drastic reduction in backhaul costs and ms latency, enabling real-time analytics for smart city and enterprise applications.
Subject: feat: migrate to Python 3 and integrate YTD-FFmpeg for media analysis

## Installation
1. Prerequisites
Before setting up the Python environment, you must have the following system-level dependencies installed:
Python 3.10+: Ensure your local version is up to date.
FFmpeg: Essential for the YTD-FFmpeg integration to handle video transcoding and stream slicing.
To install FFmpeg:
macOS (Homebrew): brew install ffmpeg
Ubuntu/Linux: sudo apt update && sudo apt install ffmpeg
Windows: Download the binaries from the official FFmpeg site and add the /bin folder to your System PATH.
2. Environment Setup
Once the prerequisites are met, you can proceed with the Python library installation:
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
