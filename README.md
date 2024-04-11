Therefore, it is an important aspect to create a protection barrier for users in
other to prevent these attacks from reaching them. Such work could be done
manually by humans, but the amount of content is too big making this task
time consuming. Therefore, it is a good idea to build a model that identifies
hate speech and draws the line between what’s acceptable speech and not.
Also, we create a model that identifies ironic speech and draws the line
between what’s ironic or not. This can help in tasks that need to discriminate
between true and false intent such as sentimental analysis. The two proposed
models use attention mechanism over BERT to get relative importance of
words, followed by Fully-Connected layers, and a final classification layer
for each sub-task, which predicts the class.
