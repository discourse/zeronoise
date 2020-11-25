# Zeronoise
## A Modern Discourse Theme 

This is a CSS Only theme. 

The main goal of the theme is improve readability, defining the interest areas and separating them from the background through color. 
It also tries to emphasize the topics and the authors through text hierarchies. 

![topic-list](https://user-images.githubusercontent.com/1082144/100288931-617ca000-2f3d-11eb-8687-dd2dcdd2d6e9.png)

## Colors
You can edit the color palette in the `about.json` file
The main colors of the theme in order of importance are: 

### header_background 
It's used in the site header through all the platform

### tertiary
Is the accent color, which gives a voice to the theme. You can replace it by a brand color, or another accent that suits for you

### quaternary
This is the color of the light backgrounds and light accents (good ol' #FFF)

### secondary
This is the body background color which serves as a basis to make the white backgrounds pop. 

### primary 
It's basically the Body and Title text color

### Color goodies 
You can manipulate the `--main-background` and `--light-accent` colors in the `variables.scss` file just in case you don't want them to be equal. 

### Why I didn't followed the original color scheme hierarchy? 
It was easier to edit the theme like that from a technical point of view. 
A side note: That's why I don't like the "primary, secondary…" naming convention; it's hard to tell what has to be the primary color, because it's completely up to the author. For me, primary would be the brand, secondary would be the background, and so on, but I'd prefer calling them by their function, for example: brand, main-background, secondary-background, text, headings, etcetera. 

## Theme fonts 
I added the Playfair Display Font to make the titles a bit more interesting. You can change this font in the `variables.scss` under the `--heading-font-family` custom property.

## Theme Settings 
Since I'm using a black background in the header and the discourse logo is mainly dark, I used some css filters to add contrast to it. You can check the settings in the `settings.yaml` (and also in the theme page when you install it) in case you want to change something. 

## Final Note. 
I believe all themes are a work in progress so feel free to open an issue if you have suggestions, and obviously to fork it if you want to make it to your taste :) 

## More screenshots to give you a sneak a peek
<img src="https://user-images.githubusercontent.com/1082144/100288928-60e40980-2f3d-11eb-8261-14dae619f103.png" width="50%" alt="topic"/>
<img src="https://user-images.githubusercontent.com/1082144/100288929-617ca000-2f3d-11eb-9a77-f6455fa19c26.png" width="50%" alt="topic"/>

## Works good on mobile of course 
<img src="https://user-images.githubusercontent.com/1082144/100288922-5fb2dc80-2f3d-11eb-8bd9-facb2c90cd31.PNG" width="200" alt="topic"/>
<img src="https://user-images.githubusercontent.com/1082144/100288926-604b7300-2f3d-11eb-9954-6692916deedc.PNG" width="200" alt="topic"/>
<img src="https://user-images.githubusercontent.com/1082144/100288917-5d508280-2f3d-11eb-9266-5b49fafbb1ed.PNG" width="200" alt="topic"/>
<img src="https://user-images.githubusercontent.com/1082144/100288919-5f1a4600-2f3d-11eb-9f8c-348b530441b4.PNG" width="200" alt="topic"/>


