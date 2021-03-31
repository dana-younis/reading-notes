# Images” (pp.94-125
* * It is good practice to create a folder for all pictures the site uses if you build a website at all levels,You can add subfolders to the pictures directory on a large website. Pictures such, for example as logos and buttons may be in placea directory called interface, product  Pictures may be on a page
Products and images called Maybe in a link to news  Called new folder
* * You have to use an element to add a picture to the page. This is a vacuumElement . They have to bear the
Two attributes follow:
- SRC The browser says whereThe image file can be found. This is what we are talking about.Usually a relative URL will be pointing to your picture Own site.

- alt ,This gives a description of text of the picture that describes Picture unless you can see it.
- Title , The title attribute with the element can also be used to provide further information The picture. 
- high , This indicates the height of the.
- The pixel image. This specifies the pixel width of the picture.

* *  place of the image 
-  in front of an item After the image begins the paragraph on a new line.
-  inside the paragraph beginning The first row of the text matches the image's bottom.
-  in a paragraph midway through The picture is placed among the words in the paragraph

* * align,The alignment attribute was used to indicate how an image would flow through other sections of a page. It was removed from HTML5 and new websites are supposed to use CSS to control image alignment.

* * There are three values that can be controlled by the aligned attribute Align with the text vertically Surrounds it: surrounds it:
- top ,This is in line with the first line text with the top of the The picture.
- The Middle This is in line with the first line text surrounding The picture.
- Bottom ,this is in line with the first line text in the surrounding area the picture

* * Based on web images, the resolution of 72 ppi should be saved. The greater the image resolution, the larger the file size.
* * Vector images differ in resolution from bitmap images. In programs such as Adobe Illustrator, vector images are usually created. 
* * Animated GIFs display multiple image frames in sequence and can thus be used to create simple animations.
* * Create a partially transparent image or "see-through"
* *Figure Images are frequently provided with subtitles. A new figure element has been added to HTML5 to contain images and their titles to link them with them.In the figure element, you can have more than one image so long as all share the same title. 

## Chapter 11: “Color” (pp.246-263
*  Values of rgbThe colors express the red, green and blue used for making it. 
*  Codes for hex These six-digit codes are red, green and blue, followed by a pound or hash # symbol in one colour.
* Names of color ,The browsers recognize 147 predefined color names.

* * In the image editing programs such as Photoshop and GIMP, color picking tools are available. Next to the radio buttons that speak R, G, B can be viewed the RGB values.Next to the Pound or Hash# symbol is provided the hex value.
* Hue ,The colloquial color idea is close to Hue. However, a color can technically also have saturation, luminosity and hue.

* Saturation The amount of gray in a color is referred to in saturating. There would be no gray in the color at maximum saturation. The color would be mostly gray at least saturation. Luminosity
* Brightness refers to the amount of black in the color (or value).There would be no black color at maximum brightness. The color would be very dark at least brightness.

* * CSS3 presents the opacity property to specify an element's opacity and all the elements of her child.
* *CSS3 presents a completely new and intuitive way of specifying colors with the use of hue , saturation and lightness. 

* * Hue This is an angle This (between 0 and 360 degrees).
* * saturation The percentage is expressed.
* * lightness This is expressed as a proportion of white 0 percent, normal 50% and black 100 percent. 



### Chapter 12: “Text” (pp.264-299)

* * Typeface Terminology

* Serif  ,Serif fonts have additional information on the end of the letters' main strokes. The details are referred to as serifs.Serif fonts have traditionally been used in print for long text passages because they were thought to be easier to read.
* Sans- serif,Sans-serif fonts have straight lines, and have a cleaner design. Screens' resolution is lower than that of printing. Therefore, unserified fonts could be clearer for reading when the text is small.
* Monospace Each letter is the same width in a monospace  fixed width font. there are different widths for non-monospace fonts 
* * This often leads to the use of a small number of types on most computers (shown above). Some techniques are available to overcome this limitationMore than one typeface can be specified and a preference order can be created (in case the user does not have your first typeface choice installed). Sometimes this is called a font pile
* * Monospace Each letter is of the same width in a single space typeface.There are different widths for non-monospace fonts.
* * Cursive fonts have strokes or other cursive features like handwriting styles.
* * fantasy,Usually the fantasy font is decorative and is used for titles. It's not intended for long text bodies.

* * The font-family property can specify the typeface for any text in the element that applies for a CSS rule.The name of the typeface you want to use is the value of this property. 
* * The font-size property enables you to specify a size for the font
* * Type Scales 

* * This is because they are determined in a size or ratio developed in the seventeenth century by European typographers.This scale for type is thought to be a good thing for the eye 
* * The text-indent property allows the first line of text to be inserted into an element.There are a number of ways to specify the amount you want to enter the line, but it is normally given in pixels or ems. 
* * text-shadow ,It is used for creating a drop shadow that is a dark, slightly compensating version of the word behind it. It can also be used to create a precipitated effect by adding a slightly lighter shadow than the text

* * Browsers display links in blue with a default highlight and change the color of the links visited to aid users in knowing which pages they were on.
* link: This allows you to specify styles for links not visited yet.
* visited This enables you to configure styles for the links you clicked on.
* * The space between lines of text, letters and words can be controlled. Text may also be left, right, center or legitimate aligned. It can be dented as well.
* * If a user hovers over or clicks text, or visits a link, you can use pseudo-classes to change the style of an element.
