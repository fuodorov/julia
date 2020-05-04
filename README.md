# Julia

## Julia tutorial

## Running Julia on your Computer

You can also do these tutorials by installing `julia` on your computer, setting up Jupyter, and downloading this tutorial repository to your computer.
If you're new to Julia, you can do that by following these steps:

1. Download julia from https://julialang.org/downloads/ (download the latest "stable" version).
   - Follow the instructions to install it on your computer (e.g. On macOS, drag it to Applications. On Windows, run the installer.)
2. Install julia's Jupyter Notebooks integration: IJulia.jl
   - Open the installed julia application, and you are presented with a "REPL" prompt. This is the main Julia interface. There, type this closing bracket
     character: <kbd>]</kbd> to open the package manager. Then type `add IJulia` to install the jupyter notebook interface for julia.
   - Then exit the package manager by pressing <kbd>delete</kbd> (as if you're deleting the `]` you typed to enter package mode)
   - Now you can open the jupyter notebooks by entering `using IJulia`, then once that loads, entering `IJulia.notebook()`, which should
     open a Jupyter tab in your browser.
