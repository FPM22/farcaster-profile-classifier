# Farcaster Profile Classifier

This Colab-based Python tool uses OpenAI GPT-4 to classify Farcaster user bios into two categories:
- `category`: Founder, Employee, Active Community Member, or N/A.
- `commercial_category`: Business, Community, or N/A.

## 🚀 Features

- Reads data from a Google Sheet (via API).
- Filters rows that still need classification.
- Uses OpenAI API to suggest categories based on user bios.
- Updates the sheet with the new classifications.
- Optionally backs up the data as CSV.

## 📦 Requirements

- Python 3.x
- Google Colab or Jupyter
- OpenAI API key
- Google Sheets API credentials

Install dependencies (in Colab):

```python
!pip install --upgrade openai gspread oauth2client
