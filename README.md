# Activate virtual environment  
## On Windows  
venv\Scripts\activate  
# or Windows with PowerShell
venv\Scripts\Activate.ps1
## On macOS and Linux  
source venv/bin/activate  

# Install requirements
pip install -r requirements.txt

# Copy .env.example and fill out values
cp .env.example .env

# Run the backend server
cd Backend
python main.py# -
