
Installation 
First install basic packages :
```bash
  pip install -r requirements.txt
```

Then check your cuda version with:
```bash
  $nvidia-smi
```

Next, you can install spacy-cuda as follows:
```bash
  pip install -U pip setuptools wheel
  pip install -U spacy[cuda110]
  python -m spacy download en_core_web_trf
```

After completing installation, you should run the notebooks in this order:
```
  CreateSpacyTrainingData.pynb
  NERSpacy.ipynb
```
For building training data and performing Entity recognition.

