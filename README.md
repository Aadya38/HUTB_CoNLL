README
Overview
This script processes a CoNLL-formatted file and a variant CSV file to generate a new CoNLL-style output with variant sentence annotations aligned to reference sentences.

Features
Parses variant sentence IDs for grouping.

Reads and parses variant sentences from CSVs with flexible column formats and separators.

Reads CoNLL files and structures sentences.

Aligns each variant sentence with its corresponding reference sentence.

Outputs CoNLL-style rows (word, pos_tag, head, rel) for each variant.

Usage
python
Copy
Edit
generate_conll_output(conll_file='input.conll', variant_file='variants.csv', output_file='output.conll')
Requirements
Python 3

pandas

Logging
Logs key steps and warnings for debugging malformed input or missing data.

