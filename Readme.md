# TrackFormer-with-MSG

This repo provides the code for the optimization scheme of Trackformer.  

In this scheme, self-attention layers are added to the Trackformer encoder. The self-attention is calculated on the 
input sequence fragments. In different sequence fragments, use message token shift mechanism to exchange message among
different fragments.

The original code of Trackformer is from https://github.com/timmeinhardt/trackformer

The idea of using messenger token shift is inspired from TeViT and MSG-Transformer.

TeViT: https://github.com/hustvl/TeViT  
MSG-Transformer: https://github.com/hustvl/MSG-Transformer  

The installation, training and tracking method is the same with Trackformer.
