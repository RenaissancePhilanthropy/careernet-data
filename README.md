# CareerNet

CareerNet is a [Renaissance Philanthropy](https://www.renaissancephilanthropy.org/)-led project to develop three state-of-the-art benchmark datasets, leveraging [CareerVillage.org](https://www.careervillage.org/), a platform that has crowdsourced career advice. Selecting data from over 60,000 questions and more than 3.5 million learners, the project aims to enhance AI’s ability to guide users in navigating careers and accessing social benefits.

Renaissance partnered with [The Learning Agency](https://the-learning-agency.com/) to implement this AI benchmarking effort and the annotated datasets designed for AI model development and targeted for applications, supporting the career trajectory and upward mobility of lower-income individuals with a particular focus on reskilling, technical occupations, and allied health occupations.

Career navigator questions and crowd-sourced professional answer data from three domains (general/reskilling, technology, and healthcare) were annotated for three quality scales (correctness, completeness, and coherency), goal identification (the goal of the question asker), scenarios (career aspects being asked about), Standard Occupational Classification (SOC) codes, and answer reasoning.

Details regarding the data, sampling, and annotation can be found in the [Data Details PDF](<https://github.com/RenaissancePhilanthropy/careernet-data/blob/main/Data-Details%20v1.1.pdf>).

The [codebook for each domain](https://github.com/RenaissancePhilanthropy/careernet-data/tree/main/Codebooks) includes the variables, variable types, variable descriptions, missing quantities, values, and value frequencies for each.

The [Notebooks folder](https://github.com/RenaissancePhilanthropy/careernet-data/tree/main/Notebooks) includes Jupyter notebooks for working with the data: two that add U.S. Bureau of Labor Statistics labor market information (employment and wages) to CareerNet by SOC code, at the national/state level or the metro/non-metro area level, and a Google Colab notebook for searching the questions and answers by meaning and asking a chat model career questions using CareerNet answers.

The [CareerNet app](https://renaissancephilanthropy.github.io/careernet-app/) lets you explore the data in your browser, with no setup: a dashboard linking SOC codes to labor market information and to the other CareerNet annotations (answer quality, scenarios, and goals), and a search of the questions and answers by meaning. Its code is in the [careernet-app repository](https://github.com/RenaissancePhilanthropy/careernet-app).

Version 1.1 adds Standard Occupational Classification (SOC) codes and answer reasoning labels to the datasets, notebooks for integrating U.S. Bureau of Labor Statistics labor market information (LMI), and a retrieval-augmented generation (RAG) notebook for searching and chatting with the data.

The CareerNet data is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://github.com/RenaissancePhilanthropy/careernet-data/blob/main/LICENSE.txt).

Want to learn more about CareerNet and be notified about potential information sessions? Please fill out [this form](https://form.fillout.com/t/1P8xyj5S2Dus).

Questions regarding the data can be directed to <ulrich@renphil.org>
