This is a CodeKata that I designed myself to solve a date manipulation problem
If you have a random date of the year, how do you find the beginning of the 
quarter, month, or week that the randomly selected date is within?

Babel compile command: npm run babel
1. npm install npm install babel-cli babel-core --save-dev
2. npm install babel-preset-es2015 --save-dev
3. "scripts": {
    "babel": "babel --presets es2015 js/main.js -o build/main.bundle.js",
}, //in package.json in main file directory
4. create a build directory
5. add <script src="build/main.bundle.js"></script> to index.html

Steps to solving:
1. Write basic index.html to hold everything ---
2. Figure out how to run EC6 ---
3. Figure out how to run Babel ---
4. Setup Q-Unit test environment ---
5. Install moment.js with npm
6. Write Q-Unit test to pass
7. Come up with 2-3 solutions to the problem