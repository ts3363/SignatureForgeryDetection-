# Make a new project folder
mkdir SignatureForgeryDetection
cd SignatureForgeryDetection

# Move the .ipynb file into the folder
# (or manually move it using File Explorer)

# Initialize Git and add your file
git init
git add SignatureForgeryDetection.ivp.ipynb
git commit -m "Add signature forgery detection notebook"

# Link to GitHub repository
git remote add origin https://github.com/YOUR_USERNAME/SignatureForgeryDetection.git

# Push to GitHub
git push -u origin master  # or `main`, based on GitHub default branch
