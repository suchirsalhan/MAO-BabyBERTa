# MAO-BabyBERTa
French, German, Japanese &amp; Chinese BabyBERTa Models. 

After cloning the repo, install requirements, using the command line:
```
git clone https://github.com/suchirsalhan/MAO-BabyBERTa
cd MAO-BabyBERTa
pip install -r requirements.txt
```

To train the BabyBERTa model on AO-CHILDES
```
python train-miniberta.py --ads-path "/data/English_ADS.txt" --cds_path "/data/aochinese.txt"
```
