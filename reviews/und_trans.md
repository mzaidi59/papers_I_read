#### - [Addressing the Under-Translation Problem from the Entropy Perspective](http://www.nlpr.ia.ac.cn/cip/ZongPublications/2019/2019-ZhaoYang-AAAI.pdf)

#### Pre-Requisites
  - Upto transformer model, which can be accessed [here] #TODO
  - Entropy
  - Even if you know what neural machine translation is, you might be able to get a good idea of what is going around
  
#### Problems
  - Undertranslation Problem in NMT Models: During translation from one language to another, words are dropped which leads to erroneous outputs. 

#### Solution
  - The model tries to analyse the words wihch are morelikely to be dropped 
  - It is found that high entropy words are more likely to be dropped out
  
- Brief Description and Key points
  + The paper claims that high entropy words are most likely to suffer under-translation
  + Solves the problem by masking confounding target words by pseudo symbols and training in 2 steps
  + Suggest Pre-Training, Multitask-Training or Two-pass method.
