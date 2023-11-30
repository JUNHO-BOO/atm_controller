# atm_controller

pip install gitpython

from git import Repo
git_url = "https://github.com/JUNHO-BOO/atm_controller"
repo_dir = "/path/to/your/local/directory"  # Replace with your desired local directory

Repo.clone_from(git_url, repo_dir)

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt  # Replace with your actual requirements file
pytest
