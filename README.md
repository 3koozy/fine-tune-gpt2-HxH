# fine-tune-gpt2-HxH
* fine tuned GPT2 text generation model on a Hunter x Hunter TV anime series dataset
* the gpt2 model and fine-tuning script was provided by huggingface team here : https://github.com/huggingface/transformers
* you can find a link to the used dataset here : https://www.kaggle.com/bkoozy/hunter-x-hunter-subtitles
* you can find and use this fine-tuned model on huggingface model hub here : https://huggingface.co/3koozy/gpt2-HxH

# run a quick test
you can run the below code snippet for a quick taste of the model :

*Note: make sure the file run_generation.py is present in the current directory.
```
!python run_generation.py \
    --model_type=gpt2 \
    --model_name_or_path=3koozy/gpt2-HxH \
    --length 50 \
    --num_return_sequences 5 \
    --seed 87 \
    --prompt 'So you became a Hunter, too.'
```
