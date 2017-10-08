## Website Performance Optimization portfolio project


### How to run the application locally
1. Go to the following github page: https://github.com/stefets42/website_optimization
2. Click on the green "Clone or download" button
3. Copy the address: https://github.com/stefets42/website_optimization.git
4. Open the terminal
5. Go to the folder where you want to copy this project
6. Run the server:
    1. If you have Python 2, run: python -m SimpleHTTPServer 8000
    2. If you have Python 3, run: python -m http.server 8000
7. On your browser, navigate to: http://localhost:8000/
    1. As there is a file called index.html in the directory, it should automatically show up
    2. If not, you should see the files in that directory listed: click on the index.html file and watch it load


### Optimizations made to the given files
#### Optimizations made in index.html
- Inlined minified style.css and print.css
- Removed link to Open Sans fonts
- Added async to scripts

#### Optimizations made in views/js/main.js for pizza.html
- Created randomPizzas variable
- Modified changePizzaSizes
- Replaced querySelectorAll by getElementsByClassName
- Removed the dot from the classname in the getElementsByClassName function
- Moved the scrollTop variable outside of the loop inside the updatePositions function
- Created the height variable
- Dynamically calculated the number of pizzas needed to fill the background

#### Optimizations made in pizza.html
- Created 2 copies of pizzeria.jpg and optimized each of them for its unique purpose

#### Optimizations made in README file
- Detailed all steps required to successfully run the application locally