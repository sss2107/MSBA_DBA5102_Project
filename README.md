# MSBA DBA5102 Project

NUS MSBA AY 2021/2022 team project on Bitcoin price prediction. The project combines time-series analysis, sentiment analysis, news data, market indicators, and deep learning experiments to study Bitcoin price movement.

## Project Focus

- Bitcoin price prediction
- Time-series analysis
- News and social sentiment analysis
- LSTM / RNN modeling
- Market and blockchain indicator exploration
- Data cleaning and multi-source dataset merging

## Repository Structure

```text
.
├── [Codes]Data_Merging_Processing/     # Data cleaning and merge notebooks/scripts
├── [Codes]Sentiment_Analysis/          # News and Twitter sentiment workflows
├── [Codes]Time_Series_Analysis/        # BTC closing price analysis
├── [Codes]LSTM:RNN/                    # Deep learning price prediction experiments
├── [Datasets]Data_Sources/             # Raw source datasets
├── [Datasets]Data_FINAL/               # Final aggregated datasets
├── Z.Appendix/                         # QR codes and visualization appendix
└── README.md
```

## Data Sources

The repository includes multiple sources used in the analysis, including:

- Bitcoin price data
- Crypto market cap indicators
- Fear and greed index
- Macro / market references such as VIX, oil, silver, gold, and equity index data
- News and Twitter-derived sentiment datasets

## Suggested Workflow

1. Review data sources in `[Datasets]Data_Sources/`
2. Run cleaning and merging notebooks in `[Codes]Data_Merging_Processing/`
3. Explore sentiment workflows in `[Codes]Sentiment_Analysis/`
4. Run baseline time-series analysis in `[Codes]Time_Series_Analysis/`
5. Review LSTM/RNN experiments in `[Codes]LSTM:RNN/`
6. Compare modeling results and document final conclusions

## Team

- Widya Gani Salim
- Felipe Chapa
- Ankit Malhotra
- Wong Cheng An
- Sahil Sharma
- Donghwan Kim

## Notes

This is an academic project repository. For long-term reproducibility, the next useful cleanup would be to add a single environment file, a final report link, and a concise model-results table.

## License

This project is licensed under the terms in [LICENSE](LICENSE).
