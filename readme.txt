papers:
https://openreview.net/pdf?id=BkQqq0gRb

notMNIST dataset:
https://www.kaggle.com/datasets/jwjohnson314/notmnist
need to delete the following zero byte files:
A/RGVtb2NyYXRpY2FCb2xkT2xkc3R5bGUgQm9sZC50dGY=.png
F/Q3Jvc3NvdmVyIEJvbGRPYmxpcXVlLnR0Zg==.png

to run:
uncomment experiments in main.py and use
uv run main.py
where uv (https://github.com/astral-sh/uv) can be installed via any package manager
(or use pip, or any tool supporting pyproject.toml - untested)
you might also have to uncomment the wandb login / logging stuff
same thing with plots.py
