# SAfriSenti Dataset Sample

This repository pack provides a balanced dataset sample from the SAfriSenti language Corpus.

## Purpose

The sample is prepared to demonstrate the dataset's structure and label distribution of the SAfriSenti corpus for verification and reproducibility.

## Important Note on Current Upload

This pack was extracted from the five language files for this task: Sepedi, Setswana, Sesotho, and isiXhosa and isiZulu. Contains a sample of **1,500 records** from the five languages. 

## Balanced Sample Design

Each included language contains 100 positive, 100 negative, and 100 neutral records, giving 300 records per language.

## Sample Distribution

| Language | Positive | Negative | Neutral | Total |
|---|---:|---:|---:|---:|
| Sepedi | 100 | 100 | 100 | 300 |
| Sesotho | 100 | 100 | 100 | 300 |
| Setswana | 100 | 100 | 100 | 300 |
| isiXhosa | 100 | 100 | 100 | 300 |
| **Total** | **400** | **400** | **400** | **1200** |

## Readability and English Code-Switching Selection

The dataset sample prioritises sentences that are easier to inspect manually. The sampling process selected records that:

- contain 5 to 26 word tokens;
- have URLs and user mentions removed;
- contain at least one English token to indicate English code-switching;
- are balanced by sentiment category;
- exclude a small set of highly explicit terms to keep the verification sample suitable for review;
- exclude obvious encoding artefacts/mojibake.

The original dataset may contain a broader range of informal spelling, slang, emojis, code-switching, and social media expressions.

## Files in This Pack

| File/Folder | Description |
|---|---|
| `sample_dataset/` | Balanced sample CSV files per language and combined sample |
| `metadata/dataset_components.csv` | Dataset component evidence summary |
| `metadata/sample_distribution_summary.csv` | Count of samples by language and sentiment |
| `metadata/selection_quality_summary.csv` | Availability and selection notes |
| `metadata/file_inventory.csv` | Inventory of files in this pack |
| `DATASET_CARD.md` | Dataset card for SAfriSenti |
| `DATA_DICTIONARY.md` | Data dictionary for sample columns |
| `ACCESS_STATEMENT.md` | Access, ethics, and redistribution statement |

## Citation Evidence

The SAfriSenti corpus and its extensions are documented in SIGUL 2022, RAIL 2023, BDCC 2024, and PLOS ONE 2025.

## Contact

Koena Ronny Mabokela  
Email: krmabokela@gmail.com


## Balanced Verification Sample Files

- `sample_dataset/sepedi_sample_300.csv`
- `sample_dataset/setswana_sample_300.csv`
- `sample_dataset/sesotho_sample_300.csv`
- `sample_dataset/isixhosa_sample_300.csv`
- `sample_dataset/isizulu_sample_300.csv`
- `sample_dataset/SAfriSenti_sample_1500.csv`
