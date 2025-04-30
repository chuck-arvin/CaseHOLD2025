This repository contains code and data used for Understanding Legal Reasoning With LLMs: A Systematic Study of Performance, Scale, and Memorization. The work assesses how well off the shelf large language models perform on the CaseHOLD dataset.

We generate labels from several LLMs in three notebooks, CaseHOLD-{Llama, Nova, OAI}Labels.ipynb. The resulting labels are written out as files, casehold_test_{llama, nova, openai}_labels.csv. Those labels are analyzed in CaseHOLD-Analysis.ipynb.

Our citation anonymization tests take place in CaseHOLD-Anonymization.ipynb, with the raw data in casehold_test_with_anonymization_oai.csv.
