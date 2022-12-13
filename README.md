# ece-5831-project
Context Derivation for Knowledge Graph Expansion
Created by: Haard Rao, Rohit Sanjay, Neel Khakhar
Role of Haard Rao: Knowledge graph implementation
Role of Rohit Sanjay: Knowledge graph implementation
Role of Neel Khakhar: Reference paper implementation and coding
Humans use language as a form of communication to think, speak, write, decide, etc; but that’s not a 
case with computers. Humans have to give some kind of input for it to understand. Through all this, 
humans can relate to different entities and make connection from different sentences but again, 
computers cannot do this. So, we decided to use our coding skills and a few open sources to give these 
abilities to computers. For doing so we used NLP so that computer understands English language and 
used spaCy LLM which is a cython based library for NLP developments. Here we decided two 
approaches. First implementation was directly from paper but it was confined to Q&A and very heavy 
to implement it. We used social IQA dataset for this particular approach. The second implementation 
was for everyday use and used wiki_sentences v2 dataset. These gave output from the queries passed 
through it. We get a knowledge graph as an outcome of both the implementations.
