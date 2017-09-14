

# Dialogue Response System

Our goal is to design a single response system for a given context , as an exploration into how an Hierarchical Recurrent Encoder-Decoder (HRED) model proposed by Serban et al. (2016)[1]  could provide the building block to a more robust chatbot system.The HRED model [2] uses a Gated Recurrent Unit (GRU) Recurrent Neural Network (RNN) and has additional functionality to remember the context.

We plan to score our HRED model using perplexity scores against the ngram/Knesser-Ney which should have a much more limited context. 

We are using the movie dialogues corpus (Movie-DiC) as our main dataset as this was used in [1].  This is a corpus scraped from the internet movie script data collection.  The dialogue corpus contains 132,229 dialogues containing a total of 764,146 turns which have been extracted from 753 movies [3]. This dataset cannot be made public and hence we are making our github repository public.

## Directory Structure

 __Report__ -> Contains the project report 
 
 __Data Exploration__ -> Contains analaysis of the dataset being used 
 
 __ngram__ -> ngram language model
 
 __rnn__ -> rnn language model 
 
 __shared__ -> Common utilities being used by various models.


## References

[1] Iulian V. Serban , Alessandro Sordoni, Yoshua Bengio, Aaron Courville and Joelle Pineau  2016. Building End-To-End Dialogue Systems Using Generative Hierarchical Neural Network Models. 

[2] Alessandro Sordonif , Yoshua Bengiof , Hossein Vahabig , Christina Liomah , Jakob G. Simonsenh , Jian-Yun Nief 2015. A Hierarchical Recurrent Encoder-Decoder for Generative Context-Aware Query Suggestion.

[3] Banchs, R. E. 2012. Movie-DiC: A movie dialogue corpus for research and development. In Proceedings of the 50th Annual Meeting of the Association for Computational Linguistics, 203–207.
