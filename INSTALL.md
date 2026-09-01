# Install the GitHub profile README

Upload the files to the `salesmayn-code/salesmayn-code` repository without changing their paths:

```text
salesmayn-code/
├── README.md
├── assets/
│   └── header.svg
└── .github/
    └── workflows/
        └── profile-visuals.yml
```

Delete the old `snake.yml` and `activity-graph.yml` files from the repository root. GitHub does not run workflow files stored there.

After committing the three replacement files:

1. Open **Actions** in the repository.
2. Select **Generate profile visuals**.
3. Click **Run workflow** if the automatic push run has not already started.
4. Wait for the workflow to complete. It creates the `profile-assets` branch containing the activity graph and snake files.
5. Refresh the profile page.

If the workflow reports a permission error, open **Settings > Actions > General > Workflow permissions**, select **Read and write permissions**, save, and run the workflow again.

Do not copy the rendered preview text into GitHub. Upload or paste the raw contents of `README.md`; otherwise Markdown headings and tables can be lost.
