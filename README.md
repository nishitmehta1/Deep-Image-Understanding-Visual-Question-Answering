# Strong baseline for visual question answering

This is a re-implementation of Vahid Kazemi and Ali Elqursh's paper [Show, Ask, Attend, and Answer: A Strong Baseline For Visual Question Answering][0] in [PyTorch][1].

The paper shows that with a relatively simple model, using only common building blocks in Deep Learning, you can get better accuracies than the majority of previously published work on the popular [VQA v1][2] dataset.

A fully trained model (convergence shown below) is [available for download][5].

![Graph of convergence of implementation versus paper results](http://i.imgur.com/moWYEm8.png)

Note that the model in [my other VQA repo](https://github.com/Cyanogenoid/vqa-counting) performs better than the model implemented here.


# This project uses the code provided [here][6]


[0]: https://arxiv.org/abs/1704.03162
[1]: https://github.com/pytorch/pytorch
[2]: http://visualqa.org/
[3]: https://github.com/ruotianluo/pytorch-resnet
[4]: http://visualqa.org/vqa_v1_download.html
[5]: https://github.com/Cyanogenoid/pytorch-vqa/releases
[6]: https://github.com/Cyanogenoid/pytorch-vqa
