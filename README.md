# Manta VPP | Intelligent Energy Trading

This is a static website for Manta VPP, built with HTML and Tailwind CSS.

## Project Structure

- `home.html`: Main landing page
- `solutions.html`: Solutions page
- `benefits.html`: Benefits page
- `contact.html`: Contact page

## Deployment

### Vercel (Recommended)

This project is configured for easy deployment on Vercel. A `vercel.json` file is included to handle routing.

1.  **Install Vercel CLI** (if you haven't already):
    ```bash
    npm i -g vercel
    ```

2.  **Deploy**:
    Run the following command in your terminal:
    ```bash
    vercel
    ```
    Follow the prompts to deploy your project.

3.  **Deploy via Git Integration**:
    - Push your code to a Git repository (GitHub, GitLab, Bitbucket).
    - Import the project into Vercel.
    - Vercel will automatically detect the configuration.

### GitHub Pages

This project is ready to be deployed on GitHub Pages.

1. Push the code to GitHub:
   ```bash
   git push -u origin main
   ```

2. Go to your GitHub repository settings:
   - Navigate to **Settings** > **Pages**
   - Under **Build and deployment**, select **Source** as `Deploy from a branch`
   - Select `main` (or `gh-pages`) branch and `/ (root)` folder
   - Click **Save**

3. Your site will be live at `https://xiaofeng19931010-bot.github.io/mantahome/` (URL may vary based on your settings).
