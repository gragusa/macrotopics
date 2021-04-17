# First-time setup: Install Julia, Jupyter & Pluto

### Step 1: Install Julia 1.5.4

Go to https://julialang.org/downloads and download the current stable release, Julia 1.5.4, using the correct version for your operating system (Linux x86, Mac, Windows, etc).

### Step 2: Run Julia

After installing, make sure that you can run Julia. On some systems, this means searching for the "Julia 1.5.3" program installed on your computer; in others, it means running the command julia in a terminal. 

Make sure that you can execute a simple command, like `sin(3.14)`:

![Julia Repl](../assets/julia_repl.png)


### Step 3: Install Jupyter

Next we will install Jupyter. Jupyter is a convenient web-based interface to interact with Julia.

Open the *Julia REPL**. This is the command-line interface to Julia, similar to the previous screenshot.

To install Jupyter, we want to run a package manager command. To switch from Julia mode to Pkg mode, type `]` (closing square bracket) at the `julia>` prompt:

```julia
julia> ]

(@v1.5) pkg>
```

The line turns blue and the prompt changes to `pkg>`. This prompt is telling you that you are now in package manager mode which allows you to do operations on packages (also called libraries).

To install Jupyter, run the following (case sensitive) command to add (install) the package to your system by downloading it from the internet. You should only need to do this once for each installation of Julia:

```julia
(@v1.5) pkg> add IJulia
```

If everything goes as planned, you will get back to the package manager mode prompt. Press ESC to go back to the Julia prompt. Then load the library
```julia
using IJulia
notebook()
```

With the first line we are loading (we are `using`) the `IJulia` package. The second line asks to start the notebook. However, is likely that you will get asked whether you want `install Jupyter via Conda, y/n? [y]`. This is when `Jupyter`, which is part of Python, is actually installed. This might take some time as several things have to be installed (python among other things). If everything goes well, your you will see your browser taking you to the Jupyter landing page:

![Jupyter](../assets/jupyter.png)

From here you can create a new notebook. 

### Install Pluto

To install Pluto, run the following (case sensitive) command from the package manager mode, that is, after you press `]` from the REPL: 
```julia
(@v1.5) pkg> add Pluto
```

This might take a couple of minutes, so you can go get yourself a cup of tea!

Then you can launch Pluto by first loading the package, and then starting a Pluto instance:
```julia
using Pluto
Pluto.run()
```
As for Jupyter, you browser should get you to the Pluto landing page:

![Pluto](../assets/pluto.png)


_Note: We need a modern browser to view Pluto notebooks with. Firefox and Chrome work best._

## Resources

Here is a list of resources that can be useful in writing Julia code:

- [The Julia manual](https://docs.julialang.org/en/v1/)
- [Mathematical vs Julia notation](https://web.stanford.edu/class/engr108/julia_slides/julia_vs_math.pdf)


