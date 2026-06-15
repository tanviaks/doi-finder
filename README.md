**FindMyDOI**
Paste your reference list — get DOIs automatically.
A free, browser-based tool that finds DOI (Digital Object Identifier) links for academic references using the Crossref API. No signup, no backend, no cost.
Live site: `https://tanviaks.github.io/doi-finder`
---
**What it does**
Researchers and students often have to manually search and add DOIs to their reference lists before submitting manuscripts. This tool automates that process:
Paste your references (any format — APA, MLA, Vancouver, numbered, plain text)
Click Find DOIs
Each reference is matched against 140M+ scholarly records in the Crossref database
Results show the DOI link + a confidence score (High / Medium / Low)
Copy your updated reference list with DOIs included
---
**Features**
✅ Works with any citation format
✅ Confidence scoring for every match
✅ Copy all references or only found DOIs
✅ No login, no API key, no cost
✅ Runs entirely in the browser — your data never leaves your device
✅ Mobile friendly
---
How to use
Just open the website and paste your references — one reference per line.
Example input:
```
Smith JA, Brown T. Long-term effects of aerobic exercise on cognitive function. Lancet. 2020;395:1573-1580.
LeCun Y, Bengio Y, Hinton G. Deep learning. Nature. 2015;521(7553):436-444.
```
Example output:
```
Smith JA, Brown T. Long-term effects of aerobic exercise on cognitive function. Lancet. 2020;395:1573-1580.
   DOI: https://doi.org/10.1016/s0140-6736(20)30567-3

LeCun Y, Bengio Y, Hinton G. Deep learning. Nature. 2015;521(7553):436-444.
   DOI: https://doi.org/10.1038/nature14539
```
---
**Limitations**
Older papers (before ~1990) may not have DOIs registered in Crossref
Some regional or predatory journals are not indexed
Book chapters and grey literature may not be found
Low confidence matches should always be verified manually
---
**Technology**
Pure HTML + CSS + JavaScript — no frameworks, no dependencies
Crossref REST API — free, open metadata for 140M+ scholarly works
Hosted on GitHub Pages — free static hosting
---
Run locally
No installation needed. Just download `index.html` and open it in any browser (Chrome or Edge recommended for local use).
---
Contributing
Contributions are welcome! If you want to improve the matching algorithm, add features, or fix bugs:
Fork this repository
Create a new branch (`git checkout -b feature/your-feature`)
Make your changes in `index.html`
Submit a pull request
---
Contributors
Name: Tanvi Sharma	 Role: Creator & maintainer
Name: Ankita Sharma	 Role: Creator
---
License
MIT License — free to use, modify, and distribute.
---
Built for researchers, by researchers. If this tool saved you time, consider sharing it with your lab or department!
