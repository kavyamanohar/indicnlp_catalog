
# A Catalog of resources for Indian language NLP

_Please suggest any other resources you may be aware of. Raise a pull request or an issue to add more resources to the catalog. Put the proposed entry in the following format:_

  \[Wikipedia Dumps\]\(https://dumps.wikimedia.org/)

_Add a small, informative description of the dataset and provide links to any paper/article/site documenting the resource. Mention your name too. We would like to acknowlege your contribution to building this catalog in the [CONTRIBUTORS](CONTRIBUTORS.md) list._

:new: Added _Evaluation Benchmarks_ sections

:+1: **Featured Resources**

- [IIT Bombay English-Hindi Parallel Corpus](http://www.cfilt.iitb.ac.in/iitb_parallel/): Largest en-hi parallel corpora in public domain (about 1.5 million semgents)
- [CVIT-IIITH PIB Multilingual Corpus](http://preon.iiit.ac.in/~jerin/resources/datasets/pib-v0.tar): Mined from Press Information Bureau for many Indian languages. Contains both English-IL and IL-IL corpora (IL=Indian language).
- [CVIT-IIITH Mann ki Baat Corpus](http://preon.iiit.ac.in/~jerin/resources/datasets/mkb-v0.tar): Mined from Indian PM Narendra Modi's _Mann ki Baat_ speeches.
- [AI4Bharat IndicNLP Project](https://github.com/ai4bharat/indicnlp_corpus): Text corpora, word embeddings, text classification datasets for Indian languages. 
- [iNLTK](https://github.com/goru001/inltk): iNLTK aims to provide out of the box support for various NLP tasks that an application developer might need for Indic languages.
- [Dakshina Dataset](https://github.com/google-research-datasets/dakshina): The Dakshina dataset is a collection of text in both Latin and native scripts for 12 South Asian languages. Contains an aggregate of around 300k word pairs and 120k sentence pairs. Useful for transliteration.

**Browse the entire catalog...**

:raising_hand:**Note**: Many known resources have not yet been classified into the catalog. They can be found as open issues in the repo.
	
<!-- vscode-markdown-toc -->
* [Major Indic Language NLP Repositories](#MajorIndicLanguageNLPRepositories)
* [Libraries](#Libraries)
* [Evaluation Benchmarks](#Benchmarks)
* [Standards](#Standards)
* [Text Corpora](#TextCorpora)
	* [Unicode Standard](#UnicodeStandard)
	* [Monolingual Corpus](#MonolingualCorpus)
	* [Language Identification](#LanguageIdentification)	
	* [Lexical Resources](#LexicalResources)
	* [NER Corpora](#NERCorpora)
	* [Parallel Translation Corpus](#ParallelTranslationCorpus)
	* [Parallel Transliteration Corpus](#ParallelTransliterationCorpus)
	* [Textual Entailment](#TextualEntailment)
	* [Paraphrase](#Paraphrase)
	* [Sentiment, Sarcasm, Emotion  Analysis](#SentimentAnalysis)
	* [Question Answering](#QuestionAnswering)
	* [Dialog](#Dialog)
	* [Discourse](#Discourse)
	* [POS Tagged corpus](#POSTaggedcorpus)
	* [Chunk Corpus](#ChunkCorpus)
	* [Dependency Parse Corpus](#DependencyParseCorpus)
* [Models](#Models)
	* [Word Embeddings](#WordEmbeddings)
	* [Sentence Embeddings](#SentenceEmbeddings)
	* [Multilingual Word Embeddings](#MultilingualWordEmbeddings)
	* [Morphanalyzers](#Morphanalyzers)
	* [SMT Models](#SMTModels)
* [Speech Corpora](#SpeechCorpora)
* [OCR Corpora](#OCRCorpora)
* [Multimodal Corpora](#MultimodalCorpora)
* [Language Specific Catalogs](#LanguageSpecificCatalogs)	


<!-- vscode-markdown-toc-config
	numbering=false
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->


## <a name='MajorIndicLanguageNLPRepositories'></a>Major Indic Language NLP Repositories

- [Technology Development for Indian Languages (TDIL)](http://tdil-dc.in)
- [Center for Indian Language Technology (CFILT)](http://www.cfilt.iitb.ac.in/)
- [Language Technologies Research Center (LTRC)](https://ltrc.iiit.ac.in/download.php)
- [Linguistic Data Consortium For Indian Languages (LDCIL)](https://data.ldcil.org)
- [University of Hyderabad - Sanskrit NLP](http://sanskrit.uohyd.ac.in/scl)


## <a name='Libraries'></a>Libraries

- [Indic NLP Library](https://github.com/anoopkunchukuttan/indic_nlp_library): Python Library for various Indian language NLP tasks like tokenization, sentece splitting, normalization, script conversion, transliteration, _etc_
- [pyiwn](https://github.com/riteshpanjwani/pyiwn): Python Interface to IndoWordNet
- [Indic-OCR](https://indic-ocr.github.io/) : OCR for Indic Scripts
- [CLTK](https://github.com/cltk/cltk/tree/master/cltk): Toolkit for many of the world's classical languages. Support for Sanskrit. Some parts of the Sanskrit library are forked from the Indic NLP Library.
- [iNLTK](https://github.com/goru001/inltk): iNLTK aims to provide out of the box support for various NLP tasks that an application developer might need for Indic languages.

## <a name='Benchmarks'></a>Evaluation Benchmarks

Benchmarks spanning multiple tasks.

- [GLUECoS](https://microsoft.github.io/GLUECoS): For Hindi-English code-mixed data containing the following tasks - Language Identification (LID), POS Tagging (POS), Named Entity Recognition (NER), Sentiment Analysis (SA), Question Answering (QA), Natural Language Inference (NLI).
- [AI4Bharat Text Classification](https://github.com/ai4bharat/indicnlp_corpus#publicly-available-classification-datasets): A compilation of classification datasets for 10 languages.

## <a name='Standards'></a>Standards

- Unicode Standard for Indic Scripts
   - [An Introduction to Indic Scripts](https://www.w3.org/2002/Talks/09-ri-indic/indic-paper.pdf)
   - [Unicode Standard for South Asian Scripts](http://www.unicode.org/versions/Unicode12.1.0/ch12.pdf)

## <a name='TextCorpora'></a>Text Corpora

### <a name='MonolingualCorpus'></a>Monolingual Corpus

- [Wikipedia Dumps](https://dumps.wikimedia.org/)
- Common Crawl
	- [OSCAR Corpus](https://traces1.inria.fr/oscar): Released in 2019, large-scaled processed CommonCrawl.	
	- [WMT Common Crawl Dumps](http://data.statmt.org/ngrams/raw): Crawls between 2012 and 2016. Noisy text, needs to be filtered.
- [WMT NEWS Crawl](http://data.statmt.org/news-crawl)
- [LDCIL Monolingual Corpus](https://data.ldcil.org)
- [Charles University Hindi Monolingual Corpus](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0023-625F-0)
- [Charles University Urdu Monolingual Corpus](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0023-65A9-5)
- [IIT Bombay Hindi Monolingual Corpus](http://www.cfilt.iitb.ac.in/iitb_parallel/iitb_corpus_download/monolingual.hi.tgz)
- [EMILLE Corpus (multiple Indian languages)](https://www.lancaster.ac.uk/fass/projects/corpus/emille/)
- [Janmabhumi Malayalam Corpus](https://github.com/ABHISHEKVALSAN/Malayalam-Newspaper-Article-Dataset)
- [Leipzig Corpus](http://wortschatz.uni-leipzig.de/en/download/)
- [Sanskrit Monolingual and Sandhi-split Corpus](http://sanskrit.uohyd.ac.in/Corpus/)
- [Lot Of Indic Tweets Corpus](https://github.com/bedapudi6788/LOIT): Large twitter datasets for telugu (7.9 million) and hindi (17.6 million) and fasttext skipgram and cbow word vectors for the same.
- [CMU Romanized Hinglish Corpus](https://github.com/khyathiraghavi/multi_task_code_switched_language_modeling/tree/master/hinglishData): See [THIS PAPER](https://www.aclweb.org/anthology/W18-3211.pdf) for details. 
- [JNU-BHLTR Bhojpuri Corpus](https://github.com/shashwatup9k/bho-resources/tree/master/mono-bho-corpus): Bhojpuri corpus of 45k sentences.
- [KMI Magahi Corpus](https://github.com/kmi-linguistics/magahi): 
- [KMI Awadhi Corpus](https://github.com/kmi-linguistics/awadhi): 

### <a name='LanguageIdentification'></a>Language Identification

- [VarDial 2018 Language Identification Dataset](https://github.com/kmi-linguistics/vardial2018): 5 languages - Hindi, Braj, Awadhi, Bhojpuri, Magahi.

### <a name='LexicalResources'></a>Lexical Resources

- [IndoWordNet](http://www.cfilt.iitb.ac.in/indowordnet/)
- [IIIT-Hyderabad Word Similarity Database](https://github.com/syedsarfarazakhtar/Word-Similarity-Datasets-for-Indian-Languages): 7 Indian languages
- [Facebook Hindi Analogy Dataset](https://dl.fbaipublicfiles.com/fasttext/word-analogies/questions-words-hi.txt)
- [MGAD Hindi Analogy dataset](https://github.com/rutrastone/MGAD)
- [AI4Bharat Word Frequency Lists](https://github.com/AI4Bharat/indicnlp_corpus#text-corpora): Tokens and their frequencies from the AI4Bharat corpus, a large monolingual corpus.

### <a name='NERCorpora'></a>NER Corpora

- [FIRE 2013 AUKBC NER Corpus](http://au-kbc.org/nlp/NER-FIRE2013)
- [FIRE 2014 AUKBC NER Corpus](http://www.au-kbc.org/nlp/NER-FIRE2014/)
- [IIT Bombay Marathi NER Corpus](http://www.cfilt.iitb.ac.in/ner/download_data.html)
- [WikiAnn NER Corpus](http://nlp.cs.rpi.edu/wikiann/) (_Noisy_)
- [a-mma NER data](https://github.com/a-mma/NER_Open_Data)

### <a name='ParallelTranslationCorpus'></a>Parallel Translation Corpus

- [IIT Bombay English-Hindi Parallel Corpus](http://www.cfilt.iitb.ac.in/iitb_parallel/): Largest en-hi parallel corpora in public domain (about 1.5 million semgents)
- [CVIT-IIITH PIB Multilingual Corpus](http://preon.iiit.ac.in/~jerin/resources/datasets/pib-v0.tar): Mined from Press Information Bureau for many Indian languages. Contains both English-IL and IL-IL corpora (IL=Indian language).
- [CVIT-IIITH Mann ki Baat Corpus](http://preon.iiit.ac.in/~jerin/resources/datasets/mkb-v0.tar): Mined from Indian PM Narendra Modi's _Mann ki Baat_ speeches.
- [PMIndia](http://data.statmt.org/pmindia): Parallel corpus for En-Indian languages mined from _Mann ki Baat_ speeches of the PM of India ([paper](https://arxiv.org/abs/2001.09907)).
- [Indian Language Corpora Initiative](http://sanskrit.jnu.ac.in/ilci/index.jsp): Available on TDIL portal on request
- [OPUS corpus](http://opus.nlpl.eu/)
- [WAT 2018 Parallel Corpus](http://lotus.kuee.kyoto-u.ac.jp/WAT/indic-multilingual/index.html): There may significant overlap between WAT and OPUS.
- [Charles University English-Hindi Parallel Corpus](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0001-BD17-1): This is included in the IITB parallel corpus.
- [Charles University English-Tamil Parallel Corpus](http://ufal.mff.cuni.cz/~ramasamy/parallel/html/)
- [Charles University English-Odia Parallel Corpus v1.0](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-2879)
- [Charles University English-Odia Parallel Corpus v2.0](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-3211)
- [Charles University English-Urdu Religious Parallel Corpus](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-2582)
- [IndoWordnet Parallel Corpus](https://github.com/anoopkunchukuttan/indowordnet_parallel): Parallel corpora mined from IndoWordNet gloss and/or examples for Indian-Indian language corpora  (6.3 million segments, 18 languages). 
- [MTurk Indian Parallel Corpus](https://github.com/joshua-decoder/indian-parallel-corpora)
- [TED Parallel Corpus](https://github.com/ajinkyakulkarni14/TED-Multilingual-Parallel-Corpus)
- [JW300 Corpus](http://opus.nlpl.eu/JW300.php): Parallel corpus mined from jw.org. Religious text from Jehovah's Witness. 
- [ALT Parallel Corpus](http://www2.nict.go.jp/astrec-att/member/mutiyama/ALT): 10k sentences for Bengali, Hindi in parallel with English and many East Asian languages.
- [FLORES dataset](https://github.com/facebookresearch/flores): English-Sinhala and English-Nepali corpora
- [Uka Tarsadia University Corpus](https://github.com/shahparth123/eng_guj_parallel_corpus): 65k English-Gujarati sentence pairs. Corpus is described in [this paper](https://arxiv.org/abs/2002.02758)
- [NLPC-UoM English-Tamil Corpus](https://github.com/nlpc-uom/English-Tamil-Parallel-Corpus): 9k sentences, 24k glossary terms
- [English-Tamil Wiki Titles](http://data.statmt.org/wikititles/v2/wikititles-v2.ta-en.tsv.gz): from statmt
- [JNU-BHLTR Bhojpuri Corpus](https://github.com/shashwatup9k/bho-resources): English-Bhojpuri corpus of 65k sentences
- [EILMT Corpus](http://tdil-dc.in/index.php?searchword=EILMT&searchphrase=all&option=com_search&lang=en)
- [QED Corpus](http://alt.qcri.org/resources/qedcorpus): English-Hindi corpus of 43k sentences from the educational domain.
- [WikiMatrix Corpus](https://ai.facebook.com/blog/wikimatrix): Mined from Wikipedia, looks noisy.
- [CCMatrix](https://github.com/facebookresearch/LASER/tree/master/tasks/CCMatrix): Parallel corpus mined from CommonCrawl, looks noisy.

### <a name='ParallelTransliterationCorpus'></a>Parallel Transliteration Corpus

- [Dakshina Dataset](https://github.com/google-research-datasets/dakshina): The Dakshina dataset is a collection of text in both Latin and native scripts for 12 South Asian languages. Contains an aggregate of around 300k word pairs and 120k sentence pairs.
- [BrahmiNet Corpus](http://www.cfilt.iitb.ac.in/brahminet/static/download.html): 110 language pairs mined from ILCI parallel corpus.
- [Xlit-Crowd](https://github.com/anoopkunchukuttan/crowd-indic-transliteration-data): Hindi-English Transliteration Corpus created via crowdsourcing.
- [Xlit-IITB-Par](http://www.cfilt.iitb.ac.in/iitb_parallel/supplementary_resources/xlit-iitb-par.tgz): Hindi-English Transliteration Corpus mined from parallel translation corpora.
- [FIRE 2013 Track on Transliterated Search](https://cse.iitkgp.ac.in/resgrp/cnerg/qa/fire13translit/index.html): Transliteration dataset of native words in Hindi, Bengali and Gujarati.
- [NEWS 2016 Shared Task dataset](http://workshop.colips.org/news2016/dataset.html): Transliteration datasets for Kannada, Tamil, Bengali and Hindi created by Microsoft Research India.
- [NotAI-tech English-Telugu](https://github.com/notAI-tech/Datasets/tree/master/En-Te_Transliteration): Around 38k word pairs

### <a name='TextualClassification'></a>Text Classification

- [BBC news articles classification dataset](https://github.com/NirantK/hindi2vec/releases/tag/bbc-hindi-v0.1): 14 class classification
- [iNLTK News Headlines classification](https://github.com/goru001/inltk): Datasets for multiple Indian languages.
- [AI4Bharat IndicNLP News Articles](https://github.com/ai4bharat/indicnlp_corpus): Word embeddings for 10 Indian languages.

### <a name='TextualEntailment'></a>Textual Entailment

- [XNLI corpus](https://github.com/facebookresearch/XNLI): Hindi and Urdu test sets and machine translated training sets (from English MultiNLI).

### <a name='Paraphrase'></a> Paraphrase

- [Amrita University-DPIL Corpus](https://nlp.amrita.edu/dpil_cen/index.html): Sentence level paraphrase identification for four Indian languages (Tamil, Malayalam, Hindi and Punjabi).

### <a name='SentimentAnalysis'></a>Sentiment, Sarcasm, Emotion Analysis

- [IIT Bombay movie review datasets for Hindi and Marathi](http://www.cfilt.iitb.ac.in/Sentiment_Analysis_Resources.html)
- [IIT Patna movie review datasets for Hindi](http://www.iitp.ac.in/~ai-nlp-ml/resources.html)
- [IIIT-H LTRC Multi-domain dataset for Telugu](https://ltrc.iiit.ac.in/showfile.php?filename=downloads/sentiraama/)
- [ACTSA corpus for Telugu](https://github.com/NirantK/bharatNLP/releases)
- [BHAAV (भाव) Corpus](https://doi.org/10.5281/zenodo.3457467): A Text Corpus for Emotion Analysis from Hindi Stories

### <a name='QuestionAnswering'></a>Question Answering
- [Facebook Multilingual QA datasets](https://github.com/facebookresearch/MLQA): Contains dev and test sets for Hindi.
- [TyDi QA datasets](https://github.com/google-research-datasets/tydiqa): QA dataset for Bengali and Telugu.
- [bAbi 1.2 dataset](http://www.thespermwhale.com/jaseweston/babi/tasks_1-20_v1-2.tar.gz): Has Hindi version of bAbi tasks in romanized Hindi.
- [MMQA dataset](https://github.com/deepaknlp/MMQA): Hindi QA dataset described in [this paper](https://www.aclweb.org/anthology/L18-1440.pdf)
- [XQuAD](https://github.com/deepmind/xquad): testset for Hindi QA from human translation of subset of SQuAD v1.1. Described in [this paper](https://arxiv.org/abs/1910.11856)
- [XQA](http://github.com/thunlp/XQA): testset for Tamil QA. Described in [this paper](https://www.aclweb.org/anthology/P19-1227.pdf)

### <a name='Dialog'></a>Dialog
- [a-mma Indic Casual Dialogs Datasets](https://github.com/a-mma/indic_casual_dialogs_dataset)

### <a name='Discourse'></a>Discourse
- [MIDAS-Hindi Discourse Analysis](https://github.com/midas-research/hindi-discourse)

### <a name='Information Extraction'></a>Information Extraction
- [EventXtract-IL](http://78.46.86.133/EventXtractionIL-FIRE2018): Event extraction for Tamil and Hindi. Described in [this paper](http://ceur-ws.org/Vol-2266/T5-1.pdf).

### <a name='POSTaggedcorpus'></a>POS Tagged corpus

- [Indian Language Corpora Initiative](http://sanskrit.jnu.ac.in/ilci/index.jsp)
- [Universal Dependencies](https://universaldependencies.org/)
- [Code Mixed Dataset for Hindi, Bengali and Telugu, ICON 2016 shared task](https://amitavadas.com/Code-Mixing.html)
- [JNU-BHLTR Bhojpuri Corpus](https://github.com/shashwatup9k/bho-resources/tree/master/mono-bho-corpus): Bhojpuri corpus of 5000 sentences.
- [KMI Magahi Corpus](https://github.com/kmi-linguistics/magahi): 
- [KMI Awadhi Corpus](https://github.com/kmi-linguistics/awadhi): 

### <a name='ChunkCorpus'></a>Chunk Corpus

- [Indian Language Corpora Initiative](http://sanskrit.jnu.ac.in/ilci/index.jsp)

### <a name='DependencyParseCorpus'></a>Dependency Parse Corpus

- [IIIT Hyderabad Hindi Treebank](http://tdil-dc.in/index.php?option=com_download&task=showresourceDetails&toolid=1977&lang=en)
- [Universal Dependencies](https://universaldependencies.org/)
- [Universal Dependencies Hindi Treebank](https://github.com/UniversalDependencies/UD_Hindi-HDTB)
- [Universal Dependencies Urdu Treebank](https://github.com/UniversalDependencies/UD_Urdu-UDTB)

## <a name='Models'></a>Models

### <a name='WordEmbeddings'></a>Word Embeddings

- [FastText CommonCrawl+Wikipedia](https://fasttext.cc/docs/en/crawl-vectors.html)
- [FastText Wikipedia](https://fasttext.cc/docs/en/pretrained-vectors.html)
- [Polyglot](https://sites.google.com/site/rmyeid/projects/polyglot)
- [AI4Bharat IndicNLP Project](https://github.com/ai4bharat/indicnlp_corpus): Word embeddings for 10 Indian languages.

### <a name='SentenceEmbeddings'></a>Sentence Embeddings

- [BERT Multilingual](https://github.com/google-research/bert): BERT model trained on Wikipedias of many languages (including major Indic languages).
- [iNLTK](https://github.com/goru001/inltk): ULMFit and TransformerXL pre-trained embeddings for many languages trained on Wikipedia and some News articles. 
- [albert-base-sanskrit](https://huggingface.co/surajp/albert-base-sanskrit): ALBERT-based model trained on Sanskrit Wikipedia.
- [RoBERTa-hindi-guj-san](https://huggingface.co/surajp/RoBERTa-hindi-guj-san): Multilingual RoBERTa like model trained on Hindi, Sanskrit and Gujarati.

### <a name='MultilingualWordEmbeddings'></a>Multilingual Word Embeddings

- [GeoMM](https://github.com/anoopkunchukuttan/geomm)
- [Babylon Partners](https://github.com/Babylonpartners/fastText_multilingual)

### <a name='Morphanalyzers'></a>Morphanalyzers

- [AI4Bharat IndicNLP Project](https://github.com/ai4bharat/indicnlp_corpus): Unsupervised morphanalyzers for 10 Indian languages learnt using morfessor.

### <a name='SMTModels'></a>SMT Models

- [Shata-Anuvaadak](http://www.cfilt.iitb.ac.in/~moses/shata_anuvaadak/): 110 language pairs
- [LTRC Vanee](https://ltrc.iiit.ac.in/downloads/tools/Vaanee.tgz): Dependency based Statistical MT system from English to Hindi

## <a name='SpeechCorpora'></a>Speech Corpora

- [Microsoft Speech Corpus](https://msropendata.com/datasets/7230b4b1-912d-400e-be58-f84e0512985e): Speech corpus for Telugu, Tamil and Gujarati.
- [Microsoft-IITB Marathi Speech Corpus](https://www.cse.iitb.ac.in/~pjyothi/indiccorpora/#marathi): 109 hours of speech data collected via crowdsourcing.
- [AccentDB](https://accentdb.org/): Database of Indian English accents from native speakers in Bangla, Malayalam, Telugu and Oriya. 
- [IIT Madras TTS database](https://www.iitm.ac.in/donlab/tts/index.php)
- [BABEL Speech Corpus](https://en.wikipedia.org/wiki/BABEL_Speech_Corpus): includes some Indian languages
- [Pratham ASER dataset](https://github.com/shashwatup9k/bho-resources): Dataset for research on reading level assessment.
- [WikiPron](https://pypi.org/project/wikipron/): Words and their pronunciations in IPA mined from Wiktionary. Includes Indian languages. [paper](https://www.aclweb.org/anthology/2020.lrec-1.521)
- [CVIT IndicSpeech](http://cvit.iiit.ac.in/research/projects/cvit-projects/text-to-speech-dataset-for-indian-languages): TTS data for 3 Indian languages: Malayalam, Bengali and Hindi (24 hours each).


## <a name='OCRCorpora'></a>OCR Corpora

- [Kannada MNIST](https://www.kaggle.com/higgstachyon/kannada-mnist)

## <a name='MultimodalCorpora'></a>Multimodal Corpora

- [English-Hindi Visual Genome](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-2997): Images captioned in both English and Hindi.
- [English-Hindi Flickr 8k](https://arxiv.org/pdf/2004.11954.pdf): A subset of images from [Flickr8k](https://jair.org/index.php/jair/article/view/10833) images captioned by native speakers in both English and Hindi. Code and data available [here](https://github.com/madaan/PML4DC-Comparable-Data-Collection).

## <a name='LanguageSpecificCatalogs'></a>Language Specific Catalogs 

 Pointers to language-specific NLP resource catalogs
 
 - [Odia](https://github.com/shantipriyap/Odia-NLP-Resource-Catalog)
