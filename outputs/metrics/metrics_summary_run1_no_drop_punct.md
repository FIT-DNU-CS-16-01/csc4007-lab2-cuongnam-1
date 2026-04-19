# Metrics Summary
- dataset: imdb
- vectorizer: tfidf
- model: logreg
- val_accuracy: 0.9076
- val_macro_f1: 0.9076
- test_accuracy: 0.9064
- test_macro_f1: 0.9064

## How to read the result on IMDB
- IMDB khá cân bằng nên accuracy và macro-F1 có thể gần nhau.
- Dù vậy vẫn cần báo cáo macro-F1 để giữ thói quen đánh giá đúng khi sang dữ liệu lệch lớp.

## Test per-class report
- class `negative`: precision=0.9157, recall=0.8952, f1=0.9053, support=2500.0
- class `positive`: precision=0.8975, recall=0.9176, f1=0.9074, support=2500.0
- class `macro avg`: precision=0.9066, recall=0.9064, f1=0.9064, support=5000.0
- class `weighted avg`: precision=0.9066, recall=0.9064, f1=0.9064, support=5000.0
