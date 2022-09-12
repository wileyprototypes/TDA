# TDA
Prototypes to test TDA Email Offer Experience (UR0020 and UR0001)

# Install
npm i

# to compile sass
sass --watch styles/styles.scss styles/styles.css --style compressed

# to compile mjml emails in mjml-code folder - must be in folder to run this command, not parent folder

mjml columns4.mjml -o columns4.html
mjml -w columns4.mjml 
