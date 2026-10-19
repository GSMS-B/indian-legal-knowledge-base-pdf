---
language:
- en
- hi
license: cc-by-4.0
tags:
- legal
- indian-law
- india-code
- gazette-of-india
- pdf
- government-gazette
- legal-corpus
- statutes
- bns
- bnss
- bsa
- constitution-of-india
- criminal-law
- corporate-law
- direct-tax
- securities-law
- telecom
- labor-codes
- intellectual-property
- environmental-law
- public-health
- legal-nlp
- document-ai
- layout-analysis
- ocr
size_categories:
- n<1K
pretty_name: Indian Legal Knowledge Base (Official Source PDFs)
task_categories:
- text-retrieval
- question-answering
- document-question-answering
---

<div align="center">

# 📜 Indian Legal Knowledge Base (v3.0)
### Official Source Publications from Gazette of India & India Code (96 Primary Enactments)

<p align="center">
  <b>The authoritative open-access collection of 96 official Gazette of India and India Code primary legislative source PDF publications — encompassing the 2026 Constitution of India, 2023 Criminal Sanhitas (BNS, BNSS, BSA), direct taxation, corporate and securities laws, labor codes, telecommunications, and 13 major legal domains.</b>
</p>

<!-- Shields / Badges -->
[![Corpus Size](https://img.shields.io/badge/Corpus%20Size-96%20Official%20Source%20PDFs-emerald.svg?style=for-the-badge&logo=adobeacrobatreader)](https://huggingface.co/datasets/GSMS-B/indian-legal-knowledge-base-pdf)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-amber.svg?style=for-the-badge)](https://creativecommons.org/licenses/by/4.0/)
[![Official Authority](https://img.shields.io/badge/Authority-Gazette%20of%20India%20%7C%20India%20Code-blue.svg?style=for-the-badge)](https://www.indiacode.nic.in/)
[![Git LFS](https://img.shields.io/badge/Storage-Git%20LFS-red.svg?style=for-the-badge&logo=git-lfs)](https://huggingface.co/datasets/GSMS-B/indian-legal-knowledge-base-pdf)
[![MCP Space](https://img.shields.io/badge/%F0%9F%A4%97%20Space-Indian%20Legal%20MCP-orange.svg?style=for-the-badge)](https://huggingface.co/spaces/GSMS-B/indian-legal-mcp)

<br>

<img src="assets/poster.png" alt="Indian Legal Knowledge Base Poster" width="100%" />

</div>

---

> ### 🔗 Ecosystem Navigation
> - ⚖️ **Companion Structured JSON Dataset:** For normalized, chaptered JSON provisions and concordance tables, visit **[Indian Legal Knowledge Base (JSON Corpus)](https://huggingface.co/datasets/GSMS-B/indian-legal-knowledge-base-json)**.
> - ⚡ **Live Model Context Protocol (MCP) Server:** Connect this corpus directly to Claude, ChatGPT, Cursor, or any agentic system using the **[Indian Legal MCP Server](https://huggingface.co/spaces/GSMS-B/indian-legal-mcp)**.

---

## 📖 Overview

The **Indian Legal Knowledge Base (Official Source PDFs)** contains unmodified, official publications of primary legislation from:
- **The Gazette of India (Extraordinary / Ordinary)**: Official notifications published by the Directorate of Printing, Ministry of Housing and Urban Affairs, Government of India.
- **India Code Digital Repository**: The official legislative repository maintained by the Legislative Department, Ministry of Law and Justice.
- **Parliamentary Act Publications**: Certified Acts of Parliament.

This dataset is designed for OCR benchmarks, Document Layout Analysis, Vision-Language Model (VLM) document parsing, and high-fidelity evidentiary verification.

---

## 📚 Complete Catalogue of Source PDFs (96 Enactments)

| Domain | PDF Filename | Act Code | Official Statute Name | Year | Source / Authority |
|---|---|:---:|---|:---:|---|
| **Criminal Law & Penal Statutes** | <code>arms_act_1959.pdf</code> | `ARMS` | Arms Act, 1959 | 1959 | Gazette of India, Pt. II, Sec. 1, No. 46 dt. 24-12-1959; India Code Act No. 54 of 1959 |
|  | <code>bharatiya_nagarik_<br>suraksha_sanhita_<br>2023.pdf</code> | `BNSS` | Bharatiya Nagarik Suraksha Sanhita, 2023 | 2023 | Gazette of India (Extraordinary), Pt. II, Sec. 1, No. 62; Enforced via S.O. 849(E) dt. 23-02-2024 |
|  | <code>bharatiya_nyaya_sanhita_<br>2023.pdf</code> | `BNS` | Bharatiya Nyaya Sanhita, 2023 | 2023 | Gazette of India (Extraordinary), Pt. II, Sec. 1, No. 61; Enforced via S.O. 848(E) dt. 23-02-2024 |
|  | <code>bharatiya_sakshya_<br>adhiniyam_2023.pdf</code> | `BSA` | Bharatiya Sakshya Adhiniyam, 2023 | 2023 | Gazette of India (Extraordinary), Pt. II, Sec. 1, No. 63; Enforced via S.O. 850(E) dt. 23-02-2024 |
|  | <code>contempt_of_courts_act_<br>1971.pdf</code> | `CONTEMPT_COURTS` | Contempt of Courts Act, 1971 | 1971 | Gazette of India, Pt. II, Sec. 1, No. 84 dt. 24-12-1971; India Code Act No. 70 of 1971 |
|  | <code>dowry_prohibition_act_<br>1961.pdf</code> | `DPA` | Dowry Prohibition Act, 1961 | 1961 | Gazette of India, Pt. II, Sec. 1, No. 29 dt. 20-05-1961; India Code Act No. 28 of 1961 |
|  | <code>narcotic_drugs_and_<br>psychotropic_substances_<br>act_1985.pdf</code> | `NDPS` | Narcotic Drugs and Psychotropic Substances Act, 1985 | 1985 | Gazette of India, Pt. II, Sec. 1, No. 74 dt. 16-09-1985; India Code Act No. 61 of 1985 |
|  | <code>prevention_of_corruption_<br>act_1988.pdf</code> | `PCA` | Prevention of Corruption Act, 1988 | 1988 | Gazette of India, Pt. II, Sec. 1, No. 63 dt. 09-09-1988; India Code Act No. 49 of 1988 |
|  | <code>prevention_of_money_<br>laundering_act_2002.pdf</code> | `PMLA` | Prevention of Money Laundering Act, 2002 | 2002 | Gazette of India, Pt. II, Sec. 1, No. 17 dt. 17-01-2003; India Code Act No. 15 of 2003 |
|  | <code>protection_of_children_<br>from_sexual_offences_act_<br>2012.pdf</code> | `POCSO` | Protection of Children from Sexual Offences Act, 2012 | 2012 | Gazette of India, Pt. II, Sec. 1, No. 37 dt. 20-06-2012; India Code Act No. 32 of 2012 |
|  | <code>unlawful_activities_<br>prevention_act_1967.pdf</code> | `UAPA` | Unlawful Activities (Prevention) Act, 1967 | 1967 | Gazette of India, Pt. II, Sec. 1, No. 42 dt. 30-12-1967; India Code Act No. 37 of 1967 |
| **Constitutional Law & Public Administration** | <code>administrative_tribunals_<br>act_1985.pdf</code> | `ATA` | Administrative Tribunals Act, 1985 | 1985 | Gazette of India, Pt. II, Sec. 1, No. 16 dt. 27-02-1985; India Code Act No. 13 of 1985 |
|  | <code>advocates_act_1961.pdf</code> | `ADVOCATES` | Advocates Act, 1961 | 1961 | Gazette of India, Pt. II, Sec. 1, No. 27 dt. 19-05-1961; India Code Act No. 25 of 1961 |
|  | <code>constitution_of_india_<br>1950_eng_2026_<br>edition.pdf</code> | `CONST` | Constitution of India (Official English Edition) | 1950 | Official Digital Edition (incorporating up to the 106th Amendment Act, 2023); Ministry of Law and Justice, Government of India |
|  | <code>legal_services_<br>authorities_act_1987.pdf</code> | `LSAA` | Legal Services Authorities Act, 1987 | 1987 | Gazette of India, Pt. II, Sec. 1, No. 49 dt. 12-10-1987; India Code Act No. 39 of 1987 |
|  | <code>protection_of_civil_<br>rights_act_1955.pdf</code> | `PCRA` | Protection of Civil Rights Act, 1955 | 1955 | Gazette of India, Pt. II, Sec. 1, No. 26 dt. 08-05-1955; India Code Act No. 22 of 1955 |
|  | <code>protection_of_human_<br>rights_act_1993.pdf</code> | `PHRA` | Protection of Human Rights Act, 1993 | 1993 | Gazette of India, Pt. II, Sec. 1, No. 10 dt. 10-01-1994; India Code Act No. 10 of 1994 |
|  | <code>representation_of_the_<br>people_act_1951.pdf</code> | `RPA` | Representation of the People Act, 1951 | 1951 | India Code Act No. 43 of 1951; Election Commission of India |
|  | <code>right_to_information_act_<br>2005.pdf</code> | `RTI` | Right to Information Act, 2005 | 2005 | Gazette of India, Pt. II, Sec. 1, No. 25 dt. 21-06-2005; India Code Act No. 22 of 2005 |
|  | <code>scheduled_castes_and_<br>scheduled_tribes_<br>prevention_of_atrocities_<br>act_1989.pdf</code> | `SCST` | Scheduled Castes and Scheduled Tribes (Prevention of Atrocities) Act, 1989 | 1989 | Gazette of India, Pt. II, Sec. 1, No. 39 dt. 12-09-1989; India Code Act No. 33 of 1989 |
| **Commercial, Corporate & Financial Law** | <code>the_arbitration_and_<br>conciliation_act_<br>1996.pdf</code> | `ACA` | Arbitration and Conciliation Act, 1996 | 1996 | Gazette of India, Pt. II, Sec. 1, No. 40 dt. 19-08-1996; India Code Act No. 26 of 1996 |
|  | <code>chit_funds_act_1982.pdf</code> | `CHIT` | Chit Funds Act, 1982 | 1982 | Gazette of India, Pt. II, Sec. 1, No. 47 dt. 20-08-1982; India Code Act No. 40 of 1982 |
|  | <code>commercial_courts_act_<br>2015.pdf</code> | `COMMERCIAL_COURTS` | Commercial Courts Act, 2015 | 2015 | Gazette of India, Pt. II, Sec. 1, No. 4 dt. 01-01-2016; India Code Act No. 4 of 2016 |
|  | <code>the_companies_act_<br>2013.pdf</code> | `CA` | Companies Act, 2013 | 2013 | Gazette of India, Pt. II, Sec. 1, No. 27 dt. 30-08-2013; India Code Act No. 18 of 2013 |
|  | <code>competition_act_2002.pdf</code> | `COMPETITION` | Competition Act, 2002 | 2002 | Gazette of India, Pt. II, Sec. 1, No. 14 dt. 14-01-2003; India Code Act No. 12 of 2003 |
|  | <code>the_consumer_protection_<br>act_2019.pdf</code> | `CPA` | Consumer Protection Act, 2019 | 2019 | Gazette of India, Pt. II, Sec. 1, No. 54 dt. 09-08-2019; India Code Act No. 35 of 2019 |
|  | <code>indian_partnership_act_<br>1932.pdf</code> | `IPA` | Indian Partnership Act, 1932 | 1932 | India Code Central Acts Repository / Act No. 9 of 1932 dt. 08-04-1932 |
|  | <code>insolvency_bankruptcy_<br>code_2016.pdf</code> | `IBC` | Insolvency and Bankruptcy Code, 2016 | 2016 | Gazette of India, Pt. II, Sec. 1, No. 37 dt. 28-05-2016; India Code Act No. 31 of 2016 |
|  | <code>limited_liability_<br>partnership_act_2008.pdf</code> | `LLP` | Limited Liability Partnership Act, 2008 | 2008 | Gazette of India, Pt. II, Sec. 1, No. 9 dt. 09-01-2009; India Code Act No. 6 of 2009 |
|  | <code>micro_small_and_medium_<br>enterprises_development_<br>act_2006.pdf</code> | `MSMED` | Micro, Small and Medium Enterprises Development Act, 2006 | 2006 | Gazette of India, Pt. II, Sec. 1, No. 32 dt. 16-06-2006; India Code Act No. 27 of 2006 |
|  | <code>real_estate_regulation_<br>and_development_act_<br>2016.pdf</code> | `RERA` | Real Estate (Regulation and Development) Act, 2016 | 2016 | Gazette of India, Pt. II, Sec. 1, No. 18 dt. 26-03-2016; India Code Act No. 16 of 2016 |
|  | <code>sale_of_goods_act_<br>1930.pdf</code> | `SGA` | Sale of Goods Act, 1930 | 1930 | India Code Central Acts Repository / Act No. 3 of 1930 dt. 15-03-1930 |
|  | <code>securities_contracts_<br>regulation_act_1956.pdf</code> | `SCRA` | Securities Contracts (Regulation) Act, 1956 | 1956 | India Code Act No. 42 of 1956; Ministry of Finance |
|  | <code>securities_and_exchange_<br>board_of_india_act_<br>1992.pdf</code> | `SEBI` | Securities and Exchange Board of India Act, 1992 | 1992 | Gazette of India, Pt. II, Sec. 1, No. 22 dt. 04-04-1992; India Code Act No. 15 of 1992 |
| **Banking, Finance & Revenue** | <code>banking_regulation_act_<br>1949.pdf</code> | `BRA` | Banking Regulation Act, 1949 | 1949 | Gazette of India, Pt. II, Sec. 1, No. 10 dt. 10-03-1949; India Code Act No. 10 of 1949 |
|  | <code>central_goods_and_<br>services_tax_act_<br>2017.pdf</code> | `CGST` | Central Goods and Services Tax Act, 2017 | 2017 | Gazette of India, Pt. II, Sec. 1, No. 12 dt. 12-04-2017; India Code Act No. 12 of 2017 |
|  | <code>customs_act_1962.pdf</code> | `CUSTOMS` | Customs Act, 1962 | 1962 | Gazette of India, Pt. II, Sec. 1, No. 58 dt. 14-12-1962; India Code Act No. 52 of 1962 |
|  | <code>foreign_contribution_<br>regulation_act_2010.pdf</code> | `FCRA` | Foreign Contribution (Regulation) Act, 2010 | 2010 | Gazette of India, Pt. II, Sec. 1, No. 51 dt. 27-09-2010; India Code Act No. 42 of 2010 |
|  | <code>foreign_exchange_<br>management_act_1999.pdf</code> | `FEMA` | Foreign Exchange Management Act, 1999 | 1999 | Gazette of India, Pt. II, Sec. 1, No. 53 dt. 30-12-1999; India Code Act No. 42 of 1999 |
|  | <code>income_tax_act_2025.pdf</code> | `ITA` | Income-tax Act, 2025 | 2025 | Official Legislative Publication; Ministry of Finance (CBDT) |
|  | <code>indian_stamp_act_<br>1899.pdf</code> | `STAMP` | Indian Stamp Act, 1899 | 1899 | India Code Central Acts Repository / Act No. 2 of 1899 dt. 27-01-1899 |
|  | <code>insurance_act_1938.pdf</code> | `INSURANCE` | Insurance Act, 1938 | 1938 | India Code Act No. 4 of 1938; Ministry of Finance |
|  | <code>insurance_regulatory_and_<br>development_authority_<br>act_1999.pdf</code> | `IRDAI` | Insurance Regulatory and Development Authority Act, 1999 | 1999 | Gazette of India, Pt. II, Sec. 1, No. 54 dt. 29-12-1999; India Code Act No. 41 of 1999 |
|  | <code>integrated_goods_and_<br>services_tax_act_<br>2017.pdf</code> | `IGST` | Integrated Goods and Services Tax Act, 2017 | 2017 | Gazette of India, Pt. II, Sec. 1, No. 13 dt. 12-04-2017; India Code Act No. 13 of 2017 |
|  | <code>payment_and_settlement_<br>systems_act_2007.pdf</code> | `PSSA` | Payment and Settlement Systems Act, 2007 | 2007 | Gazette of India, Pt. II, Sec. 1, No. 62 dt. 20-12-2007; India Code Act No. 51 of 2007 |
|  | <code>prohibition_of_benami_<br>property_transactions_<br>act_1988.pdf</code> | `PBPTA` | Prohibition of Benami Property Transactions Act, 1988 | 1988 | India Code Act No. 45 of 1988 as amended by Act No. 43 of 2016; Ministry of Finance |
|  | <code>recovery_of_debts_and_<br>bankruptcy_act_1993.pdf</code> | `RDBA` | Recovery of Debts and Bankruptcy Act, 1993 | 1993 | Gazette of India, Pt. II, Sec. 1, No. 74 dt. 27-08-1993; India Code Act No. 51 of 1993 |
|  | <code>reserve_bank_of_india_<br>act_1934.pdf</code> | `RBI` | Reserve Bank of India Act, 1934 | 1934 | India Code Central Acts Repository / Act No. 2 of 1934 dt. 06-03-1934 |
|  | <code>securitisation_and_<br>reconstruction_of_<br>financial_assets_and_<br>enforcement_of_security_<br>interest_act_2002.pdf</code> | `SARFAESI` | SARFAESI Act, 2002 | 2002 | Gazette of India, Pt. II, Sec. 1, No. 67 dt. 18-12-2002; India Code Act No. 54 of 2002 |
| **Civil Procedure, Contracts & Property** | <code>indian_contract_act_<br>1872.pdf</code> | `ICA` | Indian Contract Act, 1872 | 1872 | India Code Central Acts Repository / Act No. 9 of 1872 dt. 25-04-1872 |
|  | <code>easements_act_1882.pdf</code> | `EASEMENTS` | Indian Easements Act, 1882 | 1882 | India Code Central Acts Repository / Act No. 5 of 1882 dt. 17-02-1882 |
|  | <code>limitation_act_1963.pdf</code> | `LA` | Limitation Act, 1963 | 1963 | Gazette of India, Pt. II, Sec. 1, No. 41 dt. 05-10-1963; India Code Act No. 36 of 1963 |
|  | <code>registration_act_<br>1908.pdf</code> | `REGISTRATION` | Registration Act, 1908 | 1908 | India Code Central Acts Repository / Act No. 16 of 1908 dt. 18-12-1908 |
|  | <code>right_to_fair_<br>compensation_and_<br>transparency_in_land_<br>acquisition_<br>rehabilitation_and_<br>resettlement_act_<br>2013.pdf</code> | `RFCTLARR` | Right to Fair Compensation & Transparency in Land Acquisition (RFCTLARR) Act, 2013 | 2013 | Gazette of India, Pt. II, Sec. 1, No. 40 dt. 27-09-2013; India Code Act No. 30 of 2013 |
|  | <code>the_specific_relief_act_<br>1963.pdf</code> | `SRA` | Specific Relief Act, 1963 | 1963 | Gazette of India, Pt. II, Sec. 1, No. 55 dt. 13-12-1963; India Code Act No. 47 of 1963 |
|  | <code>transfer_of_property_act_<br>1882.pdf</code> | `TPA` | Transfer of Property Act, 1882 | 1882 | India Code Central Acts Repository / Act No. 4 of 1882 dt. 17-02-1882 |
| **Unified Labor Codes** | <code>child_and_adolescent_<br>labour_prohibition_and_<br>regulation_act_1986.pdf</code> | `CALPRA` | Child and Adolescent Labour (Prohibition and Regulation) Act, 1986 | 1986 | Gazette of India, Pt. II, Sec. 1, No. 75 dt. 23-12-1986; India Code Act No. 61 of 1986 |
|  | <code>code_on_social_security_<br>2020.pdf</code> | `CSS` | Code on Social Security, 2020 | 2020 | Gazette of India, Pt. II, Sec. 1, No. 53 dt. 29-09-2020; India Code Act No. 36 of 2020 |
|  | <code>code_on_wages_2019.pdf</code> | `COW` | Code on Wages, 2019 | 2019 | Gazette of India, Pt. II, Sec. 1, No. 43 dt. 08-08-2019; India Code Act No. 29 of 2019 |
|  | <code>the_industrial_relations_<br>code_2020.pdf</code> | `IRC` | Industrial Relations Code, 2020 | 2020 | Gazette of India, Pt. II, Sec. 1, No. 52 dt. 29-09-2020; India Code Act No. 35 of 2020 |
|  | <code>occupational_safety_<br>health_and_working_<br>conditions_code_2020.pdf</code> | `OSH` | Occupational Safety, Health and Working Conditions Code, 2020 | 2020 | Gazette of India, Pt. II, Sec. 1, No. 54 dt. 29-09-2020; India Code Act No. 37 of 2020 |
| **Cyber, Technology, Telecom & Identity** | <code>the_aadhaar_targeted_<br>delivery_of_financial_<br>and_other_subsidies_<br>benefits_and_services_<br>act_2016.pdf</code> | `AADHAAR` | Aadhaar (Targeted Delivery of Financial and Other Subsidies) Act, 2016 | 2016 | Gazette of India, Pt. II, Sec. 1, No. 20 dt. 26-03-2016; India Code Act No. 18 of 2016 |
|  | <code>the_digital_personal_<br>data_protection_act_<br>2023.pdf</code> | `DPDPA` | Digital Personal Data Protection Act, 2023 | 2023 | Gazette of India, Pt. II, Sec. 1, No. 25 dt. 11-08-2023; India Code Act No. 22 of 2023 |
|  | <code>the_information_<br>technology_act_2000.pdf</code> | `IT_ACT` | Information Technology Act, 2000 | 2000 | Gazette of India, Pt. II, Sec. 1, No. 26 dt. 09-06-2000; India Code Act No. 21 of 2000 |
|  | <code>telecommunications_act_<br>2023.pdf</code> | `TELECOM` | Telecommunications Act, 2023 | 2023 | Gazette of India (Extraordinary), Pt. II, Sec. 1, No. 60 dt. 24-12-2023; Act No. 44 of 2023 |
| **Intellectual Property Rights (IPR)** | <code>copyright_act_1957.pdf</code> | `COPYRIGHT` | Copyright Act, 1957 | 1957 | Gazette of India, Pt. II, Sec. 1, No. 15 dt. 04-06-1957; India Code Act No. 14 of 1957 |
|  | <code>designs_act_2000.pdf</code> | `DESIGNS` | Designs Act, 2000 | 2000 | Gazette of India, Pt. II, Sec. 1, No. 20 dt. 25-05-2000; India Code Act No. 16 of 2000 |
|  | <code>geographical_indications_<br>of_goods_registration_<br>and_protection_act_<br>1999.pdf</code> | `GI` | Geographical Indications of Goods (Registration and Protection) Act, 1999 | 1999 | Gazette of India, Pt. II, Sec. 1, No. 60 dt. 30-12-1999; India Code Act No. 48 of 1999 |
|  | <code>patents_act_1970.pdf</code> | `PATENTS` | Patents Act, 1970 | 1970 | Gazette of India, Pt. II, Sec. 1, No. 49 dt. 19-09-1970; India Code Act No. 39 of 1970 |
|  | <code>trade_marks_act_1999.pdf</code> | `TRADEMARKS` | Trade Marks Act, 1999 | 1999 | Gazette of India, Pt. II, Sec. 1, No. 59 dt. 30-12-1999; India Code Act No. 47 of 1999 |
| **Family & Personal Laws** | <code>family_courts_act_<br>1984.pdf</code> | `FCA` | Family Courts Act, 1984 | 1984 | Gazette of India, Pt. II, Sec. 1, No. 79 dt. 14-09-1984; India Code Act No. 66 of 1984 |
|  | <code>guardians_and_wards_act_<br>1890.pdf</code> | `GWA` | Guardians and Wards Act, 1890 | 1890 | India Code Act No. 8 of 1890; Ministry of Law and Justice |
|  | <code>hindu_adoptions_and_<br>maintenance_act_1956.pdf</code> | `HAMA` | Hindu Adoptions and Maintenance Act, 1956 | 1956 | Gazette of India, Pt. II, Sec. 1, No. 67 dt. 21-12-1956; India Code Act No. 78 of 1956 |
|  | <code>hindu_marriage_act_<br>1955.pdf</code> | `HMA` | Hindu Marriage Act, 1955 | 1955 | Gazette of India, Pt. II, Sec. 1, No. 29 dt. 18-05-1955; India Code Act No. 25 of 1955 |
|  | <code>hindu_succession_act_<br>1956.pdf</code> | `HSA` | Hindu Succession Act, 1956 | 1956 | Gazette of India, Pt. II, Sec. 1, No. 34 dt. 17-06-1956; India Code Act No. 30 of 1956 |
|  | <code>indian_succession_act_<br>1925.pdf</code> | `ISA` | Indian Succession Act, 1925 | 1925 | India Code Central Acts Repository / Act No. 39 of 1925 dt. 30-09-1925 |
|  | <code>muslim_women_protection_<br>of_rights_on_divorce_act_<br>1986.pdf</code> | `MWPRDA` | Muslim Women (Protection of Rights on Divorce) Act, 1986 | 1986 | Gazette of India, Pt. II, Sec. 1, No. 30 dt. 19-05-1986; India Code Act No. 25 of 1986 |
|  | <code>muslim_women_protection_<br>of_rights_on_marriage_<br>act_2019.pdf</code> | `MWPRMA` | Muslim Women (Protection of Rights on Marriage) Act, 2019 | 2019 | Gazette of India, Pt. II, Sec. 1, No. 31 dt. 31-07-2019; India Code Act No. 20 of 2019 |
|  | <code>prohibition_of_child_<br>marriage_act_2006.pdf</code> | `PCMA` | Prohibition of Child Marriage Act, 2006 | 2006 | Gazette of India, Pt. II, Sec. 1, No. 6 dt. 11-01-2007; India Code Act No. 6 of 2007 |
|  | <code>special_marriage_act_<br>1954.pdf</code> | `SMA` | Special Marriage Act, 1954 | 1954 | Gazette of India, Pt. II, Sec. 1, No. 49 dt. 09-10-1954; India Code Act No. 43 of 1954 |
| **Environmental & Green Law** | <code>air_prevention_and_<br>control_of_pollution_act_<br>1981.pdf</code> | `AIR` | Air (Prevention and Control of Pollution) Act, 1981 | 1981 | Gazette of India, Pt. II, Sec. 1, No. 14 dt. 29-03-1981; India Code Act No. 14 of 1981 |
|  | <code>environment_protection_<br>act_1986.pdf</code> | `EPA` | Environment (Protection) Act, 1986 | 1986 | Gazette of India, Pt. II, Sec. 1, No. 34 dt. 23-05-1986; India Code Act No. 29 of 1986 |
|  | <code>national_green_tribunal_<br>act_2010.pdf</code> | `NGT` | National Green Tribunal Act, 2010 | 2010 | Gazette of India, Pt. II, Sec. 1, No. 25 dt. 02-06-2010; India Code Act No. 19 of 2010 |
|  | <code>van_sanrakshan_evam_<br>samvardhan_adhiniyam_<br>1980.pdf</code> | `VSA` | Van (Sanrakshan Evam Samvardhan) Adhiniyam, 1980 | 1980 | Gazette of India, Pt. II, Sec. 1, No. 80 dt. 27-12-1980; India Code Act No. 69 of 1980 |
|  | <code>water_prevention_and_<br>control_of_pollution_act_<br>1974.pdf</code> | `WATER` | Water (Prevention and Control of Pollution) Act, 1974 | 1974 | Gazette of India, Pt. II, Sec. 1, No. 6 dt. 23-03-1974; India Code Act No. 6 of 1974 |
|  | <code>wildlife_protection_act_<br>1972.pdf</code> | `WPA` | Wild Life (Protection) Act, 1972 | 1972 | Gazette of India, Pt. II, Sec. 1, No. 59 dt. 09-09-1972; India Code Act No. 53 of 1972 |
| **Public Health, Healthcare & Food Safety** | <code>drugs_and_cosmetics_act_<br>1940.pdf</code> | `DCA` | Drugs and Cosmetics Act, 1940 | 1940 | India Code Act No. 23 of 1940; Ministry of Health and Family Welfare |
|  | <code>food_safety_and_<br>standards_act_2006.pdf</code> | `FSSA` | Food Safety and Standards Act, 2006 | 2006 | Gazette of India, Pt. II, Sec. 1, No. 40 dt. 24-08-2006; India Code Act No. 34 of 2006 |
|  | <code>mental_healthcare_act_<br>2017.pdf</code> | `MHA` | Mental Healthcare Act, 2017 | 2017 | Gazette of India, Pt. II, Sec. 1, No. 11 dt. 07-04-2017; India Code Act No. 10 of 2017 |
| **Social Protection, Education & Human Welfare** | <code>juvenile_justice_care_<br>and_protection_of_<br>children_act_2015.pdf</code> | `JJ` | Juvenile Justice (Care and Protection of Children) Act, 2015 | 2015 | Gazette of India, Pt. II, Sec. 1, No. 2 dt. 01-01-2016; India Code Act No. 2 of 2016 |
|  | <code>maintenance_and_welfare_<br>of_parents_and_senior_<br>citizens_act_2007.pdf</code> | `MWPSC` | Maintenance and Welfare of Parents and Senior Citizens Act, 2007 | 2007 | Gazette of India, Pt. II, Sec. 1, No. 67 dt. 31-12-2007; India Code Act No. 56 of 2007 |
|  | <code>protection_of_women_from_<br>domestic_violence_act_<br>2005.pdf</code> | `DV` | Protection of Women from Domestic Violence Act, 2005 | 2005 | Gazette of India, Pt. II, Sec. 1, No. 51 dt. 14-09-2005; India Code Act No. 43 of 2005 |
|  | <code>right_of_children_to_<br>free_and_compulsory_<br>education_act_2009.pdf</code> | `RTE` | Right of Children to Free and Compulsory Education Act, 2009 | 2009 | Gazette of India, Pt. II, Sec. 1, No. 39 dt. 27-08-2009; India Code Act No. 35 of 2009 |
|  | <code>rights_of_persons_with_<br>disabilities_act_<br>2016.pdf</code> | `RPWDA` | Rights of Persons with Disabilities Act, 2016 | 2016 | Gazette of India, Pt. II, Sec. 1, No. 59 dt. 28-12-2016; India Code Act No. 49 of 2016 |
|  | <code>sexual_harassment_of_<br>women_at_workplace_<br>prevention_prohibition_<br>and_redressal_act_<br>2013.pdf</code> | `POSH` | Sexual Harassment of Women at Workplace (Prevention, Prohibition and Redressal) Act, 2013 | 2013 | Gazette of India, Pt. II, Sec. 1, No. 18 dt. 23-04-2013; India Code Act No. 14 of 2013 |
| **Energy, Infrastructure & Public Utilities** | <code>electricity_act_2003.pdf</code> | `EA` | Electricity Act, 2003 | 2003 | Gazette of India, Pt. II, Sec. 1, No. 39 dt. 02-06-2003; India Code Act No. 36 of 2003 |

---

## 🏛️ Domain Distribution Summary (96 Source PDFs)

| Legal Domain | Total Source PDFs |
|---|:---:|
| Criminal Law & Penal Statutes | 11 |
| Constitutional Law & Public Administration | 9 |
| Commercial, Corporate & Financial Law | 14 |
| Banking, Finance & Revenue | 15 |
| Civil Procedure, Contracts & Property | 7 |
| Unified Labor Codes | 5 |
| Cyber, Technology, Telecom & Identity | 4 |
| Intellectual Property Rights (IPR) | 5 |
| Family & Personal Laws | 10 |
| Environmental & Green Law | 6 |
| Public Health, Healthcare & Food Safety | 3 |
| Social Protection, Education & Human Welfare | 6 |
| Energy, Infrastructure & Public Utilities | 1 |
| **Total Official Source PDFs** | **96** |

---

## ⚖️ Legal Disclaimer

> **Notice:** These documents are official public records published by the Government of India under open access. For commercial, legal, or judicial proceedings, certified true copies should be procured from the respective Ministry or the Directorate of Printing.

## 👤 Curator & Citation

Curated with dedication by **GSMS-B**.

```bibtex
@dataset{indian_legal_source_pdfs_2026,
  author       = {GSMS-B},
  title        = {Indian Legal Knowledge Base: Official Gazette and India Code Source PDFs (96 Enactments)},
  year         = {2026},
  publisher    = {Hugging Face},
  version      = {3.0.0},
  url          = {https://huggingface.co/datasets/GSMS-B/indian-legal-knowledge-base-pdf}
}
```

---

<div align="center">

## 👨‍💻 Created & Curated by **GSMS-B**

**Built with dedication for Indian Legal AI Researchers, NLP Practitioners, and Legal Scholars Worldwide.**

[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-GSMS--B-orange.svg?style=for-the-badge)](https://huggingface.co/GSMS-B)
[![GitHub](https://img.shields.io/badge/GitHub-GSMS--B-181717.svg?style=for-the-badge&logo=github)](https://github.com/GSMS-B)
[![Live MCP Server](https://img.shields.io/badge/Model%20Context%20Protocol-Indian%20Legal%20MCP-blue.svg?style=for-the-badge)](https://huggingface.co/spaces/GSMS-B/indian-legal-mcp)

*“Empowering democratic access to the laws of India through open, authoritative, and structured AI intelligence.”*

</div>
