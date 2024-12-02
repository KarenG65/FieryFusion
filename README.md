1.	 cd /Users/rorymcginnis/Desktop/karen_github/artwork/test/FieryFusion
(Replace with the path to karens on her computer)
2.	Git pull
3.	Open public/art.json and add the following (place the images that you want in the public/img folder for example if you are adding a piece called g_art to garden art add the image to the folder public/img/Garden art and assuming the images name is g_art.png the text that will go under image will be (“public/img/Garden art/g_art.png”)
    ,
    {
      "id": ,
      "name": "",
      "image": "
      "snippet": "",
      "category": [""]
    }
4.	Now run rm -rf node_modules package-lock.json
5.	Now run npm install
6.	You can view the page by running npm start
7.	Now run npm run build
8.	Now run git add .
9.	Now run git commit -m "adding new items"
10.	Now run git push https://KarenG65:(Personal access token)@github.com/KarenG65/FieryFusion.git
