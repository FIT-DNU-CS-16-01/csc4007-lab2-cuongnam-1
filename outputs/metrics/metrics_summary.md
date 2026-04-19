# Metrics Summary
- dataset: imdb
- vectorizer: tfidf
- model: logreg
- val_accuracy: 0.9076
- val_macro_f1: 0.9076
- test_accuracy: 0.9068
- test_macro_f1: 0.9068

## How to read the result on IMDB
- IMDB khá cân bằng nên accuracy và macro-F1 có thể gần nhau.
- Dù vậy vẫn cần báo cáo macro-F1 để giữ thói quen đánh giá đúng khi sang dữ liệu lệch lớp.

## Test per-class report
- class `negative`: precision=0.9168, recall=0.8948, f1=0.9057, support=2500.0
- class `positive`: precision=0.8973, recall=0.9188, f1=0.9079, support=2500.0
- class `macro avg`: precision=0.9070, recall=0.9068, f1=0.9068, support=5000.0
- class `weighted avg`: precision=0.9070, recall=0.9068, f1=0.9068, support=5000.0
