# Angular Store Project

## Getting Started

### Prerequisites
- **Node.js**: Ensure Node.js is installed. Download from [nodejs.org](https://nodejs.org/).
- **npm**: Comes bundled with Node.js.

### Installing Node.js and npm
1. Download the LTS version from [nodejs.org](https://nodejs.org/).
2. Run the installer and follow the prompts. (Make sure to select install all needed requirements)
3. Verify installation:
   ```bash
   node --version
   npm --version
   ```

### Running the Project Locally
1. Navigate to the project directory:
   ```bash
   cd path/to/angular-store
   ```
2. Install project dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   nx serve angular-store
   ```
4. Open your browser and go to `http://localhost:4200`.

### Building the Project
1. To build the project for production:
   ```bash
   nx build angular-store --prod --skip-nx-cache
   ```

### Deploying to GitHub Pages
1. Navigate to the build output directory:
   ```bash
   cd dist/apps/angular-store
   ```
2. Initialize a Git repository (if not already done):
   ```bash
   git init
   ```
3. Add the remote repository:
   ```bash
   git remote add origin https://github.com/your-username/AngularSite.git
   ```
4. Add and commit the changes:
   ```bash
   git add .
   git commit -m "Deploy Angular store to GitHub Pages"
   ```
5. Push to the `gh-pages` branch:
   ```bash
   git push -u origin master:gh-pages
   ```

## Accessing the Site
- Your site will be available at: `https://your-username.github.io/AngularSite/`