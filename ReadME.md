- Install all dependency using npm i 
- Run npm start using terminal and go to localhost:8080

Folder structure
    - src
        - assests
            styles
            Images
            Javascript files
        - Index.html
        - [page].html

- Whenever you add new page 
    - Go to webpack.config.js 
    - Add your page name in pages array at line number 4
    - Terminate your server using (ctrl + c)
    - start server again (npm start)
- Make sure your all css class names are as per BEM methodology (serach it in google)
- Make sure no image should excceed size of 1 MB
- Do not use svg in image tag
- Make new scss file for every new pages and import it in app.scss file