# internship_keywords
4/11/2021 working summary 


- Dataset: 
https://www.americanrhetoric.com/speeches/convention2004/barackobama2004dnc.htm

- Things to do: 
  - Audio preprocessing:
    - Convert the dataset into wav format, by using pydub library 
    - Break the audio into smaller size (to avoid error) 
  - Predict text from audio:  
    - By using wav2vec2.0 to convert the audio into text
  - Extract keywords from the text: 
    - By using spacy, rake,bert,yake library 
      Note: spacy is much easier 


- Reference: 
  - https://towardsdatascience.com/how-to-extract-keywords-from-audio-files-with-natural-language-processing-nlp-3084ceb951c9
  - https://towardsdatascience.com/keyword-extraction-process-in-python-with-natural-language-processing-nlp-d769a9069d5c
