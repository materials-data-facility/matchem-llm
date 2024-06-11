# 🧱🧪 Materials Science and Chemistry LLM Resources
A public repository collecting links to state-of-the-art training sets, QA, benchmarks and other evaluations for various ML and LLM applications in materials science and chemistry.

- [Chemistry](#chemistry)
  - [Chemistry Knowledge Graphs](#chemistry-knowledge-graphs)

# 🧪 Materials Science and Chemistry LLM Resources
A public repository collecting links to state-of-the-art training sets, QA, benchmarks and other evaluations for various ML and LLM applications in materials science and chemistry.

## 🧪 Chemistry
* [ChemQA](https://huggingface.co/datasets/shangzhu/ChemQA): ChemQA is a Multimodal Question-and-Answering dataset on chemistry reasoning. This work is inspired by IsoBench and ChemLLMBench. Containts 5 QA Tasks in total: Counting Numbers of Carbons and Hydrogens in Organic Molecules, Calculating Molecular Weights in Organic Molecules, Name Conversion: From SMILES to IUPAC, Molecule Captioning and Editing, and retro-synthesis Planning: inspired by [2], adapted from dataset provided in [4], following the same training, validation and evaluation splits.
* [ChemLLMBench](https://github.com/ChemFoundationModels/ChemLLMBench): A comprehensive benchmark on eight chemistry tasks
* [SMolInstruct](https://huggingface.co/datasets/osunlp/SMolInstruct): SMolInstruct is a large-scale, comprehensive, and high-quality instruction tuning dataset crafted for chemistry. It centers around small molecules, and contains 14 meticulously selected tasks and over 3M samples. This dataset has both SMILES and SELFIES versions, and you could switch to SELFIES by using use_selfies=True when loading. Tasks include name conversion, property prediction, molecule description, and chemical reaction prediction.
* [CamelAI - Chemistry](https://huggingface.co/datasets/camel-ai/chemistry): Chemistry dataset is composed of 20K problem-solution pairs obtained using gpt-4. The dataset problem-solutions pairs generating from 25 chemistry topics, 25 subtopics for each topic and 32 problems for each "topic,subtopic" pairs.
* [ChemData700k](https://huggingface.co/datasets/AI4Chem/ChemData700K?row=0): ChemData is a large-scale chemistry competency instruction tuning dataset for language models, which includes nine chemistry core tasks and 730K high-quality questions and answers, sampled from 1/10 of 7 million pieces of data.
* [ChemBench4k](https://huggingface.co/datasets/AI4Chem/ChemBench4K): ChemBench is a large-scale chemistry competency evaluation benchmark for language models, which includes nine chemistry core tasks and 4100 high-quality single-choice questions and answers.
* [ChemBench - Lamalab](https://github.com/lamalab-org/chem-bench):  A benchmark with more than 7000 questions, manually curated for various chemical topics. Covering multi-choice and free-form questions. Supports models as well as tool-augmented systems. Provides [leaderboards](https://lamalab-org.github.io/chem-bench/leaderboard/) and [human baseline](https://chembench.org/). See [paper](https://arxiv.org/abs/2404.01475) for more details.
* [Chem-RnD and ChemEDU CLAIRify](https://github.com/ac-rad/xdl-generation/tree/master/datasets): Chem-EDU (Everyday Educational Chemistry) - 40 natural language instructions containing only safe (edible) chamicals. Chem-RnD (Chemistry Research & Development) - 108 detailed chemistry-protocols for synthesizing different organic compounds in real-world chemisty labs. This is a subset of Benchmarking results and the XDL XML schema.
* [ChemCrow](https://github.com/ur-whitelab/chemcrow-public): ChemCrow is an open source package for the accurate solution of reasoning-intensive chemical tasks. Built with Langchain, it uses a collection of chemical tools including RDKit, paper-qa, as well as some relevant databases in chemistry, like Pubchem and chem-space.
* [SciAssess](https://github.com/sci-assess/SciAssess): SciAssess is a comprehensive benchmark designed to evaluate the proficiency of Large Language Models (LLMs) in scientific literature analysis. It focuses on assessing LLMs' abilities in memorization, comprehension, and analysis within the context of scientific literature, covering a wide range of scientific fields such as general chemistry, organic materials, and alloy materials. SciAssess provides a rigorous and thorough assessment of LLMs, supporting the ongoing development of LLM applications in scientific literature analysis. [paper](https://arxiv.org/abs/2403.01976).
* [VNHSGE](): VietNamese High School Graduation Examination Dataset for Large Language Models is a dataset for large language models, collected from the Vietnamese National High School Graduation Examination and similar exams to: 1.Evaluate large language models in multitasks such as question answering, text generation, reading comprehension, visual question answering, and more. 2.Cover nine subjects including 300 essays on literature and 19,000 multiple-choice questions on other subjects including mathematics, physics, chemistry, biology, English, history, geography, and civic education; 3.Contain both text and images; 4. Support Vietnamese and English languages. [|paper on chem|](https://www.researchgate.net/profile/Dao-Xuan-Quy/publication/371638463_LLMs'_Capabilities_at_the_High_School_Level_in_Chemistry_Cases_of_ChatGPT_and_Microsoft_Bing_AI_Chat/links/649fce09c41fb852dd42c064/LLMs-Capabilities-at-the-High-School-Level-in-Chemistry-Cases-of-ChatGPT-and-Microsoft-Bing-AI-Chat.pdf)  [|paper on dataset|](https://arxiv.org/abs/2305.12199)
* [GPQA](https://github.com/idavidrein/gpqa/): GPQA (Google-Proof Q&A) is a challenging dataset of 448 multiple-choice questions written by domain experts in biology, physics, and chemistry. We ensure that the questions are high-quality and extremely difficult: experts who have or are pursuing PhDs in the corresponding domains reach 65% accuracy (74% when discounting clear mistakes the experts identified in retrospect), while highly skilled non-expert validators only reach 34% accuracy, despite spending on average over 30 minutes with unrestricted access to the web (i.e., the questions are "Google-proof"). [paper](https://arxiv.org/abs/2311.12022)
* [LLM-Esterification](https://github.com/Mantas-it/LLM_Esterification): The LLM-Esterification dataset is comprised of 1200 samples linking SMILES to output synthesis procedures. [paper](https://doi.org/2076-3417/13/24/13140)

### 🕸️ Chemistry Knowledge Graphs
* [Global Chem](https://github.com/Global-Chem/global-chem): Global Chem is a public dictionary of common chemical lists using the Common Chemical Name as input and SMILES/SMARTS as output organized by their respective community in a knowledge graph.

## Materials
* [Battery Device QA](https://huggingface.co/datasets/batterydata/battery-device-data-qa): Battery device records, including anode, cathode, and electrolyte.
Examples of the question answering evaluation dataset: {'question': 'What is the cathode?', 'answer': 'Al foil', 'context': 'The blended slurry was then cast onto a clean current collector (Al foil for the cathode and Cu foil for the anode) and dried at 90 °C under vacuum overnight.', 'start index': 645}
* [MaScQA](https://github.com/M3RG-IITD/MaScQA.git): A dataset of 650 challenging questions from the materials domain that require the knowledge and skills of a materials science student who has cleared their undergraduate degree. Questions are classified based on their structure and the materials science domain-based subcategories.
* [Optical BERT Training Data](https://huggingface.co/datasets/opticalmaterials/test_datasets): Has HF errors, but data are available.
* [Optical Table QA](https://huggingface.co/datasets/opticalmaterials/OpticalTableQA): 
* [LLMs for Sustainable Concrete](https://github.com/BAMcvoelker/LLM-s-can-Design-Sustainable-Concrete-a-Systematic-Benchmark-Code-) [paper](https://www.researchsquare.com/article/rs-3913272/v1)
* [PNCExtract: Extracting Polymer Nanocomposite Samples from Articles](https://github.com/ghazalkhalighinejad/PNCExtract): The contains a manually curated list of samples for each PNC article. The data is divided into 52 validation articles and 151 test articles.
### Materials Knowledge Graphs
* [MatKG](https://github.com/olivettigroup/MatKG): MatKG is a comprehensive Knowledge Graph of Materials Science that captures a diverse range of entities and relationships from scientific literature. MatKG includes materials, properties, applications, characterization methods, synthesis methods, symmetry phase labels, and descriptors, among other entities, which are extracted automatically using advanced natural language processing methods from over 5 million papers in the domain.
* [MGED-KG](https://zenodo.org/records/11315713): Materials Genome Engineering Database Knowledge Graph (MGED-KG), which is automatically constructed from text corpus via natural language processing. MGED-KG is the most comprehensive KG for materials terminology in both Chinese and English languages, consisting of 8,660 terms and their explanations. It encompasses 11 principal categories, such as Metals, Composites, Nanomaterials, each with two or three levels of subcategories, resulting in a total of 235 distinct category labels. **(web page was not working when checked on Jun 10, 2024, but code/data are available on Zenodo)**

## Multimodal
* [Wikipedia Materials Multimodal](https://huggingface.co/datasets/lamm-mit/Cephalo-Wikipedia-Materials)

## ❓ Unknown Quality
[Chemistry Dataset from Andrersonbcedef](https://huggingface.co/datasets/andersonbcdefg/chemistry)

## 👥 Community Needs
This is an area for relatively "open comments" one community needs.
* One good thing to add would be a benchmark set for weak interactions between aminoacids in proteins, if it exists. [(Marcos Veríssimo Alves)](https://www.linkedin.com/feed/update/urn:li:activity:7203787267348267008?commentUrn=urn%3Ali%3Acomment%3A%28activity%3A7203787267348267008%2C7203843329195675649%29&dashCommentUrn=urn%3Ali%3Afsd_comment%3A%287203843329195675649%2Curn%3Ali%3Aactivity%3A7203787267348267008%29)
 


## ⚖️ Ethics and Dual Use Concerns
Ensuring safe usage of data is of paramount concern, especially for the chemistry data included in this list. We encourage all users of these data to read papers by e.g., Gabe Gomes et al. [1,2] on the potential dangers of dual use before constructing their datasets or models. If you have concerns about potential dual use of any of the datasets listed, create an issue and we will do our best to evaluate the safety concerns, remove the data, or consult with outside experts if necessary.

[1] [Emergent autonomous scientific research capabilities of large language models](https://arxiv.org/2304.05332)
[2] [Censoring chemical data to mitigate dual use risk](https://arxiv.org/2304.10510).

## 🤝 Contributing Guidelines
Add other resources to the list by: 
1. forking the repository and creating a pull request back to the main repository or,
2. creating an issue with the markdown that should be added to the repository and one of the admins will add to the main document.

If you would like to help maintain this repository, open an issue expressing your interest and we will reach out to you!

