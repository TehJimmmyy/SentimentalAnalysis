We build a model that identifies hate speech and draws the line between what’s acceptable speech and not.
Also, we create a model that identifies ironic speech and draws the line
between what’s ironic or not. This can help in tasks that need to discriminate
between true and false intent such as sentimental analysis. The two proposed
models use attention mechanism over BERT to get relative importance of
words, followed by Fully-Connected layers, and a final classification layer
for each sub-task, which predicts the class.
