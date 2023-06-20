# doescashflow
We benefit immensely from the publicly available works of Gürkaynak, Karasoy-Can, and Lee (2022). We extend our gratitude to Gürkaynak, Karasoy-Can, and Lee (2022) for their fearless endeavour and their commitment to the study of the impacts of monetary policy so much so that they provided their code, word-list and methodology fit for our critique. We follow in their footsteps and provide our code and findings for future research and critique. We are limited on the extent of the code and information we can share as most of our data is proprietary. We explain:
1. We provide the excel macros file (03 Exposure creation document.xlsm) that we deploy to develop our exposure variable. The files downloaded from S&P Capital IQ under Capital structure details for each company are proprietary. We provide a dummy sample (10.xls) for ease of visualisation. These files can be downloaded and the macros deployed on the downloaded files.
2. We use sec-api to download data from SEC-Edgar database. The code used is a modified version of that provided by sec-api. Through developing the hedge variable we tested differences of the text files or html files downloaded from sec-api vs those downloaded from Notre-Dame university website (https://sraf.nd.edu/sec-edgar-data/) and find that the latters information is free and similar in all aspects. We therefore do not provide this code.
3. We provide the code used in the creation of the hedge variable (04 Final Read Hedge.ipynb) and the hedge variable created (Hedge variable.csv).
4. We provide the code and methodology employed to derive the raw GSS-factors which are used to develop the final GSS factors as previously described. The development of the final GSS factors is done using a modification of the code provided by Gürkaynak, Sack, and Swanson (2007). The code provided is stored under the name 05 GSS Factor derivation.ipnyb //

All other methodology cannot be provided without a violation of protections for proprietary data. The code and methodology is provided under www.github.com.
