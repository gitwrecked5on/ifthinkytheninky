 Clone the original Excalidraw repo
git clone https://github.com/excalidraw/excalidraw.git ifthinkytheninky

# Enter your new project
cd ifthinkytheninky

# Install dependencies for the monorepo (build tools, shared packages)
yarn install

# Enter the main app folder
cd excalidraw-app

# Install dependencies for the React app
yarn install

# Test that the app works locally
yarn start

# Open VSCode workspace
cd ..
code .
# Then File → Save Workspace As... → ifthinkytheninky.code-workspace