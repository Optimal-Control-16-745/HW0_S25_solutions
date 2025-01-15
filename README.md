# HW0_S25

Please check out the [HW0 + Julia Video Walkthrough](https://www.youtube.com/watch?v=RetAn_9AOMg) by [Kevin Tracy](https://kevintracy.info/) from last year. Note: this was made for the previous Julia LTS version(1.6.7) and we will be using the latest (and much improved) LTS, but the content in the video is still very much relevant.

## Getting Started
All the homeworks are distributed as Jupyter notebooks. Follow these instructions to get everything set up.

1. Install [Julia](https://julialang.org/) by running the one of the following terminal commands depending on your system. This will install the [Juliaup](https://github.com/JuliaLang/juliaup) installation manager. DO NOT install version-specific binaries.  
   a. for Windows, run `winget install julia -s msstore`, then `juliaup add lts` to install the LTS version, and `juliaup default lts` to set LTS as the default Julia version.
   b. for Mac/Linux, run `curl -fsSL https://install.julialang.org | sh -s -- -y --default-channel lts` to achive the same thing.
2. Clone this repo and put it wherever you want.
3. Start a Julia REPL in your terminal using `julia`
4. Install the [IJulia](https://github.com/JuliaLang/IJulia.jl) using the Julia package manager. In the REPL, enter the package manager using `]`, then enter `add IJulia` to add it to your system path.
5. In the REPL (hit backspace to exit the package manager), enter `using IJulia`
6. Launch the notebook using `notebook()` or `jupyterlab()`
7. (Optional) If you use VSCode, instead of steps 5-7, you can install the [Julia](https://code.visualstudio.com/docs/languages/julia) and [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) extensions in VSCode. Make sure you set the `kernel` to `Julia lts channel` before running your code.

## HW Instructions 

Fill out `Q1.ipynb` and `Q2.ipynb`.

## Submission Instructions 

Feel free to use any method you'd like to export your Jupyter notebook as a PDF (**with all the cell outputs shown**) and **submit on gradescope**. 

### HTML to PDF (Recommended)

We recommend this method of converting your Jupyter notebook to a PDF because it requires no additional installs (hopefully). It's slightly involved, but it is the most consistent in our experience.

1. Open the Jupyter notebook in your favorite **web browser** (not VS Code) with [IJulia](https://github.com/JuliaLang/IJulia.jl).
2. Make sure **all cell outputs are shown** including plots and unit tests' results.
3. In the top left corner of the Jupyter menu bar, do `File -> Save and Export Notebook As -> HTML`. It should download an HTML file.
4. Open the downloaded HTML file in your favorite web browser.
5. Open up the browser's print menu and select `Save as PDF`.
6. Save PDF and **submit on gradescope**.

### Others

If HTML to PDF does not work, feel free to try other methods: [https://mljar.com/blog/jupyter-notebook-pdf/](https://mljar.com/blog/jupyter-notebook-pdf/). 
