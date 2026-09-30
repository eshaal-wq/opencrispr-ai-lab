# opencrispr-ai-lab

# OpenCRISPR-1 FASTA Validator

Browser-based tool to validate FASTA records for OpenCRISPR-1 and other CRISPR proteins.

##  What it does
Paste FASTA records or open a .fasta / .fa file. The page reports each sequence, and checks that a DNA coding sequence translates to the protein record.

Everything runs in your browser; nothing is uploaded. Privacy-first for lab work.

##  Features
- Paste FASTA or open file (.fasta, .fa, .txt)
- Reports each sequence: ID, length, type (DNA/Protein)
- Validates DNA → Protein translation
- Flags mismatches and frame errors
- 100% client-side - no server, no upload, data never leaves your browser

##  Built With
- HTML, CSS, JavaScript
- Browser FileReader API
- No dependencies

##  Data Source
Tested with Profluent Bio OpenCRISPR-1 sequences (Open License).
Works with any FASTA file.

##  How to Run
1. Open `index.html` in browser
2. Paste FASTA records or click "Open File"
3. View report and translation check

##  Privacy
All validation happens locally in your browser. No data is sent to any server.
## Credits & References
- This tool is built to support [OpenCRISPR-1](https://github.com/Profluent-Bio/OpenCRISPR) by Profluent Bio
- OpenCRISPR-1 is an open-source AI-generated gene editor, released under MIT License
- FASTA format specification: NCBI
- This project is not affiliated with Profluent Bio, but built as a companion validation tool for the Open Science community.
- ```bibtex
@article{ruffolo2024design,
  title   = {Design of highly functional genome editors by modeling the universe of CRISPR-Cas sequences},
  author  = {Ruffolo, Jeffrey A. and Nayfach, Stephen and Gallagher, Joseph and Bhatnagar, Aadyot and Beazer, Joel and Hussain, Riffat and Russ, Jordan and Yip, Jennifer and Hill, Emily and Pacesa, Martin and Meeske, Alexander J. and Cameron, Peter and Madani, Ali},
  journal = {bioRxiv},
  year    = {2024}

##  Global Hack Week - Oct 2026
Built for GHW - Open Science / AI for Good Challenge

##  Author
eshaal-wq - Karachi, PK
