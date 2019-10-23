[![N|Solid](assets/img/django_logo.png)](https://docs.djangoproject.com/en/2.2/)
# Django core
This is a pre built django template to make project setup faster. It includes an environment file based configuration, a ready built template and static file structure, a gulp workflow for frontend works, and a blank core app.
## Usage:


### requirements.txt
First you need to install the dependencies. Run:
`pip install -r requirements.txt`. It gets all the python packages you need.


### .env
Create a `.env` file in the root directory - based on the `.env.example` file. The project will load more sensitive central data from here. Extend it as later needed.

### Gulp workflow
This gulp workflow is meant to make your template building process way faster and more efficient. 
1. install node.js in order to be able to use npm
2. run: `npm install -global gulp-cli`
3. install the necessary node modules: `npm install`
4. run the gulp tasks `gulp`
5. To start building, run: `gulp watch`


Ready to work.

version: 1.1

For help, contact: nyitrai.done@gmail.com