# Clone the repo
git clone https://github.com/abhishekdunakhe/fastapitodolist.git
cd fastapitodolist

# Create virtual environment
python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows

# Install dependencies
pip install -r requirements.txt

# Run locally
uvicorn main:app --reload
