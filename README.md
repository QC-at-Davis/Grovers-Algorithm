## Grover's Algorithm Workshop

## Getting Set Up
* intsall [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
  * After installation open your terminal and run `git --version` just to make sure it installed properly
* install [conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html)
  * After installation open your terminal and run `conda --version` just to make sure it installed properly
* Clone this repository to a place on your system
  * Run the following in the cloned folder
  * `conda env create --file=environment.yml`
  * You should see something after running the command that will tell you that to `activate this environment, use: conda activate grovers-workshop-env`
* Go ahead and run `conda activate grovers-workshop-env`
* Ensure that you are in the environment by running `conda env list`
  * You'll see a list of environments on the left side with a bunch of file paths on the right. If you're in the *right* environment, there should be a `*` to the right of `grovers-workshop-env`
* run `jupyter-lab` in your command line, you should see the Jupyter Lab pop up in your browser. On the left hand side you should be able to navigate through the different notebooks.
  * For this workshop, please refer to the `INDEX.ipynb` file FIRST. It will give you the proper order to view the other notebooks.
