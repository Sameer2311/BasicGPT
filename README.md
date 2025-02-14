
# DUMB GPT LLM

About Dumb GPT :

This is a learning project created by me.   

It is a pre-processed Large Language Model meaning it is not smart as there is no Finetuning involved in the training process or not pre-processed transformers are used while creating it.   

It is created to find the text which looks similar to it's prompt (the input which we give).   

The current model is trained on a wopping 100k iterations taking a time of 18H to traing on my RTX 3050 grapics cards     

You can train yours by getting the data from [Open Web Text](https://skylion007.github.io/OpenWebTextCorpus/).

Steps to Run this LLM: (on linux environment)
1. Create your venv.
Use command `python3 -m venv env_name`
2. Make sure you have pytorch on your venv [Pytorch Installation link](https://pytorch.org/get-started/locally/)       
I would suggest to go with the lastest version of CUDA.    

3. Clone this repo.

4. Download the data from [Open Web Text](https://skylion007.github.io/OpenWebTextCorpus/).
5. Extract the data using the Data-Extract.ipynb file.
6. After the extraction is done. Go to chatbot.py and make sure the paths are correct.
7. After that open your terminal and type the magical words (obviously this are for my model :grin: That you have pre tarained with the repo)
`python3 chatbot.py -batch_size 48`    
Don't forget to download the GPT model from [here](https://drive.google.com/file/d/1jBqRjpzoVb_u6Zv2WQbBTgvYqBav9dF8/view?usp=drive_link)      
This is because the current model was trained on 48 batch size you can adjust this as per your graphics card's convenience. :grimacing:      

Also make sure to change the batch size when ever you try to traing your own model using the file `training.py`    

And don't forget to change the name of the traing file when you run your custom model.

I would like to thank Elliot Arledge, he is my mentor and guid through out this project.(check out the links below).  

Below are the paper links that are useful in creating of this GPT:
1. [A Survey of Large Language Models]()
2. [Attention is all you need basic transformer](https://arxiv.org/abs/1706.03762)      

    Below paper is not using in this project as it is on fine tuning.   
[QL O RA: Efficient Finetuning of Quantized LLMs](https://arxiv.org/abs/2305.14314])

Connect with Me:
[LinkedIn](https://www.linkedin.com/in/biren-mer/)

Links   
=> [Elliot Arledge's Youtube Channel](https://youtube.com/@elliotarledge?si=X9pvHB2Z2wnuwd-l)  
=> [Free Code Camp Course For LLM](https://youtu.be/UU1WVnMk4E8?si=cJsaAvxqzhvH2Uge)


Thank you for viewing 
