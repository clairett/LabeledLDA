# LabeledLDA
Labeled LDA in Python 

The code implemented by Shuyo (https://github.com/shuyo/iir/blob/master/lda/llda.py)

And I add the function "fold" to make new document acquire P(z|new_d) which based on trained LDA Model originally. 

Data
-----
Input data is required in following format:

```
[label1,label2,...]doc_text``
```


