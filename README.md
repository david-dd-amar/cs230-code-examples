# CS230 Code

[Tutorials](https://cs230-stanford.github.io)


This is a vopy of Stanford' CS 230 course. The structure of the repository is the following:

```
README.md
pytorch/
    vision/
        README.md
    nlp/
        README.md
tensorflow/
    vision/
        README.md
    nlp/
        README.md
```

To start the projects locally install [anaconda](https://www.anaconda.com/distribution/). This will add python 3 if not installed) and conda to the PATH (in mac /Users/username/anaconda3 or /Users/username/opt/anaconda3). Then add TensorFlow using the commands [here](https://www.anaconda.com/tensorflow-in-anaconda/). Finally use `conda install pytorch torchvision -c pytorch` for installing pytorch.

Once these are installed properly, you will need to create an environment so that all required libraries will be available. For example for tensorflow/vision you can use:
```
conda create -n cs230_tf_vision --file requirements.txt
conda activate cs230_tf_vision
```

Some libraries may fail to load and require an update (after creating the environment, e.g., `conda install tabulate`). 
