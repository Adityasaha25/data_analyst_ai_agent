# 📊 AI Data Analyst Agent

An intelligent data analysis tool powered by Google's Gemini AI that allows you to analyze CSV files using natural language queries. Simply upload your data, ask questions in plain English, and get AI-generated insights with automatic visualizations.


##  Features

-  **Natural Language Queries**: Ask questions about your data in plain English
-  **Automatic Visualizations**: Generate charts and graphs automatically when relevant
-  **Smart Analysis**: Get AI-powered insights using Google's Gemini models
-  **User-Friendly Interface**: Clean and intuitive Gradio web interface
-  **CSV Support**: Easy upload and analysis of CSV files
-  **Fast Processing**: Quick responses for data exploration

##  Use Cases

- Quick data exploration and summarization
- Trend analysis and pattern detection
- Statistical insights generation
- Data quality assessment
- Visual data representation
- Business intelligence queries

##  Prerequisites

- Python 3.8 or higher
- Google Gemini API key (get it free at [Google AI Studio](https://makersuite.google.com/app/apikey))

##  Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Adityasaha25/ai-data-analyst-agent.git
   cd ai-data-analyst-agent
   ```

2. **Install required packages**
   ```bash
   pip install google-generativeai pandas matplotlib pillow gradio
   ```

3. **Set up your API key**
   - Get your free Gemini API key from [Google AI Studio](https://makersuite.google.com/app/apikey)
   - Open the notebook and replace `YOUR_API_KEY` with your actual API key in Cell 3

##  Usage

### Running in Jupyter Notebook

1. Open the notebook:
   ```bash
   jupyter notebook data_analyst_ai.ipynb
   ```

2. Run all cells sequentially (Cells 1-7)

3. The Gradio interface will launch automatically in your browser

4. Upload a CSV file and start asking questions!

### Example Queries

- "What are the top 5 rows by sales?"
- "Show me a summary of the data"
- "What's the average value of the price column?"
- "Plot the relationship between date and revenue"
- "Are there any missing values in the dataset?"
- "Show me trends over time"

##  Project Structure

```
ai-data-analyst-agent/
│
├── data_analyst_ai.ipynb    # Main Jupyter notebook
├── README.md                 # Project documentation
├── LICENSE                   # MIT License
├── .gitignore               # Git ignore file
└── requirements.txt         # Python dependencies (optional)
```

##  How It Works

1. **Upload**: User uploads a CSV file through the Gradio interface
2. **Query**: User asks a question in natural language
3. **Process**: The system reads the CSV and extracts key information
4. **AI Analysis**: Gemini AI processes the query and data context
5. **Visualize**: If relevant, automatic charts are generated
6. **Display**: Results and visualizations are shown in the interface

##  Configuration

You can customize the following in the notebook:

- **Model Selection**: Automatically uses the first available Gemini model
- **Plot Settings**: Modify figure size, DPI, and styling in Cell 5
- **Interface Theme**: Change Gradio theme in Cell 6
- **Data Preview**: Adjust number of preview rows (default: 20)

##  Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Create a Pull Request

##  Known Issues

- Currently supports only CSV files
- Visualization logic is basic and may not cover all chart types
- Large files may take longer to process

##  Roadmap

- [ ] Support for Excel files (.xlsx, .xls)
- [ ] More sophisticated chart generation
- [ ] Export analysis results
- [ ] Conversation history/memory
- [ ] Multiple file comparison
- [ ] Advanced statistical analysis
- [ ] Custom visualization options
- [ ] Database connectivity

##  License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

##  Acknowledgments

- Google Gemini AI for powerful language models
- Gradio for the excellent UI framework
- The open-source community

##  Contact

For questions or feedback, please open an issue on GitHub.

##  Disclaimer

This tool is for educational and analytical purposes. Always verify critical insights with domain experts and proper statistical analysis.

---

**Made with using Google Gemini AI**
