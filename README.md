# Photography
A jekyll website for photographers

## Highlights
Photos go in `fulls` and thumbnails go in `thumbs`. Filenames can not contain spaces.


**Just follow the below steps and your website would be live in no time:**

1. Fork this repo by hitting the `Fork` button at the top right corner.
2. Enable github pages from the repo settings.
3. Upload your pictures to `images/fulls` and `images/thumbs` directory. _You can do that on github.com itself or you can clone and push the images to your repo._
4. Add your own custom domain in `CNAME` file or just remove the file if you don't own a domain and use the default domain that github provides ([yourusername].github.io/photography).
5. Update `baseurl` field in `_config.yml` file with whatever domain you used in step 4.

Edit `_config.yml` 
 
## Resizing images

To make thumbnails, use ImageMagick and the following command:
	
	mogrify -resize "512>"  -format jpg *.jpg

Make sure you have a separate directory with copies of the original images. 

