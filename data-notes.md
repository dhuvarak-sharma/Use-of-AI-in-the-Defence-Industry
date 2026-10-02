# Data Quality and Cleaning Notes

## Dataset size

The latest export contains **201 populated response records**.

The workbook also contains nine trailing blank spreadsheet rows. These are not responses and are excluded.

## Missing fields

- Automated-combatant efficiency question: **9 missing responses**
- Optional final suggestions question: **121 missing responses**

No missing values were imputed.

## Multi-select risk question

The four predefined risk categories were counted from their explicit selections. Because respondents could select multiple options, the percentages are not expected to sum to 100%.

There were **16 responses containing additional Other text**. These were retained as qualitative information and were not used to manufacture a fifth standardized category.

## Responsibility question

There were **12 responses outside the three predefined options**. They were retained as Other/free-text responses rather than silently recoded.

## Pre-emptive-strike question

There were **31 non-standard/free-text responses**.

The original direct-selection results are preserved:

- Human confirmation: 160
- Own discretion: 4
- No: 6
- Other/free-text: 31

A separate semantic audit records manual interpretation of the non-standard responses. The semantic audit is **not used to overwrite the original direct-selection counts**.

## Privacy rule

Names were collected in the original form but are not included in the repository. Individual timestamps and respondent-level raw text are also excluded from the public data files.


## Public-data note

The repository keeps only aggregate results. The original respondent-level spreadsheet, names, individual timestamps, and raw respondent-level text are not included. The separate audit files from the working analysis were consolidated into these notes to keep the public repository concise.
