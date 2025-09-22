# CYBERSECURITY-PORTFOLIO
# local folder
mkdir cybersecurity-portfolio
cd cybersecurity-portfolio
git init
git checkout -b main
echo "# Cybersecurity Portfolio" > README.md
git add README.md
git commit -m "Initial commit"

# create repo on GitHub (get URL from web or use SSH)
git remote add origin git@github.com:YOURUSERNAME/cybersecurity-portfolio.git
git push -u origin main
