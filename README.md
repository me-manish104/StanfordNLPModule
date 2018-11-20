# StanfordNLPModule

 Note : jar file stanford-core-nlp-3.8 models.jar needs to be added explicitly in the class path,as there is 
 * no standard way to specify a classifier.
 * 
 * In case of maven projects, <classifier>models</classifier> needs to be specified in core-nlp dependency
 * 
 * Basic program to understand the various tagging techniques offered by Standford NLP library.
 * 
 * 
 * Tagging includes POS, NER,
 * 
 * Pipeline of ("annotators", "tokenize, ssplit, pos, lemma, ner, parse, dcoref") is 
 * created and the text is passed through it.
 * 
 * The text can also be passed through individual models as well like ner
 * 
 * 
 * 
 * {@link https://interviewbubble.com/getting-started-with-stanford-corenlp-a-stanford-corenlp-tutorial/}
 * 
 * {@link https://interviewbubble.com/getting-started-with-stanford-corenlp/}
