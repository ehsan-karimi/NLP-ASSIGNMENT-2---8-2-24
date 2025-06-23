# Assignment 2 – Hierarchical Style-Based Summarization

This project implements a hierarchical summarization system that summarizes a given input text **in the style of another reference text**, using Python and NLTK. It handles both short and long documents by recursively summarizing text chunks until the summary fits within a specified context window (default 4000 tokens).

## ✅ Features
- Frequency-based extractive summarization
- Token-based chunking and slicing
- Hierarchical summarization loop for long documents
- Proportional context allocation based on document size
- Saves summarized input, style, and a final query prompt

## 📁 Files
- `input.txt`: Main document to summarize
- `style.txt`: Document whose style is to be imitated
- `input_summary.txt`: Final summary of the input text
- `style_summary.txt`: Final summary of the style reference
- `final_query.txt`: Final prompt that combines both summaries
