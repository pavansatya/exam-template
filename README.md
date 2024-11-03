# Loaded Lecture Template

Template for lecture notes with reveal.js presentations, latex dependencies, poetry, and VS Code extensions for Python.

## Installation and Usage

### Installation and Use via Github Codespaces

To use this repository via codespaces simply click on the `code` &rarr; `codespaces` &rarr; `create codespace on main` buttons.

Once the codespace is open in the browser, click the three bars in the top left corner and select `Open in VS Code Desktop`.

Widgets might work better when using VS Code Desktop vs. in the browser.

Note the codespace might take a long time to build. This is usually due to TexLive dependencies. Use `Cmd` / `Ctrl` + `Shift` + `P` &rarr; `Codespaces: View Creation Logs` to check status.

If required, use `Cmd` / `Ctrl` + `Shift` + `P` &rarr; `Codespaces: Rebuild Container` to rebuild the container. Do not use `gh codespace rebuild`. This takes a long time since it re-downloads the entire image.

### Installation and Use via VSCode DevContainer

To ue this repository via a Dev Container, ensure you have Docker Desktop install and functioning on your system and have the Dev Containers extension in VSCode. Clone the repository and open VS Code in the repository root folder.

Once VS Code is opened in the repository's root folder, you should be prompted to open in a Dev Container. If you are not prompted, use `Cmd` / `Ctrl` + `Shift` + `P` &rarr; `Dev Containers: Rebuild and Reopen in Container`.

### Using Scripts and Notebooks

This repository uses Poetry to build a local Python environment in the `.venv` directory. When you are running scripts, ensure you are using the correct Python interpreter. Do this by `Cmd` / `Ctrl` + `Shift` + `P` &rarr; `Python: Select Interpreter` and selecting the `.venv` Python environment. When you are running Jupyter notebooks, be sure to use the `.venv` Python by clicking `Select Kernel` and selecting the Python environment in `.venv`.

## License

This repository is provided with an MIT license. See the `LICENSE` file.

## Contributing

Please email Mauro Sanchirico at ms3978@camden.rutgers.edu (academic) or sanchirico.mauro@gmail.com (personal) with questions, comments, bug reports, or suggestions for improvement.

