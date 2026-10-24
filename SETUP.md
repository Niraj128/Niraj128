# GitHub Profile Design — Version 2

This package updates your existing `Niraj128` GitHub profile. It does **not** change GitHub's outer site theme.

## Update an existing profile

1. Open `https://github.com/Niraj128/Niraj128`.
2. Upload these **two new assets** into the repository's `assets/` folder (not the root):
   - `project-pipeline.svg`
   - `engineering-flow.svg`
3. Edit the root `README.md` and replace all its contents with the README in this ZIP. Commit.
4. Refresh `https://github.com/Niraj128`.

No need to reupload existing banner and project cards. You may alternatively upload the package's entire `assets/` folder and replace the root README.

## Why the change

- Two equal-width cards show work in progress without exaggerating technical experience.
- The grey Markdown code block (with GitHub copy/explain controls) is replaced with an SVG visual workflow.
- Static images render on GitHub without plugins, HTML styling, or scripts.

## Safety

Before publishing additional Terraform repos, make sure state files, secret `.tfvars`, credentials, and `.terraform/` are not tracked.
