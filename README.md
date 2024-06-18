# Gradient_Descent_demo

A animated gradient descent demo. The codebase was originally created by Mrigankshi Kapoor.

## Create a conda enviroment

download Anaconda: https://www.anaconda.com/download/success

next you are going to use command line to set up the environment.

#### 1. Create a new conda environment

```bash
conda create -n "ret" python==3.9 -y
```

if you get any error, try this instead:

```bash
conda create -n "ret" conda-forge::python==3.9 -y
```

now you have created an virtual environment named `ret`, we are going to configure the environment while not breaking the default one.

#### 2. Activate the environment

```bash
conda activate ret
```

#### 3. Install dependency

```bash
pip install -r requirements.txt
```

The installation is only required once. Next time if you want to use the same environment, simply run `conda activate ret` before you luanch the notebook.


#### 4. launch the notebook from commandline (not GUI/navigator)

Under this folder, run:

```bash
jupyter notebook
```

## Troubleshooting

Still not working?

- Are you under the correct environment? 

If you close your terminal, it would fall back to the default environment. So you need to run `conda activate ret` again if you close and open your terminal.

- Open an issue or contact me!


## Examples

#### 2D example

![Demo](demo.png)

#### 3D example

![Demo](demo_3d.png)
