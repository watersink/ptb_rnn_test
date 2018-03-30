# ptb_rnn_test
from this paper of google brain,[RECURRENT NEURAL NETWORK REGULARIZATION](https://arxiv.org/abs/1409.2329)

##### There are 3 supported model configurations:
| config | epochs | train | valid  | test   |
|--------|--------|-------|--------|--------|
| small  |   13   | 37.99 | 121.39 | 115.91 |
| medium |   39   | 48.45 |  86.16 |  82.07 |
| large  |   55   | 37.87 |  82.62 |  78.29 |


### train-small
    python3 ptb_word_lm.py --data_path=./data/ --model=small --save_path=./small
<div>
<img width="400" height="300" src="https://github.com/watersink/ptb_rnn_test/raw/master/pic/train_small_loss.jpg"/>
<img width="400" height="300" src="https://github.com/watersink/ptb_rnn_test/raw/master/pic/valid_small_loss.jpg"/>
</div>

### train-medium
    python3 ptb_word_lm.py --data_path=./data/ --model=medium --save_path=./medium
<div>
<img width="400" height="300" src="https://github.com/watersink/ptb_rnn_test/raw/master/pic/train_medium_loss.jpg"/>
<img width="400" height="300" src="https://github.com/watersink/ptb_rnn_test/raw/master/pic/valid_medium_loss.jpg"/>
</div>

### train-large
    python3 ptb_word_lm.py --data_path=./data/ --model=large --save_path=./large

