# Install uv using homebrew 
brew install uv 

# Create a new project folder
mkdir MLWorkSpace 

# Clone this repo: 
git clone git@github.com:madhavchekka/ML-PlayGround.git

# Create venv 
uv sync 

# Upgrade all packages if needed. They apply to the environment
uv lock --upgrade 
uv sync 
