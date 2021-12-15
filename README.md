# Software Supply Chain Compromises - A Living Dataset

The `.csv` file in this repository represents the work by *IQT Labs* to identify
and create a living (though not breathing) dataset of publicly reported software
supply chain compromises.
Dan Geer, Bentz Tozer, and John Speed Meyers used this dataset for an article
analyzing software supply chain compromises (see the citation below).

We want and need help to maintain this dataset. Please help us maintain it by
submitting pull requests to identify mistakes we made (we're human after all)
either of commission or by omission. Importantly, this dataset will quickly go
out of date unless new attacks are added.

**Some conventions...**

- All table entries are sorted according to their `report_date`, since it is the only non-null sortable field.
- All dates in the table are in `m / d / yyyy` format.

**If you are interested in software supply chain security, we recommend recent
research and initiatives such as...**

- Software Bill of Materials effort, National Telecommunications and
  Information Administration.
  [Link](https://www.ntia.gov/SBOM).

- Trey Herr, William Loomis, Stewart Scott, June Lee, "Breaking Trust: Shades of
  Crisis across an Insecure Software Supply Chain," The Atlantic Council, 2020.
  [Link](https://www.atlanticcouncil.org/wp-content/uploads/2020/07/Breaking-
  trust-Shades-of-crisis-across-an-insecure-software-supply-chain.pdf).

- OpenSSF, Open Source Security Foundation, a Linux Foundation project.
  [Link](https://openssf.org/).

- Marc Ohm, Backstabber's Knife Collection, an open source malware research
  repository.
  [Link](https://dasfreak.github.io/Backstabbers-Knife-Collection/).

- In-toto Project, Software Supply Chain Compromises, New York University Secure
  Systems Lab.
  [Link](https://github.com/in-toto/supply-chain-compromises).


**You can find IQT Lab's own public research on software supply chain security
below...**

- Dan Geer, Bentz Tozer, and John Speed Meyers, "Counting Broken Links: A
  Quant's View of Software Supply Chain Security," USENIX, December 2020.
  [Link](https://www.usenix.org/system/files/login/articles/login_
  winter20_17_geer.pdf)

- John Speed Meyers and Bentz Tozer, "pypi-scan: A Tool for Scanning the Python
  Package Index for Typosquatters," IQT Blog, October 16, 2020.
  [Link](https://www.iqt.org/pypi-scan/),
  [GitHub Repository](https://github.com/IQTLabs/pypi-scan).

- John Speed Meyers and Bentz Tozer, "Bewear: Python Typosquatting is About More
  than Typos," IQT Blog, September 30, 2020.
  [Link](https://www.iqt.org/bewear-python-typosquatting-is-about-more-than-
  typos/).

