# Shakespeare-Generator
This is a from scratch implementation of a character level
lanuage model which generates text that resembles 
Shakespeare's writing style.

The project implements a transformer network
using Pytorch and shows the working of
self attention and multi-headed attention blocks.

The result at the end of the notebook
shows text that looks similar to what 
other Shakespeare writings may look like 
but when read carefully, it does not 
actually create logical sentences which 
have a meaning.

The transformer model is pretrained on
the text which allows it to blabber in
Shakespeare-like language. It does not
actually perform a specific task such as
answering questions based on the data.
It only includes decoder blocks which
do not provide real world functionality 
on their own. A refined and larger variation
of this model could be fine tuned to perform
a desired task.
