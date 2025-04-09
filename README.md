# my-first-project
# Clone the repo
git clone https://github.com/YOUR-GITHUB-USERNAME/my-first-project.git
cd my-first-project

# Create README.md with your name and today’s date
echo "Name: Your-Name" > README.md
echo "Date: $(date +%Y-%m-%d)" >> README.md

# Add, commit, and push the file to GitHub
git add README.md
git commit -m "Added README with name and date"
git push origin main
