# twitter_education_gender

This repository contains the code and the datasets used in the article titled: Topic modeling of twitter data to identify issues impacting women and girls’ education during the COVID-19 pandemic

Use the code is the following order:

1. Use the file 'Download_twitter_data.Rmd' to specify Twitter access keys and secrets and then download data for particilar twitter handles
2. Use the LDA_Gensim.ipynb to undertake LDA on the downloaded data and to identify topics. The output from the topic modelling is saved in a file called "output.csv"
3. Use Process_gensim_output.Rmd to load Output.csv generated in the step above. This script will process the output generated from topic modelling and create the datasets for the specific analysis.
4. Use Script_output_Figures.Rmd to generate the figures / plots used in the brief
5. The datasets generate from step 3 are also added in the repository titled: data_wordcloud.csv, data_fig_2.csv adn data_fig_3.csv
