## Understanding Cultures and Perspectives through Text and Emoji Visualization
## Jason S. Kessler (CDK Global)
### #ddsea17: October 20, 2017

This talk is about visualizing how language differs across groups and categories.  

Two Python libraries I've developed, Scattertext and AgeFromName, are heavily used in the talk.

Please install them and if you have time, star them on Github:

- [Scattertext](https://github.com/JasonKessler/scattertext)
- [AgeFromName](https://github.com/JasonKessler/agefromname)

`$ pip install scattertext agefromname && python -m spacy.en.download`

It's news you can use: six Python 3.6 Jupyter notebooks showing how to visualize the following data:

- [Introduction to Scattertext](https://nbviewer.jupyter.org/github/JasonKessler/NLPDaySeattle2017/blob/master/Scattertext-Intro-Part-1.ipynb)
- [Analyzing President Trump's Twitter stream before and after the election](https://nbviewer.jupyter.org/github/JasonKessler/NLPDaySeattle2017/blob/master/President-Trump-Twitter-Analysis-Part-2.ipynb)
- [Using Scattertext to visualize Emoji usage by gender and heritage on Twitter](https://nbviewer.jupyter.org/github/JasonKessler/NLPDaySeattle2017/blob/master/Emoji-Gender-Heritage-Part-4.ipynb)
- [Using Scattertext to visualize Emoji usage by language (e.g., English or Spanish) on Twitter](https://nbviewer.jupyter.org/github/JasonKessler/NLPDaySeattle2017/blob/master/Emoji-and-Language-In-the-US-Part-5.ipynb)
- [Visualizing how Emojis vary by nationality](https://nbviewer.jupyter.org/github/JasonKessler/NLPDaySeattle2017/blob/master/Emoji-and-Nationality-Part-6.ipynb)

## Recent related computational linguistic work in demography

Imputing demographics from text is a long-standing problem in computational linguistics.  Argamon et al. (2009) provides an overview of earlier psycholinguistic work on language and demography by Pennebaker and Argamon.

Bergsma et al. (2013) built highly accurate race, gender, language and ethnicity classifiers, all using a Twitter user's first and last names as input.

Lee et al. (2017) use lists of Olympic athletes to train an RNN to predict nationality and ethnicity from an athlete's name.  Ethnicity is imputed from nationality in this work, with the majority ethnicity from each nation treated as a label, reducing the veracity of data derived from diverse countries.

Dong et al. (2013) predict age from the content of a Twitter user's tweets. Users were manually annotated for age-range and gender.  Annotators looked through a user's social media profiles (e.g., their Linkedin profiles) to figure out a user's approximate age or gender. They found that the language used in a user's tweets is predictive of life-stages, and that language varied by gender.

Montasser et al. (2017) accurately predict gender/race/ethnicity demographics of a US census tract, block, blockgroup, or county from bag-of-words features from geotagged tweet-content.

## References 

Shlomo Argamon, Moshe Koppel, James W. Pennebaker, Jonathan Schler .Automatically Profiling the Author of an Anonymous Text. CACM. 2009. http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.136.9952&rep=rep1&type=pdf

Shane Bergsma, Mark Dredze, Benjamin Van Durme, Theresa Wilson, David Yarowsky. Broadly Improving User Classification via Communication-Based Name and Location Clustering on Twitter. NAACL-HLT 2013. http://www.aclweb.org/anthology/N/N13/N13-1121.pdf

Omar Montasser, Daniel Kifer. Predicting Demographics of High-Resolution Geographies with Geotagged Tweets. AAAI. 2017.

Jinhyuk Lee, Hyunjae Kim, Miyoung Ko, Donghee Choi, Jaehoon Choi, Jaewoo Kang. Name Nationality Classification with Recurrent Neural Networks. IJCAI-17. 2017. https://www.ijcai.org/proceedings/2017/0289.pdf

Dong Nguyen, Rilana Gravel, Dolf Trieschnigg, Theo Meder. “How Old Do You Think I Am?”: A Study of Language and Age in Twitter. ICWSM. 2013. http://www.dongnguyen.nl/publications/nguyen-icwsm2013.pdf


