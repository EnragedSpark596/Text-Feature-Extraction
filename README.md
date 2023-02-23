# Text-Feature-Extraction
Jupyter notebook that reads from a group of text files, extracts and sorts words

Objective: find commonest words that are unique to single doc
so that document themes can be inferred without user having to read them

# 1.0 Imports
# 2.0 Functions
    # getText
# 3.0 Global variables
    # filepath
    # filenames
    # docName
    # stem.verbs = [verb_stems.txt1, verb_stems.txt2, etc.]    - document-specific unique list of text strings
    # nouns = [doc.1_nouns, doc.2_nouns, etc.]                 - list of nouns unique to each doc
    # adj = [doc1.adj, etc]
    # adv = [doc1.adv, etc]
    
# 4.0 set-up - populate docNames with text file contents
# 5.0 Clean docNames[files] ready for spacy, TF-IDF: -each txt file should have a vocab list of stem_verbs, nouns, adj, adv
    # make content lower case
    # remove stopwords and dropwords
    # remove punctuation
# 6.0 prep for POS extraction
    # spacy
#7.0 Gather bulk data
    # make a corpus from all 8 files
#8.0 All Text
    # make a word-set (vocab of unique words) of the corpus
    # manual Term Frequeny calc
    # manual inverse document frequency (IDF) calc
    # apply sklearn TfidfVectorizer
# 9.0 Nouns
    # make a corpus from all 8 files
    # make a word-set (vocab of unique words) of the corpus
    # manual Term Frequeny calc
    # manual inverse document frequency (IDF) calc
    # apply sklearn TfidfVectorizer
# 10.0 Verbs
    # make a corpus from all 8 files
    # make a word-set (vocab of unique words) of the corpus
    # manual Term Frequeny calc
    # manual inverse document frequency (IDF) calc
    # apply sklearn TfidfVectorizer
# 11.0 Adjs and Advs
    # make a corpus from all 8 files
    # make a word-set (vocab of unique words) of the corpus
    # manual Term Frequeny calc
    # manual inverse document frequency (IDF) calc
    # apply sklearn TfidfVectorizer
