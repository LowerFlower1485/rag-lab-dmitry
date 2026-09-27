- backend: `tfidf`
- chunk size: `80`
- overlap: `20`
- k: `1 3 5 10`
- dev: `data/dev_questions.json`

powershell
python run.py evaluate --questions instructor\test_gold.json --backend tfidf --chunk-size 80 --overlap 20 --k 1 3 5 10 --output results\dmitry_test_fixed.json
