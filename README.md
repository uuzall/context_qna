# QnA using Context 

Question Answering using context is one of the most important applications for language models in general because adding a vector search engine will make it very powerful. OpenAI's GPT suite is one of the few models that can actually perform this task remarkably well. I wanted to see if it is possible to train a similarly performing model using open-source models. Hence, this repo was born. 

I used the Pythia 1b model, and tried to do it with the LLaMA model but I did not have enough memory to do so. After training it on the LFQA dataset, and the MS-MARCO dataset (separately) I found quite a few odd things. Firstly, since LFQA is taken from Reddit, the trained model talks like a Redditor (if you know what I mean). Another thing I found out was that output from the model trained on the MS-MARCO dataset was better, succinct, and more professional. 

The sample responses are saved in 'sample_out.txt.' All questions (except for the magnetism question) in the sample_out was very similar to the output from GPT-3 Davinci which is pretty great in my opinion.

I will conclude by saying that I know for a fact that using a larger and better model like the LLaMA 2 will make the performance better. 