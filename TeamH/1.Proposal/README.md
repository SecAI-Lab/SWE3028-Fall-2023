# Setting up a LaTeX Compilation Environment in VScode

If you're working on WSL or Linux and want to set up a LaTeX compilation environment in Visual Studio Code, follow these steps:

1. Install TexLive.

	First, make sure you have TexLive installed. You can do this by running the following commands in your terminal:
	```bash
	sudo apt update
	sudo apt upgrade
	sudo apt install texlive-latex-base
	```
	If you want to use the full LaTeX package, you can install it like this:
	```bash
	sudo apt install texlive-full
	```
2. Install LaTeX Workshop Extension

	To make your LaTeX editing experience more convenient in Visual Studio Code, install the LaTeX Workshop extension. You can find it in the
	[Visual Studio Code Marketplace.](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop&ssr=false#review-details)

3. Easy Compilation with LaTeX Workshop

	With LaTeX Workshop installed, compiling your LaTeX files becomes a breeze. Simply save your `main.tex` or any other `.tex` files in your project's directory, and the extension will handle the compilation for you.

4. Manual Compilation (Optional)
	
	If you prefer compiling LaTeX files manually via the terminal, you can use the following command:
	```bash
	pdflatex main.tex
	```

# How to edit tex file.

Details are shown in [this file](./Guide/llncsdoc.pdf).