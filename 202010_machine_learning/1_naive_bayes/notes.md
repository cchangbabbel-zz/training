### Naive Bayes
- "Naive" because it ignores word order. 

- PROS
    - Easy to implement
    - Can work with a lot of features
- CONS 
    - Can break. e.g. "Chicago Bull" images - returns images of Chicago and Bulls. Not good for phrases made up of multiple words with distinct meanings

- Algorithm is good for: 
    - text classification (e.g. author id)
        - When dealing with text, it’s very common to treat each unique word as a feature, and since the typical person’s vocabulary is many thousands of words, this makes for a large number of features. 
        - The relative simplicity of the algorithm and the independent features assumption of Naive Bayes make it a strong performer for classifying texts
        
        
#### Bayes Rule
- prior probabilities
- sensivity
- specificity
- posterior probabilities