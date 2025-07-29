Launch GitHub Desktop and switch to the main branch (or the branch you are working on).

Click Fetch origin to synchronize with the remote repository.

Open the project in Sublime Text: Repository → Open in Sublime Text.

In Sublime’s sidebar, right-click the www/ folder and choose Open in Terminal (or open a terminal and cd into www/).

Activate the Python 2 environment and generate the HTML files:

bash
conda activate py2
python ../jemdoc.py -c jemdoc.conf -o ../html/ *.jemdoc
Navigate to the html/ directory and double-click index.html to preview the site locally in your browser.

After verifying your changes, return to GitHub Desktop, enter a concise commit message (e.g., “Update content and rebuild site”), and click Commit to main.

Finally, click Push origin to upload the commit and trigger the GitHub Pages deployment workflow.

Deployment will complete automatically; visit https://hkuyonghengwang.github.io/ to confirm the updated site.
