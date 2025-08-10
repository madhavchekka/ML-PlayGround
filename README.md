Before working on any ML project, it is important that you have proper virtual environment set up with necessary packages. Setting up the environment from scratch is cumbersome. Instead, you can clone this repo and start working on your ML project right away! Instructions provided are for Mac users.

# Install uv using homebrew 
brew install uv 

# Create a new project folder
mkdir MLWorkSpace 

# Clone this repo: 
git clone git@github.com:madhavchekka/ML-PlayGround.git

# Create venv 
cd ML-PlayGround
uv sync 

# Optional Step: 
# Upgrade all packages if needed. They apply to the environment
uv lock --upgrade 
uv sync 

# Launch Jupyter notebook and start working 
uv run jupyter notebook
