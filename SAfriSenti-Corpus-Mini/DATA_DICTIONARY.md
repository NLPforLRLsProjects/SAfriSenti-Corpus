# Data Dictionary

| Column | Description |
|---|---|
| `sample_id` | Unique sample identifier generated for this verification pack |
| `language` | Language associated with the record |
| `text` | Cleaned tweet/post text after removal of URLs and user mentions |
| `sentiment` | Sentiment label: positive, negative, or neutral |
| `code_switched_english` | Indicates whether the record contains at least one English token based on a practical English-token list |
| `english_token_count` | Number of detected English tokens |
| `word_count` | Approximate number of word tokens |
| `source` | General source description, listed as Twitter |

## Label Meaning

| Label | Meaning |
|---|---|
| `positive` | The text expresses favourable or positive sentiment |
| `negative` | The text expresses unfavourable or negative sentiment |
| `neutral` | The text is factual, unclear, balanced, or does not express strong sentiment |
