# Photography
A jekyll website for photographers

## Highlights
1. Easy setup and you get a site of your own for __free__.
2. To add new pictures, you need to just upload them. __No code__ changes required.
3. This I like the most, you get to see EXIF data like __aperture, shutter speed, iso__ etc when you click on any image automagically.

## Quick Start
If you know a tad about tech and love taking pictures then this open-source project may help you setup a website to showcase
all your creations without effort. And not just that, with this you need not pay a single dime to host your website as
it's hosted by GitHub for __free__.

**Just follow the below steps and your website would be live in no time:**

1. Fork this repo by hitting the `Fork` button at the top right corner.
2. Enable github pages from the repo settings.
3. Upload your pictures to `images/fulls` and `images/thumbs` directory. _You can do that on github.com itself or you can clone and push the images to your repo._
4. Add your own custom domain in `CNAME` file or just remove the file if you don't own a domain and use the default domain that github provides ([yourusername].github.io/photography).
5. Update `baseurl` field in `_config.yml` file with whatever domain you used in step 4.
6. And that's it, your website is set. 

And of course, you don't want my name at the bottom to show up. You can change it in `_config.yml` file as well as few other settings like your google analytics etc.
 
## ProTips
I have made this as an [npm](https://www.npmjs.com) package with [gulp](http://gulpjs.com/) to __automate image resizing
and thumbnail generation__. So if you're lazy like me then you can just do the following before you push your images to github.

1. Fork and then clone the project to your computer
2. Go inside the project `$ cd photography`
3. Install all dependencies by `$ npm install`
4. Copy all your pictures (possibly jpg, the largest size available, straight from your camera) and put it inside `images` directory
5. Run `$ gulp` to resize the images and to generate thumbnails automatically
6. Push your changes to github.com by `$ git commit -am "a nice commit message"` and then `$ git push origin master`

## Credits
Thanks to [AJ](https://twitter.com/ajlkn) for the website template which I enhanced for [jekyll](http://jekyllrb.com/).


