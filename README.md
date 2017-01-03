# restaurant_hybrid_template
nice css layout features

check readme.testing for info on protractor/ selenium test harness via npm

in essence

Clone the github repository:

git clone https://github.com/angular/protractor.git
cd protractor
npm install
./bin/webdriver-manager update
cd website
npm install
cd ..

Start up a selenium server. By default, the tests expect the selenium server to be running at http://localhost:4444/wd/hub. A selenium server can be started with webdriver-manager which is included in bin/webdriver-manager.

webdriver-manager update
webdriver-manager start
Protractor's test suite runs against the included test application.

Install the test application dependencies with:

npm run install_testapp
Start web server for this html and css template

npm start
Then run the tests with

npm test
