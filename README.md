
# Cinematic Story Generator 🎬

A simple command-line tool to generate cinematic story outlines and scene prompts
(English + Persian ready).

## Features

- Asks you for:
  - main character
  - setting (place)
  - mood (emotional tone)
  - story length (short / medium / long)
- Creates:
  - logline (one-line hook)
  - 5-step emotional story structure
  - scene prompts for AI video tools (Gemini, Grok, Runway, etc.)

## How to Use

```bash
# 1. Create virtual environment (optional)
python -m venv venv
source venv/bin/activate  # on Windows: venv\Scripts\activate

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the generator
python src/main.py
