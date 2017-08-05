# poem_generator

Generate Chinese poem automatically.

## Requirements

* Python 3.0+
* Flask
* jieba
* sklearn
- `sudo pip3 install flask,jieba,sklearn`

## Usage

For the first time, run the commands below to init.

```bash
python3 preprocess.py
python3 get_collocations.py
python3 get_topic.py
python3 get_start_words.py
```

Next time, just run this command.

```bash
python3 index.py
```

## Data

In `./data` folder, there is a corpus file "唐诗语料库.txt", and some data files will be generated here.
