#### - [Attention Forcing for Sequence to Sequence Model Training](https://arxiv.org/abs/1909.12289) [OpenReview](https://openreview.net/forum?id=rJe5_CNtPB) 
- Brief Description and Key points
  + Teacher Forcing: Provide reference output history during training, difficult to correct errors during inference
  + Free Running: Only provide generated output, difficult to converge. Finding attention(aligning with input) and inferring the output is difficult task.
  + Solution: Attention Forcing- Use a pre-trained model to find attention scores, use generated output now
  + Force learned model attention to be close to reference attention through losses(KL-Divergence)
