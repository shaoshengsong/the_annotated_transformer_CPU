# the_annotated_transformer_CPU

Python3.9

```
# CUDA 10.2
conda install pytorch==1.11.0 torchvision==0.12.0 torchaudio==0.11.0 cudatoolkit=10.2 -c pytorch

# CUDA 11.3
conda install pytorch==1.11.0 torchvision==0.12.0 torchaudio==0.11.0 cudatoolkit=11.3 -c pytorch

# CPU Only
conda install pytorch==1.11.0 torchvision==0.12.0 torchaudio==0.11.0 cpuonly -c pytorch
```

```
pip install -q torchdata==0.3.0 torchtext==0.12 spacy==3.2.6 altair 
python -m spacy download de_core_news_sm
python -m spacy download en_core_web_sm
```


 `torchtext\datasets\multi30k.py`
```
# URL = {
#     "train": r"http://www.quest.dcs.shef.ac.uk/wmt16_files_mmt/training.tar.gz",
#     "valid": r"http://www.quest.dcs.shef.ac.uk/wmt16_files_mmt/validation.tar.gz",
#     "test": r"http://www.quest.dcs.shef.ac.uk/wmt16_files_mmt/mmt16_task1_test.tar.gz",
# }

# MD5 = {
#     "train": "20140d013d05dd9a72dfde46478663ba05737ce983f478f960c1123c6671be5e",
#     "valid": "a7aa20e9ebd5ba5adce7909498b94410996040857154dab029851af3a866da8c",
#     "test": "0681be16a532912288a91ddd573594fbdd57c0fbb81486eff7c55247e35326c2",
# }
URL = {
    "train": r"https://raw.githubusercontent.com/neychev/small_DL_repo/master/datasets/Multi30k/training.tar.gz",
    "valid": r"https://raw.githubusercontent.com/neychev/small_DL_repo/master/datasets/Multi30k/validation.tar.gz",
    "test": r"https://raw.githubusercontent.com/neychev/small_DL_repo/master/datasets/Multi30k/mmt16_task1_test.tar.gz",
}

MD5 = {
    "train": "20140d013d05dd9a72dfde46478663ba05737ce983f478f960c1123c6671be5e",
    "valid": "a7aa20e9ebd5ba5adce7909498b94410996040857154dab029851af3a866da8c",
    "test": "6d1ca1dba99e2c5dd54cae1226ff11c2551e6ce63527ebb072a1f70f72a5cd36",
}
```
