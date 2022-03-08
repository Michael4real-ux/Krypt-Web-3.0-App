## Krypt - Web 3.0 Blockchain Application



## DESCRIPTION
This is a dencentralized smart contract app where users can send and recieve cryptocoin on real time.This unique smart contract app is a version of Web 3.0. Users are authenticated using metamask and many more amazing features which is the future of web.
Technologies Used - React.js ,solidity, hardhat,Metamask ,Tailwind css.

## Install Tailwind CSS with Create React App
## Setting up Tailwind CSS in a Create React App project.




# Terminal

npx create-react-app my-project
cd my-project
 Save

# Install Tailwind CSS
# Install tailwindcss and its peer dependencies via npm, and then run the init command to generate both tailwind.config.js and postcss.config.js.

# Terminal

npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p

yarn add postcss-cli autoprefixer --save-dev
yarn add tailwindcss --dev
npx tailwindcss init -p
 Save

# Configure your template paths
# Add the paths to all of your template files in your tailwind.config.js file.

tailwind.config.js

module.exports = {
  content: [
    "./src/**/*.{js,jsx,ts,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
 Save

# Add the Tailwind directives to your CSS
# Add the @tailwind directives for each of Tailwind’s layers to your ./src/index.css file.

index.css

@tailwind base;
@tailwind components;
@tailwind utilities;
 Save

# Start your build process
 # Run your build process with npm run start.

Terminal

npm run start
yarn start
