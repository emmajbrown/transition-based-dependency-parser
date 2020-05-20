# Transition-Based Dependency Parser

Use the following:
train.projective.short.conll: training dataset containing 9,568 tokens
dev.projective.conll: dataset to evaluate your parser’s performance

You will use train.projective.short.conll(which contains 425 trees) for training your model. Each datafile contains the following 8 columns: index, word, lemmatized word, pos1, pos2, head index, dependency label.

Implement parts of a transition-based dependency parser:
1) Check for projectivity
2) Create an oracle
3) Tree parsing with predictions
