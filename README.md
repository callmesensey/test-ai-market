# Example Engineering AI Tools

This is a complete example marketplace repository that publishes the `code-review` skill and the `reviewer` subagent.

## Repository layout

```text
example-repository/
├── marketplace.json
├── README.md
├── docs/
│   └── code-review.md
├── skills/
│   └── code-review/
│       ├── SKILL.md
│       └── templates/
│           └── review-checklist.md
└── subagents/
    └── reviewer/
        └── AGENT.md
```

## Publish the repository

Initialize the example as its own Git repository:

```sh
cd example-repository
git init
git add .
git commit -m "feat: add example AI tools"
```

Push the repository to an SSH or HTTPS Git remote, then connect that remote URL in the application's Sources view. Production sources accept SSH and HTTPS Git URLs; `file://` URLs are used only by automated tests.
