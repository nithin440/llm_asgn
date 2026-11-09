# Botswana IMF Report Analysis

This project analyses Botswana’s 2024 IMF Article IV report using Python, Qwen, MiniLM embeddings and FAISS.

## How to Run

1. Open the notebook in Google Colab.
2. Select a T4 GPU under **Runtime → Change runtime type**.
3. Download the source PDF below and upload it through the Colab Files sidebar.
4. Run all notebook cells in order.

No API key is required. Internet access is needed to download packages and models.

## Source Report

[Download the Botswana 2024 IMF report](https://meetings.imf.org/en/-/media/files/publications/cr/2024/english/1bwaea2024006-print-pdf.pdf)

## Outputs

The notebook generates summaries, indicator JSON, thematic counts, economic trends, RAG answers, evaluation results and a four-panel dashboard.

Results are saved in `outputs/` and packaged as `botswana_results.zip`. Intermediate files are cached in `cache/`.

## Limitations

Some indicators were not extracted, some findings were misclassified, and several judge responses failed validation. Generated results require checking against the source PDF.

## License

The code is released under the MIT License; see `LICENSE`. The IMF report and model weights retain their respective terms.
