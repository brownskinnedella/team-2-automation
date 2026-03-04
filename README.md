#  Redmi 6 Review Analysis Automation

An end-to-end automation pipeline that performs sentiment classification and AI-powered summarization of customer reviews stored in Google Sheets.
The system integrates the Cohere LLM API with Google Sheets to automate review analysis, update structured outputs, and generate visual sentiment insights — eliminating manual review processing.

## Project Overview
- Service account authentication with Google Sheets API
- Automated ingestion of customer review data
- LLM-powered sentiment classification and one-line summarization
- Structured output writing back to the sheet
- Sentiment aggregation and visualization using Matplotlib
  
This design demonstrates API integration, LLM workflow automation, and data reporting in a single pipeline.

## Technologies Used

  - Python

  - gspread

  - Cohere API

  - Matplotlib

  - Google Sheets API

  - OAuth2Client
    

## How to Run

1. Clone the repository.

2.  Install the required Python packages:

```python 
pip install gspread oauth2client cohere matplotlib
```

3. Add your service_account.json credentials file.

4. Replace the Cohere API key with your own in the script.

5. Run the Python script:
```python
   python main.py
   ```

## Project Structure
```css

├── main.py
├── service_account.json
├── README.md
```

## Deliverables

- Updated Google Sheet containing:
- Sentiment classification
- AI-generated summary
- Action-needed indicator
- Automatically generated pie chart showing sentiment distribution
- Structured dataset ready for reporting or decision-making


## Potential Enhancements 

- Batch processing optimization for large datasets
- Deployment as a scheduled cloud function
- Dashboard integration (Power BI or Streamlit)
- Persistent logging and error monitoring
- Support for multi-product sentiment tracking

## Author
Emmanuella Osuala
Data Analyst | Automation & LLM Workflow Design
