#### - [Monotonic Infinite Loopback Attention](https://arxiv.org/abs/1906.05218)

- Brief Description and Key points
  + Hard Attention to decide where to stop and where to proceed reading input.
  + Transformer like soft-attention over the partially seen input. 
  + Backpropagation Issue: Draw analogies with sampling vs expected values as in Soft-attention to facilitate training in the case of hard attention by using expected value during training time.
  + Modify loss to penalise for high-latency solutions
  + Also presents a new latency metric called 'Differentiable Average Lagging'
