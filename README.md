# Please download the pretrained NanoGPT model on QA data from the [link](https://drive.google.com/file/d/1gIZw-HAB-tHtEYCmNugwlIV7R3WsgjjZ/view?usp=sharing), and place it into the folder `./sft`!

# If you have any questions, please feel free to open an issue on GitHub, and I will respond.

# For Team Discussion

I have completed basically Task 2 and Task 3. For Task 1, currently I have 10k training data. But we need at least 100k:

- Currently I generated 5000 simple arithmetic like the ones provided, and 5000 more 2 step arithmetic like 2\*(5+3)=?
- Would need to generate more until at least 100k in 1:1 ratio
- Then maybe 50k more for ones that uses brackets like (x+5)\*2=30,x=?. Need about 50k to maintain the ratio

Uncompleted Tasks:

1. Task 4
2. Tweaking the batch size and epoch numbers to train our model better. Currently, it seems to fail at answering basic questions
