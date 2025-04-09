git clone https://github.com/YOUR-GITHUB-USERNAME/my-first-project.git
cd my-first-project

echo "Name: Your-Name" > README.md
echo "Date: $(date +%Y-%m-%d)" >> README.md

git add README.md
git commit -m "Added README with name and date"
git push origin main
