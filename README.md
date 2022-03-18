### insperation
https://github.com/thecodercoder/frontend-boilerplate

### start project
Enter with this command `cd dist` to the dist folder
start localy the php serve with `php -S localhost:9002`
To compile the files use: `gulp` in your terminal

### Publish to S3
git push to main trigger the github action. Github action insatll node and gulp and run gulp. Afterwards gulp copy all file to the dist folder. GitHub Action copy these folder to aws s3.

npm install --save-dev gulp-replace