# Metrics Summary
- dataset: imdb
- vectorizer: bow
- model: logreg
- val_accuracy: 0.8892
- val_macro_f1: 0.8892
- test_accuracy: 0.8962
- test_macro_f1: 0.8962

## How to read the result on IMDB
- IMDB khá cân bằng nên accuracy và macro-F1 có thể gần nhau.
- Dù vậy vẫn cần báo cáo macro-F1 để giữ thói quen đánh giá đúng khi sang dữ liệu lệch lớp.

## Test per-class report
- class `negative`: precision=0.8983, recall=0.8936, f1=0.8959, support=2500.0
- class `positive`: precision=0.8942, recall=0.8988, f1=0.8965, support=2500.0
- class `macro avg`: precision=0.8962, recall=0.8962, f1=0.8962, support=5000.0
- class `weighted avg`: precision=0.8962, recall=0.8962, f1=0.8962, support=5000.0
