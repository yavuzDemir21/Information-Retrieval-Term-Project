To run Stanford Parser follow the instructions from here

https://github.com/nltk/nltk/wiki/Stanford-CoreNLP-API-in-NLTK

java -mx4g -cp "*" edu.stanford.nlp.pipeline.StanfordCoreNLPServer -preload tokenize,ssplit,pos,lemma,ner,parse,depparse -status_port 9000 -port 9000 -timeout 15000 &

BioWordVec Model can be downloaded from

https://github.com/ncbi-nlp/BioSentVec