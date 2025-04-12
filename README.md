# 1. Go to saqly branch
git checkout saqly

# 2. Commit your changes
git add .
git commit -m "Updated saqly branch"

# 3. Push changes to remote saqly
git push origin saqly

# 4. Go to main branch
git checkout main

# 5. Pull latest changes from remote main
git pull origin main

# 6. Merge saqly into main
git merge saqly

# 7. Push updated main to GitHub
git push origin main
