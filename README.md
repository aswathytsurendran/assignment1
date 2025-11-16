# 1. Clone your repo
git clone https://github.com/aswathytsurendran/assignment1.git
cd assignment1

# 2. Move contents from test/ to repo root (if safe to do so)
git mv test/* .
# If hidden files exist, you may need to move them separately.

# 3. Remove the now-empty test folder
git rm -r test

# 4. Stage, commit and push
git add -A
git commit -m "Move test files to repo root for assignment starter"
git push origin main

