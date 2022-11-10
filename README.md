Assignment7
-------------
*by Ellemijn Galjaard*

This project runs a [COQUI-based STT model](https://github.com/coqui-ai/STT/blob/main/notebooks/train_personal_model_with_common_voice.ipynb) and fine-tunes it on a self-recorded open-source CommonVoice dataset containing 230 .mp3 files. This project is protected under an MIT License, see ``LICENSE.txt`` for the specifics.  

About this project
--------------
- The files, metadata, and ``requirements.txt`` are downloaded via [gdown](https://pypi.org/project/gdown/). This was done so users are not required to mount their Drive when working in a Colab environment. This means that you only need to run the script (on Colab or locally) and have a working internet connection to run this project.  

- Download or clone the .py script, ``cd`` into the applicable directory and run ``run_model.py pre-trained`` to print the results of the COQUI pre-trained model on the test set. Run ``run_model.py fine-tuned`` to print the results of the fine-tuned model (fine-tuned on CommonVoice .mp3 files recorded by me) on the test set.
  
Have fun!
