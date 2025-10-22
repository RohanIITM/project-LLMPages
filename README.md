# GitHub Pages Site

This project is designed to run as a GitHub Pages site. Below is the setup guide to publish this site.

## Setup & Installation

1. **Clone the Repository**: Clone the GitHub repository to your local machine.

```bash
git clone <repository-url>
```

2. **Navigate into the directory**:

```bash
cd <repository-directory>
```

3. **Verify Files**: Ensure the following files are present:
   - `index.html`: Homepage linking to all content files.
   - `ashravan.txt`: Contains a short story.
   - `dilemma.json`: Data on an autonomous vehicle's dilemma.
   - `about.md`: Three-word about description.
   - `pelican.svg`: SVG image file.
   - `restaurant.json`: Restaurant recommendation.
   - `prediction.json`: Fed Rate prediction.
   - `LICENSE`: MIT license text.
   - `uid.txt`: The UID file.

4. **Push to GitHub**: Make sure the repository is connected to your GitHub account. Push the changes.

```bash
git add .
git commit -m "Initial commit"
git push origin main
```

5. **Enable GitHub Pages**: 
   - Go to your GitHub repository settings.
   - Under the "GitHub Pages" section, choose the `main` branch and click save.

6. **Access the Site**: Wait a few minutes and your site will be live at `https://<username>.github.io/<repository-name>/`.

Ensure all files have valid content and double-check the links to verify that they point to the correct downloadable content.