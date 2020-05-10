# PyTorch-Pre-trained-models-with-Resnet-18
PyTorch Peer 
PyTorch is an open source machine learning library based on the Torch library,[1][2][3] used for applications such as computer vision and natural language processing,[4] primarily developed by Facebook's AI Research lab (FAIR).[5][6][7] It is free and open-source software released under the Modified BSD license. Although the Python interface is more polished and the primary focus of development, PyTorch also has a C++ interface.[8]

A number of pieces of Deep Learning software are built on top of PyTorch, including Uber's Pyro,[9] HuggingFace's Transformers,[10] and Catalyst.[11][12]

PyTorch provides two high-level features:[13]

Tensor computing (like NumPy) with strong acceleration via graphics processing units (GPU)
Deep neural networks built on a tape-based automatic differentiation system

Simply put, a pre-trained model is a model created by some one else to solve a similar problem. Instead of building a model from scratch to solve a similar problem, you use the model trained on other problem as a starting point. For example, if you want to build a self learning car
Neural networks are a different breed of models compared to the supervised machine learning algorithms. Why do I say so? There are multiple reasons for that, but the most prominent is the cost of running algorithms on the hardware.

In today’s world, RAM on a machine is cheap and is available in plenty. You need hundreds of GBs of RAM to run a super complex supervised machine learning problem – it can be yours for a little investment / rent. On the other hand, access to GPUs is not that cheap. You need access to hundred GB VRAM on GPUs – it won’t be straight forward and would involve significant costs.

Now, that may change in future. But for now, it means that we have to be smarter about the way we use our resources in solving Deep Learning problems. Especially so, when we try to solve complex real life problems on areas like image and voice recognition. Once you have a few hidden layers in your model, adding another layer of hidden layer would need immense resources.

Thankfully, there is something called “Transfer Learning” which enables us to use pre-trained models from other people by making small changes. In this article, I am going to tell how we can use pre-trained models to accelerate our solutions.
