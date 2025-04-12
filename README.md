# abstractive-text-summarization
`📌 Objective`
Implement and evaluate abstractive text summarization models using Keras, specifically:

A basic LSTM-based Seq2Seq model.

A Bidirectional LSTM Seq2Seq model.

A Hybrid model with a Bidirectional LSTM encoder and a regular LSTM decoder.

`🧠 Model Architectures`
build_seq2seq_model_with_just_lstm: LSTM encoder + LSTM decoder.

build_seq2seq_model_with_bidirectional_lstm: Bidirectional LSTM encoder + Bidirectional LSTM decoder.

build_hybrid_seq2seq_model: Bidirectional LSTM encoder + LSTM decoder.

`⚙️ Tools & Libraries`
Core: TensorFlow (Keras API)

NLP Preprocessing: contractions, nltk, re, etc.

Visualization: matplotlib, seaborn, wordcloud

Data Handling: pandas, numpy

📂 Data Used`
Two CSV datasets:

news_summary.csv

news_summary_more.csv

After preprocessing, the combined dataset includes cleaned text and summary.

`📌 End of Notebook`
Compares performance of all three models.

Only the first model's trained weights (model, encoder_model, decoder_model) are saved.
