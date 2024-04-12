#zid : z5398380
      #z5365604
### Understanding the Kernelization Process

Through this tool, Users can intuitively see how the kernelization process gradually simplifies a graph, and how this process affects the complexity of solving the problem. For the vertex cover problem, students can observe how different simplification rules are applied and how they gradually reduce the number of vertices and edges in the graph.

### Exploring the Impact of Parameters

Users can generate different graph instances by adjusting the number of vertices and sparsity parameters. This helps them understand how these graph characteristics affect the kernelization process and the final outcome. 
### description of the repository contents
main scr.ipynb------>main code file 

report--------> report
### instructions

## Running SageMath 9.5 with Jupyter Lab: Required Dependencies

To run SageMath 9.5 in Jupyter Lab effectively, you may need to ensure the following dependencies are installed:

### Python Packages
- `ipywidgets` for interactive widgets in Jupyter notebooks.

### JavaScript Dependencies
- Node.js is required for installing and managing some JupyterLab extensions that enhance interactivity.

### Installation Commands

```bash
# Install Jupyter Lab (if not installed)
pip install jupyterlab

# Install ipywidgets using SageMath
sage -pip install ipywidgets

# Ensure Jupyter Lab supports ipywidgets
jupyter labextension install @jupyter-widgets/jupyterlab-manager

# Install Node.js (check your system's best method)
# Linux: sudo apt-get install nodejs npm
# macOS: brew install node
# Windows: Download installer from https://nodejs.org/

