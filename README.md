# Drama/Movie Script generator

An attempt at designing a network which generates Movie Scripts (how cool is that!)
### Topology
I have shortlisted some candidates for acomplishing this taks:
1. Seq2seq LSTM with encoders
2. Variational Autoencoders OR
3. A GAN where Gen produces dialogues and Cop tells if it comes close to the storyline (This will be cool!). We'll need a different loss function here to penalise the network based on the cosine similarity with subsequent story segments for each character. 

### Dataset
Two obvious candidates:
1. Cornell's [Movie Dialog Corpus](http://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html)
2. I love Elementary. Its a modern take on /*Sherlock Holmes*/. Drama, mystery, perfect. So I am going to try to curate a dataset from Elementary Season 1 or 5 subtitles. Unfortunately, I havent been able to find Subtitles for the deaf or hard-of-hearing ([SDH](https://en.wikipedia.org/wiki/Subtitle_(captioning)#Subtitles_for_the_deaf_or_hard-of-hearing_(SDH))) which have character labled dialogs insted of just dialogs. Still looking, if you guys find any let me know.
 

### Contributers
- Abhiraj (Me obviously)
- I have been discussing various ML/DL projects with two interesting college mates @[Ritesh](https://github.com/rkmalaiya) and @[Richa](https://github.com/richa9407). They have helped and contributed ideas to various projects including this one.
