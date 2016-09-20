# Dev-GitHubPages
Try to Design my pages

1. Create a New Repository

2. $(git clone $reposURL)

3. Commit and Push

    - git status
    - git add README.md
    - git commit -m 'first commit'
    - git push

4. Create Branch gh-pages

5. Update to Branch ( $(cvs -q up -d -r $branch_name) )

6. Add your home page (index.html)

7. Commit home page

    git status
    git commit -m 'add home page'
    git push
    git push origin gh-pages

8. Check your pages by https://$account.github.io/$repository_name/
