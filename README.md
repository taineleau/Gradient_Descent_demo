# Gradient_Descent_demo

A animated gradient descent demo. You can change learning rate (step size), .

The codebase was originally created by Mrigankshi Kapoor.

## Download this github repo

You can directly download it as a zip file or use git. 


## Create a conda enviroment


download Anaconda: https://www.anaconda.com/download/success

Next you are going to use command line (mac/linux: `terminal`, windows: `command prompt`/`powershell`) to set up the environment. 


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

#### 5. Use it in the future

You only need to do step 2 & 4, which are the following:

```bash
conda activate ret

```

## Troubleshooting

##### Do I have to use command line? Can I launch it from jupyterlab or anaconda navigator?

The short answer is no. Jupyterlab or Google colab does not support javascript output by default. It is hard to config a specific jupyter version so we want to use command line.



##### Still not working? Are you under the correct environment? 

If you close your terminal, it would fall back to the default environment. So you need to run `conda activate ret` again if you close and open your terminal.

Or, Open an issue or contact me!

##### Windows user?

Yes we tested it on windows and it works! You need to use either `command prompt` or `powershell` to install the dependency.



## Examples

#### 2D example

A large learning rate make you further away from the minimum (target).

![Demo](demo.png)

#### 3D example

Local minima and global minimum.

![Demo](demo_3d.png)
