# PASM-analysis
Practical Applications of Stochastic Modelling (PASM) workshop series analysis.
This repository compiles data from the PASM and describe a brief analysis in a [ResearchGate pre-print](https://www.researchgate.net/publication/357279741_Practical_Applications_of_Stochastic_Modelling_PASM_over_15_years_ten_workshop_editions_and_95_papers_later) entitled: _"Practical Applications of Stochastic Modelling (PASM) over 15 years: ten workshop editions and 95 papers later"_, December 2021, [DOI: 10.13140/RG.2.2.30162.07368](http://dx.doi.org/10.13140/RG.2.2.30162.07368), License: Creative Commons BY-NC-SA 4.0, by Ricardo M. Czekster.

# Files
- `keywords-PASM.txt`: the 'full' list of keywords for all 95 papers (all editions), a total of 414;
- `myLayout.layout`: file used to perform a customised export using the [JabRef](https://docs.jabref.org/) tool;
- `pasm-analysis.xlsx`: brief analysis for the PASM LaTeX .bib file, obtained from the JabRef export and using MS-Excel to combine outputs;
- `PASM-new2021.bib`: main LaTeX bibfile extracted directly from ScienceDirect workshop links;
- `workshop-editions.txt`: list of workshop editions and dates;

# Auxiliary tools
- [Overleaf](overleaf.com/) online LaTeX editor (free)
  - On-line tool (Internet)
- [JabRef](https://docs.jabref.org/) version 5.4 (free)
  - Download: 169Mb
- [WordClouds](https://www.wordclouds.co.uk/) (free)
  - On-line tool (Internet)
- MS-Excel (proprietary)

# Using the JabRef layout file
1. Open JabRef 
2. Open .bibfile (`PASM-new2021.bib`)
3. Go to _Options > Preferences > Custom export formats_
4. Create a new one: click on "Add", then choose a name (e.g., `myFormat`), add the layout file provided here (`myLayout.layout`), and file extension put `export`
5. Click on _File > Export > Export all entries_
6. Choose a name (e.g., `output`) and then on 'Type' option, select the `export` option (created on item 4)
7. Open exported file in a text editor (`output.export`) - change the layout file as you wish to your needs

