
Installation 
First install basic packages :

  pip install -r requirements.txt


Then check your cuda version with:
  $nvidia-smi


Next you can install spacy-cuda as follows:

  pip install -U pip setuptools wheel
  pip install -U spacy[cuda110]
  python -m spacy download en_core_web_trf


After completing installation you can run: 
  CreateSpacyTrainingData.pynb
  
and

  NERSpacy.ipynb

For building training data and performing Entity recognition.

