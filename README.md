Hello!

Welcome to the photo mosaic project.  

A photo mosaic is a large-scale picture created by combining many small photos.

The aim of this project is to make it easy for you to create mosaics from your existing Google Photos albums.

If you don't have any photos on Google at the moment, the below instructions will get you started using some publicly shared photos. 

NOTE:  If you already have some suitable photos on Google, you can skip steps 1-3 below.


### Instructions:

1.  Sign up for a Google account if for some reason you don't have one already

2.  Add/join [ths album](https://photos.google.com/share/AF1QipObFrD-wTNYMZ3jZ__n8RXd5dV_vFIebNy8VCqL8d7cIZzUlfyhMvLeXkOtEgxUBA?key=R2REQ0ZlOE9jVWJyUTlZcVoxbHh3N2NaTjlkRm1R) in Google Photos

    This album contains "source" images which we will use to create the mosaic.  This is a public album that was selected because it contains a variety of colourful images.

3.  Add/join [this album](https://photos.app.goo.gl/NP2YqkyDLu4SbkV88) in Google Photos

    This album contains a "target" image.  We will try to create a photo mosaic that looks like this image.

4.  Visit [the main site](https://us-central1-handy-station-246311.cloudfunctions.net/authenticator) and follow the prompts:
    - Sign in with Google when prompted and allow the app access to your photos
    - Select an album cover containing the "source" images (it might take a few seconds for the album covers to appear)
    - Select one of your photos to use as the "target" image (it might take a few seconds for your photos to appear)
    - Wait up to 2 minutes for the mosaic to be created
    

### Notes:

- This is an early protoype so there are lots of things that might not work very well
- Creation of the final mosaic should take up to 2 minutes (after two minutes if a mosaic hasn't been created the app should give up and return an error)
- The final mosaic consists of a 32x32 grid (1024 images)
- Please don't select albums much larger than 1024 images (the app should still work but processing time and resource usage might be increased)
- When authorising the app to access your photos, all of the requested permissions are required and if you don't provide some of these the process might fail inexplicably for no reason
- The target photo selector probably doesn't work very well if you have lots of photos (Sorry!)
- If you select the wrong album or photo by mistake you can press the back button on your browser at any point
- Remember, the quality of the final mosaic will depend on how suitable your source photos are for the target you have chosen

If you have any feedback, suggestions or problems feel free to raise an issue on GitHub!
