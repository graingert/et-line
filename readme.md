<span class="post-meta">Jan<span>29</span></span>

Posted on January 29, 2014 by [Kenny
Sing](https://www.elegantthemes.com/blog/author/kennysing "Posts by Kenny Sing")
in [Resources](https://www.elegantthemes.com/blog/category/resources) |
<span class="comments-number">[106
comments](https://www.elegantthemes.com/blog/resources/how-to-use-and-embed-an-icon-font-on-your-website#respond)</span>

<div class="post-thumbnail">

![How To Use And Embed An Icon Font On Your
Website](https://cdn.elegantthemes.com/blog/wp-content/uploads/2014/01/iconfont-tut-thumbnail.jpg)

</div>

Last week we released a pack of [100 line-style
icons](http://www.elegantthemes.com/blog/freebie-of-the-week/free-line-style-icons "Download 100 Free Line-Style Icons").
Today we are releasing those exact icons in the form of a 100 piece icon
font along with an extensive tutorial about how to use them. Icon fonts
are great for their scalability on high-resolution displays and they can
be treated and styled exactly like text. Below are steps to embed and
use icon fonts on your very own website. *Note that Icon fonts do not
work in some Windows mobile browsers.*

<span id="jointoday_button">[<span style="padding: 7px 20px">Download
The Font
Pack</span>](http://www.elegantthemes.com/icons/et-line-font.zip)</span>

\

Embedding an Icon Font
----------------------

**1. Download the icon font you wish to use.**\
 In this tutorial we will be using the files from the download above,
which contains an icon font created with
[icomoon](http://icomoon.io/#home "icomoon").\
 *You can also download and use our [Elegant Icons
Font](http://www.elegantthemes.com/blog/resources/elegant-icon-font "The Elegant Icon Font – 360 Of The Best Free Icons For The Modern Web")
if you wish.*

**2. Copy the code from “style.css” and paste it into your own
“style.css” file.**\
 This css file embeds the icon font via @font-face, and has a unique
class for each icon, telling it which character in the font to use. This
is also where unique styling can be added to each icon.\
 *We always recommend using a child theme for this. For more info on
child themes see our [Child Theme
Tutorial](http://www.elegantthemes.com/blog/resources/wordpress-child-theme-tutorial "How To Create A Child Theme, And Why You Should Be Using One").*

**3. Copy the “fonts” folder into your theme directory:**\
 /wp-content/themes/yourtheme/\
 *If your theme directory already has a “fonts” folder, drag the
contents from “fonts” into the existing folder.*

![fonts-directory](https://cdn.elegantthemes.com/blog/wp-content/uploads/2014/01/fonts-directory.jpg)

Using an Icon Font
------------------

**1. If you are using WordPress, this will not work with the visual text
editor.** You will want to disable the visual editor or there is a
chance that all of your code will be deleted after saving. You can do
this in Users\>Your Profile

![disable-visual-editor](https://cdn.elegantthemes.com/blog/wp-content/uploads/2014/01/disable-visual-editor.jpg)

**2. You can now insert these icons into any text area** such as a post,
page, or widget using two different methods.

<div class="boxed">

<div id="highlighter_729695" class="syntaxhighlighter nogutter">

<div class="lines">

<div class="line alt1">

  ----------------
  `HTML`{.plain}
  ----------------

</div>

<div class="line alt2">

  ---------------------------------------------------------------------------
  `<!-- Use the following if you want to use class selectors-->`{.comments}
  ---------------------------------------------------------------------------

</div>

<div class="line alt1">

  ------------------------------------------------------------------------------------------------------------------------
  `<`{.plain}`span`{.keyword} `class`{.color1}`=`{.plain}`"icon-phone"`{.string}`></`{.plain}`span`{.keyword}`>`{.plain}
  ------------------------------------------------------------------------------------------------------------------------

</div>

<div class="line alt2">

  ---
   
  ---

</div>

<div class="line alt1">

  ----------------------------------------------------------------------------
  `<!-- Use the following if you want to use data attributes.-->`{.comments}
  ----------------------------------------------------------------------------

</div>

<div class="line alt2">

  -------------------------------------------------------------------------------------------------------------------------
  `<`{.plain}`span`{.keyword} `data-icon`{.color1}`=`{.plain}`"&#xe004"`{.string}`></`{.plain}`span`{.keyword}`>`{.plain}
  -------------------------------------------------------------------------------------------------------------------------

</div>

</div>

</div>

<div style="text-align: center;margin-top: 40px; margin-bottom:20px;">

<span class="icon-phone" style="font-size: 32px;"></span><span
data-icon="&amp;#xe004"
style="font-size: 32px; margin-left: 40px;"></span>

</div>

*The results are visually the same, but we will be using the class
method so that we can easily style the icons using external CSS.*

</div>

\

<span class="big icon-genius" style="color:#66B9AC;"><span
class="big icon-tools" style="color:#F5953C;"><span
class="big icon-happy" style="color:#5A92C5;"></span></span></span>

Examples of Styling and Implementation
--------------------------------------

The instructions and examples below cover some of the different ways you
can use an icon font on your website. Again, we will be using the class
name method and styling the font with external CSS.

1. Placing Icons Inline
-----------------------

You can add an icon within any body of text. You can also style the icon
however you wish by editing the css that you pasted into style.css in
Step 1. Here is an example of an icon used above a Divi Theme header.

![inline-icon](https://cdn.elegantthemes.com/blog/wp-content/uploads/2014/01/inline-icon.jpg)

To achieve this, paste this html into a Divi text module (or any text
field in any theme) and the following css into your style.css file *(or
custom css box in ePanel if you are using an Elegant Theme)*. The main
thing to focus on here is the first line of HTML where I inserted the
icon, and the lines of CSS used to define the icon size and color.

<div class="boxed">

<div id="highlighter_436365" class="syntaxhighlighter nogutter">

<div class="lines">

<div class="line alt1">

  ----------------
  `HTML`{.plain}
  ----------------

</div>

<div class="line alt2">

  ---
   
  ---

</div>

<div class="line alt1">

  --------------------------------------------------------------------------------------------------------------------------
  `<`{.plain}`span`{.keyword} `class`{.color1}`=`{.plain}`"icon-tools-2"`{.string}`></`{.plain}`span`{.keyword}`>`{.plain}
  --------------------------------------------------------------------------------------------------------------------------

</div>

<div class="line alt2">

  ---------------------------------------------------------------------------------------------
  `<`{.plain}`h1`{.keyword}`>Advanced Drag & Drop Builder</`{.plain}`h1`{.keyword}`>`{.plain}
  ---------------------------------------------------------------------------------------------

</div>

<div class="line alt1">

  -----------------------------------------------------------------------------
  `Combining our various modules, you can build just about anything.`{.plain}
  -----------------------------------------------------------------------------

</div>

</div>

</div>

<div id="highlighter_692061" class="syntaxhighlighter nogutter">

<div class="lines">

<div class="line alt1">

  ---------------
  `CSS`{.plain}
  ---------------

</div>

<div class="line alt2">

  ---
   
  ---

</div>

<div class="line alt1">

  ------------------------------------------------------
  `.icon-tools`{.plain}`-2:`{.value}`before {`{.plain}
  ------------------------------------------------------

</div>

<div class="line alt2">

  -----------------------------------------------------------------------------
  `    `{.spaces}`content`{.keyword}`: `{.plain}`"\e034"`{.string}`;`{.plain}
  -----------------------------------------------------------------------------

</div>

<div class="line alt1">

  ---------------------------------------------------------------------------
  `    `{.spaces}`font-size`{.keyword}`: `{.plain}`64px`{.value}`;`{.plain}
  ---------------------------------------------------------------------------

</div>

<div class="line alt2">

  --------------------------------------------------------------------------
  `    `{.spaces}`color`{.keyword}`: `{.plain}`#318EC3`{.value}`;`{.plain}
  --------------------------------------------------------------------------

</div>

<div class="line alt1">

  -------------
  `}`{.plain}
  -------------

</div>

</div>

</div>

</div>

\

2. Adding an Icon to Navigation Labels
--------------------------------------

Using an icon font, you can add an icon to your navigation items to give
your page titles a little something extra. Below is an example using the
Nimble Theme.

![navigation-label-icons](https://cdn.elegantthemes.com/blog/wp-content/uploads/2014/01/navigation-label-icons.jpg)

In the Menu Editor, you can add an icon span at the beginning of your
Navigation Label to achieve this affect. You can also use just an icon
for a Navigation Label like the RSS icon in the example above. This
could be a cool way to add social media icon links to your navigation.

![icon-navigation-label](https://cdn.elegantthemes.com/blog/wp-content/uploads/2014/01/icon-navigation-label.jpg)\
\

3. Using Icons as Hyperlinks
----------------------------

Because this is a font, anything that you can do to traditional text,
can be applied to an icon font. Here is an example of an icon being used
as a link. In addition, I’ve also added a hover state that makes the
icon semi transparent. *Try it out below!*

<div id="download">

[<span class="icon-download"></span>](http://www.elegantthemes.com)\
 DOWNLOAD

</div>

\

To achieve this, paste this html into a text field, and the following
css into your style.css file (or custom css box in ePanel).

<div class="boxed">

<div id="highlighter_729605" class="syntaxhighlighter nogutter">

<div class="lines">

<div class="line alt1">

  ----------------
  `HTML`{.plain}
  ----------------

</div>

<div class="line alt2">

  --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  `<`{.plain}`a`{.keyword} `href`{.color1}`=`{.plain}`"http://www.elegantthemes.com"`{.string}`><`{.plain}`span`{.keyword} `class`{.color1}`=`{.plain}`"icon-download"`{.string}`></`{.plain}`span`{.keyword}`></`{.plain}`a`{.keyword}`>`{.plain}
  --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

</div>

<div class="line alt1">

  --------------------
  `DOWNLOAD`{.plain}
  --------------------

</div>

</div>

</div>

<div id="highlighter_860350" class="syntaxhighlighter nogutter">

<div class="lines">

<div class="line alt1">

  ---------------
  `CSS`{.plain}
  ---------------

</div>

<div class="line alt2">

  -----------------------------------
  `.icon-download:before {`{.plain}
  -----------------------------------

</div>

<div class="line alt1">

  -----------------------------------------------------------------------------
  `    `{.spaces}`content`{.keyword}`: `{.plain}`"\e04d"`{.string}`;`{.plain}
  -----------------------------------------------------------------------------

</div>

<div class="line alt2">

  ---------------------------------------------------------------------------
  `    `{.spaces}`font-size`{.keyword}`: `{.plain}`64px`{.value}`;`{.plain}
  ---------------------------------------------------------------------------

</div>

<div class="line alt1">

  ---------------------------------------------------------------
  `    `{.spaces}`color`{.keyword}`: `{.plain}`#318EC3`{.value}
  ---------------------------------------------------------------

</div>

<div class="line alt2">

  -------------
  `}`{.plain}
  -------------

</div>

<div class="line alt1">

  ---
   
  ---

</div>

<div class="line alt2">

  -----------------------------------------
  `.icon-download:hover:before {`{.plain}
  -----------------------------------------

</div>

<div class="line alt1">

  -----------------------------------------------------------
  `    `{.spaces}`opacity:`{.plain}`0.5`{.value}`;`{.plain}
  -----------------------------------------------------------

</div>

<div class="line alt2">

  -------------
  `}`{.plain}
  -------------

</div>

</div>

</div>

</div>

\

4. Styling Multiple Icons at Once
---------------------------------

By adding a unique class to a group of icons, we can target multiple
icons at once. A good example of this is adding icons to the beginning
of list items. If we want to give all of these icons the same styling we
can assign them an addition class to get an effect such as this.

<div id="icon-list" class="boxed">

<span class="icon-envelope icon-list"></span> Envelope Lorem Ipsum\
 <span class="icon-mobile icon-list"></span> Mobile Lorem Ipsum\
 <span class="icon-megaphone icon-list"></span> Speaker Lorem Ipsum\
 <span class="icon-chat icon-list"></span> Chat Lorem Ipsum\
 <span class="icon-genius icon-list"></span> Genius Lorem Ipsum

</div>

\

To achieve this I have given each icon a class of “icon-list” and
defined a few css styles for optimal alignment.

<div class="boxed">

<div id="highlighter_64282" class="syntaxhighlighter nogutter">

<div class="lines">

<div class="line alt1">

  ----------------
  `HTML`{.plain}
  ----------------

</div>

<div class="line alt2">

  ----------------------------------------------------------------------------------------------------------------------------------------------------------
  `<`{.plain}`span`{.keyword} `class`{.color1}`=`{.plain}`"icon-envelope icon-list"`{.string}`></`{.plain}`span`{.keyword}`> Envelope Lorem Ipsum`{.plain}
  ----------------------------------------------------------------------------------------------------------------------------------------------------------

</div>

<div class="line alt1">

  --------------------------------------
  `<`{.plain}`br`{.keyword}`>`{.plain}
  --------------------------------------

</div>

<div class="line alt2">

  ------------------------------------------------------------------------------------------------------------------------------------------------------
  `<`{.plain}`span`{.keyword} `class`{.color1}`=`{.plain}`"icon-mobile icon-list"`{.string}`></`{.plain}`span`{.keyword}`> Mobile Lorem Ipsum`{.plain}
  ------------------------------------------------------------------------------------------------------------------------------------------------------

</div>

<div class="line alt1">

  --------------------------------------
  `<`{.plain}`br`{.keyword}`>`{.plain}
  --------------------------------------

</div>

<div class="line alt2">

  ----------------------------------------------------------------------------------------------------------------------------------------------------------
  `<`{.plain}`span`{.keyword} `class`{.color1}`=`{.plain}`"icon-megaphone icon-list"`{.string}`></`{.plain}`span`{.keyword}`> Speaker Lorem Ipsum`{.plain}
  ----------------------------------------------------------------------------------------------------------------------------------------------------------

</div>

<div class="line alt1">

  --------------------------------------
  `<`{.plain}`br`{.keyword}`>`{.plain}
  --------------------------------------

</div>

<div class="line alt2">

  --------------------------------------------------------------------------------------------------------------------------------------------------
  `<`{.plain}`span`{.keyword} `class`{.color1}`=`{.plain}`"icon-chat icon-list"`{.string}`></`{.plain}`span`{.keyword}`> Chat Lorem Ipsum`{.plain}
  --------------------------------------------------------------------------------------------------------------------------------------------------

</div>

<div class="line alt1">

  --------------------------------------
  `<`{.plain}`br`{.keyword}`>`{.plain}
  --------------------------------------

</div>

<div class="line alt2">

  ------------------------------------------------------------------------------------------------------------------------------------------------------
  `<`{.plain}`span`{.keyword} `class`{.color1}`=`{.plain}`"icon-genius icon-list"`{.string}`></`{.plain}`span`{.keyword}`> Genius Lorem Ipsum`{.plain}
  ------------------------------------------------------------------------------------------------------------------------------------------------------

</div>

</div>

</div>

<div id="highlighter_25158" class="syntaxhighlighter nogutter">

<div class="lines">

<div class="line alt1">

  ---------------
  `CSS`{.plain}
  ---------------

</div>

<div class="line alt2">

  -----------------------
  `.icon-list{`{.plain}
  -----------------------

</div>

<div class="line alt1">

  -----------------------------------------------------------------------
  `    `{.spaces}`width`{.keyword}`: `{.plain}`25px`{.value}`;`{.plain}
  -----------------------------------------------------------------------

</div>

<div class="line alt2">

  -------------------------------------------------------------------------------
  `    `{.spaces}`text-align`{.keyword}`: `{.plain}`center`{.value}`; `{.plain}
  -------------------------------------------------------------------------------

</div>

<div class="line alt1">

  --------------------------------------------------------------------------
  `    `{.spaces}`color`{.keyword}`: `{.plain}`#AD1EB9`{.value}`;`{.plain}
  --------------------------------------------------------------------------

</div>

<div class="line alt2">

  -------------
  `}`{.plain}
  -------------

</div>

</div>

</div>

</div>

\

5. Styling Your Icons with CSS Animations.
------------------------------------------

You can do some really interesting things with icons fonts using CSS
animations, and because they are vector graphics, animations will not
degrade the quality of the icons. Below are just a few examples of what
can be done.

<div class="boxed" <span="">

<span class="icon-dial tick animated"></span><span
class="icon-happy sway animated"></span>

</div>

\

The above animations are entirely controlled by CSS properties defined
below.

<div class="boxed scroll">

<div id="highlighter_408808" class="syntaxhighlighter nogutter">

<div class="lines">

<div class="line alt1">

  ----------------
  `HTML`{.plain}
  ----------------

</div>

<div class="line alt2">

  ------------------------------------------------------------------------------------------------------------------------------
  `<`{.plain}`span`{.keyword} `class`{.color1}`=`{.plain}`"icon-heart pulse"`{.string}`></`{.plain}`span`{.keyword}`>`{.plain}
  ------------------------------------------------------------------------------------------------------------------------------

</div>

<div class="line alt1">

  ----------------------------------------------------------------------------------------------------------------------------
  `<`{.plain}`span`{.keyword} `class`{.color1}`=`{.plain}`"icon-dial tick"`{.string}`></`{.plain}`span`{.keyword}`>`{.plain}
  ----------------------------------------------------------------------------------------------------------------------------

</div>

<div class="line alt2">

  -----------------------------------------------------------------------------------------------------------------------------
  `<`{.plain}`span`{.keyword} `class`{.color1}`=`{.plain}`"icon-happy sway"`{.string}`></`{.plain}`span`{.keyword}`>`{.plain}
  -----------------------------------------------------------------------------------------------------------------------------

</div>

</div>

</div>

<div id="highlighter_638793" class="syntaxhighlighter nogutter">

<div class="lines">

<div class="line alt1">

  ---------------
  `CSS`{.plain}
  ---------------

</div>

<div class="line alt2">

  ---------------------------------------
  `/* Pulsing Heart Icon */`{.comments}
  ---------------------------------------

</div>

<div class="line alt1">

  --------------------
  `.pulse {`{.plain}
  --------------------

</div>

<div class="line alt2">

  ------------------------------------------------------------------------------------
  `    `{.spaces}`-webkit-animation: pulse `{.plain}`4`{.value}`s infinite;`{.plain}
  ------------------------------------------------------------------------------------

</div>

<div class="line alt1">

  ---------------------------------------------------------------------------------
  `    `{.spaces}`-moz-animation: pulse `{.plain}`4`{.value}`s infinite;`{.plain}
  ---------------------------------------------------------------------------------

</div>

<div class="line alt2">

  -------------------------------------------------------------------------------
  `    `{.spaces}`-o-animation: pulse `{.plain}`4`{.value}`s infinite;`{.plain}
  -------------------------------------------------------------------------------

</div>

<div class="line alt1">

  ----------------------------------------------------------------------------
  `    `{.spaces}`animation: pulse `{.plain}`4`{.value}`s infinite;`{.plain}
  ----------------------------------------------------------------------------

</div>

<div class="line alt2">

  -------------
  `}`{.plain}
  -------------

</div>

<div class="line alt1">

  ---------------
  ` `{.spaces} 
  ---------------

</div>

<div class="line alt2">

  ---
   
  ---

</div>

<div class="line alt1">

  -----------------------------------
  `@-moz-keyframes pulse {`{.plain}
  -----------------------------------

</div>

<div class="line alt2">

  ------------------------------------------------------------------------------------------------------------------------------------------------------
  `      `{.spaces}`0%`{.value} `{-moz-transform: scale(`{.plain}`0.9`{.value}`, `{.plain}`0.9`{.value}`); opacity: `{.plain}`0.0`{.value}`;}`{.plain}
  ------------------------------------------------------------------------------------------------------------------------------------------------------

</div>

<div class="line alt1">

  -----------------------------------------------------------------------------
  `     `{.spaces}`50%`{.value} `{opacity: `{.plain}`1.0`{.value}`;}`{.plain}
  -----------------------------------------------------------------------------

</div>

<div class="line alt2">

  --------------------------------------------------------------------------------------------------------------------------------------------------
  `    `{.spaces}`100%`{.value} `{-moz-transform: scale(`{.plain}`1`{.value}`, `{.plain}`1`{.value}`); opacity: `{.plain}`0.0`{.value}`;}`{.plain}
  --------------------------------------------------------------------------------------------------------------------------------------------------

</div>

<div class="line alt1">

  -------------
  `}`{.plain}
  -------------

</div>

<div class="line alt2">

  ---
   
  ---

</div>

<div class="line alt1">

  --------------------------------------
  `@-webkit-keyframes pulse {`{.plain}
  --------------------------------------

</div>

<div class="line alt2">

  ---------------------------------------------------------------------------------------------------------------------------------------------------------
  `      `{.spaces}`0%`{.value} `{-webkit-transform: scale(`{.plain}`0.9`{.value}`, `{.plain}`0.9`{.value}`); opacity: `{.plain}`0.0`{.value}`;}`{.plain}
  ---------------------------------------------------------------------------------------------------------------------------------------------------------

</div>

<div class="line alt1">

  -----------------------------------------------------------------------------
  `     `{.spaces}`50%`{.value} `{opacity: `{.plain}`1.0`{.value}`;}`{.plain}
  -----------------------------------------------------------------------------

</div>

<div class="line alt2">

  -----------------------------------------------------------------------------------------------------------------------------------------------------
  `    `{.spaces}`100%`{.value} `{-webkit-transform: scale(`{.plain}`1`{.value}`, `{.plain}`1`{.value}`); opacity: `{.plain}`0.0`{.value}`;}`{.plain}
  -----------------------------------------------------------------------------------------------------------------------------------------------------

</div>

<div class="line alt1">

  -------------
  `}`{.plain}
  -------------

</div>

<div class="line alt2">

  ---
   
  ---

</div>

<div class="line alt1">

  ------------------------------
  `@keyframes pulse {`{.plain}
  ------------------------------

</div>

<div class="line alt2">

  ----------------------------------------------------------------------------------------------------------------------------------------
  `      `{.spaces}`0%`{.value} `{scale: (`{.plain}`0.9`{.value}`, `{.plain}`0.9`{.value}`); opacity: `{.plain}`0.0`{.value}`;}`{.plain}
  ----------------------------------------------------------------------------------------------------------------------------------------

</div>

<div class="line alt1">

  -----------------------------------------------------------------------------
  `     `{.spaces}`50%`{.value} `{opacity: `{.plain}`1.0`{.value}`;}`{.plain}
  -----------------------------------------------------------------------------

</div>

<div class="line alt2">

  ------------------------------------------------------------------------------------------------------------------------------------
  `    `{.spaces}`100%`{.value} `{scale: (`{.plain}`1`{.value}`, `{.plain}`1`{.value}`); opacity: `{.plain}`0.0`{.value}`;}`{.plain}
  ------------------------------------------------------------------------------------------------------------------------------------

</div>

<div class="line alt1">

  -------------
  `}`{.plain}
  -------------

</div>

<div class="line alt2">

  ---
   
  ---

</div>

<div class="line alt1">

  --------------------------------------
  `/* Ticking Dial Icon */`{.comments}
  --------------------------------------

</div>

<div class="line alt2">

  -------------------
  `.tick {`{.plain}
  -------------------

</div>

<div class="line alt1">

  -------------------------------------------------------------------------------------------------------------------------------------------
  `    `{.spaces}`-webkit-animation: tick steps(`{.plain}`4`{.value}`) `{.plain}`2`{.value}`s infinite `{.plain}`normal`{.value}`;`{.plain}
  -------------------------------------------------------------------------------------------------------------------------------------------

</div>

<div class="line alt2">

  ----------------------------------------------------------------------------------------------------------------------------------------
  `    `{.spaces}`-moz-animation: tick steps(`{.plain}`4`{.value}`) `{.plain}`2`{.value}`s infinite `{.plain}`normal`{.value}`;`{.plain}
  ----------------------------------------------------------------------------------------------------------------------------------------

</div>

<div class="line alt1">

  --------------------------------------------------------------------------------------------------------------------------------------
  `    `{.spaces}`-o-animation: tick steps(`{.plain}`4`{.value}`) `{.plain}`2`{.value}`s infinite `{.plain}`normal`{.value}`;`{.plain}
  --------------------------------------------------------------------------------------------------------------------------------------

</div>

<div class="line alt2">

  -----------------------------------------------------------------------------------------------------------------------------------
  `    `{.spaces}`animation: tick steps(`{.plain}`4`{.value}`) `{.plain}`2`{.value}`s infinite `{.plain}`normal`{.value}`;`{.plain}
  -----------------------------------------------------------------------------------------------------------------------------------

</div>

<div class="line alt1">

  -------------
  `}`{.plain}
  -------------

</div>

<div class="line alt2">

  ---
   
  ---

</div>

<div class="line alt1">

  ---------------------------------------------------------------------------------------------------------------------
  `@-moz-keyframes tick { `{.plain}`100%`{.value} `{ -moz-transform: rotate(`{.plain}`360`{.value}`deg); } }`{.plain}
  ---------------------------------------------------------------------------------------------------------------------

</div>

<div class="line alt2">

  ---
   
  ---

</div>

<div class="line alt1">

  ---------------------------------------------------------------------------------------------------------------------------
  `@-webkit-keyframes tick { `{.plain}`100%`{.value} `{ -webkit-transform: rotate(`{.plain}`360`{.value}`deg); } }`{.plain}
  ---------------------------------------------------------------------------------------------------------------------------

</div>

<div class="line alt2">

  ---
   
  ---

</div>

<div class="line alt1">

  -----------------------------------------------------------------------------------------------------------------------------------------------------------------
  `@keyframes tick { `{.plain}`100%`{.value} `{ -webkit-transform: rotate(`{.plain}`360`{.value}`deg); transform:rotate(`{.plain}`360`{.value}`deg); } }`{.plain}
  -----------------------------------------------------------------------------------------------------------------------------------------------------------------

</div>

<div class="line alt2">

  ---------------
  ` `{.spaces} 
  ---------------

</div>

<div class="line alt1">

  --------------------------------------------
  `/* Swaying Happy-Face Icon */`{.comments}
  --------------------------------------------

</div>

<div class="line alt2">

  -------------------
  `.sway {`{.plain}
  -------------------

</div>

<div class="line alt1">

  ---------------------------------------------------------------------------------------------------------
  `    `{.spaces}`-webkit-animation: sway `{.plain}`3`{.value}`s ease-in-out infinite alternate;`{.plain}
  ---------------------------------------------------------------------------------------------------------

</div>

<div class="line alt2">

  ------------------------------------------------------------------------------------------------------
  `    `{.spaces}`-moz-animation: sway `{.plain}`3`{.value}`s ease-in-out infinite alternate;`{.plain}
  ------------------------------------------------------------------------------------------------------

</div>

<div class="line alt1">

  ----------------------------------------------------------------------------------------------------
  `    `{.spaces}`-o-animation: sway `{.plain}`3`{.value}`s ease-in-out infinite alternate;`{.plain}
  ----------------------------------------------------------------------------------------------------

</div>

<div class="line alt2">

  -------------------------------------------------------------------------------------------------
  `    `{.spaces}`animation: sway `{.plain}`3`{.value}`s ease-in-out infinite alternate;`{.plain}
  -------------------------------------------------------------------------------------------------

</div>

<div class="line alt1">

  -------------
  `}`{.plain}
  -------------

</div>

<div class="line alt2">

  ---------------
  ` `{.spaces} 
  ---------------

</div>

<div class="line alt1">

  ----------------------------------
  `@-moz-keyframes sway {`{.plain}
  ----------------------------------

</div>

<div class="line alt2">

  -------------------------------------------------------------------------------------------------
  `      `{.spaces}`0%`{.value} `{ -moz-transform: rotate(`{.plain}`-15`{.value}`deg); }`{.plain}
  -------------------------------------------------------------------------------------------------

</div>

<div class="line alt1">

  ------------------------------------------------------------------------------------------------
  `    `{.spaces}`100%`{.value} `{ -moz-transform: rotate(`{.plain}`15`{.value}`deg); }`{.plain}
  ------------------------------------------------------------------------------------------------

</div>

<div class="line alt2">

  -------------
  `}`{.plain}
  -------------

</div>

<div class="line alt1">

  ---------------
  ` `{.spaces} 
  ---------------

</div>

<div class="line alt2">

  -------------------------------------
  `@-webkit-keyframes sway {`{.plain}
  -------------------------------------

</div>

<div class="line alt1">

  ----------------------------------------------------------------------------------------------------
  `      `{.spaces}`0%`{.value} `{ -webkit-transform: rotate(`{.plain}`-15`{.value}`deg); }`{.plain}
  ----------------------------------------------------------------------------------------------------

</div>

<div class="line alt2">

  ---------------------------------------------------------------------------------------------------
  `    `{.spaces}`100%`{.value} `{ -webkit-transform: rotate(`{.plain}`15`{.value}`deg); }`{.plain}
  ---------------------------------------------------------------------------------------------------

</div>

<div class="line alt1">

  -------------
  `}`{.plain}
  -------------

</div>

<div class="line alt2">

  ---------------
  ` `{.spaces} 
  ---------------

</div>

<div class="line alt1">

  --------------------------------
  `@-o-keyframes sway {`{.plain}
  --------------------------------

</div>

<div class="line alt2">

  -----------------------------------------------------------------------------------------------
  `      `{.spaces}`0%`{.value} `{ -o-transform: rotate(`{.plain}`-15`{.value}`deg); }`{.plain}
  -----------------------------------------------------------------------------------------------

</div>

<div class="line alt1">

  ----------------------------------------------------------------------------------------------
  `    `{.spaces}`100%`{.value} `{ -o-transform: rotate(`{.plain}`15`{.value}`deg); }`{.plain}
  ----------------------------------------------------------------------------------------------

</div>

<div class="line alt2">

  -------------
  `}`{.plain}
  -------------

</div>

<div class="line alt1">

  ---------------
  ` `{.spaces} 
  ---------------

</div>

<div class="line alt2">

  ---------------------------------
  `@-ms-keyframes sway {`{.plain}
  ---------------------------------

</div>

<div class="line alt1">

  ------------------------------------------------------------------------------------------------
  `      `{.spaces}`0%`{.value} `{ -ms-transform: rotate(`{.plain}`-15`{.value}`deg); }`{.plain}
  ------------------------------------------------------------------------------------------------

</div>

<div class="line alt2">

  -----------------------------------------------------------------------------------------------
  `    `{.spaces}`100%`{.value} `{ -ms-transform: rotate(`{.plain}`15`{.value}`deg); }`{.plain}
  -----------------------------------------------------------------------------------------------

</div>

<div class="line alt1">

  -------------
  `}`{.plain}
  -------------

</div>

<div class="line alt2">

  ---------------
  ` `{.spaces} 
  ---------------

</div>

<div class="line alt1">

  -----------------------------
  `@keyframes sway {`{.plain}
  -----------------------------

</div>

<div class="line alt2">

  --------------------------------------------------------------------------------------------
  `      `{.spaces}`0%`{.value} `{ transform: rotate(`{.plain}`-15`{.value}`deg); }`{.plain}
  --------------------------------------------------------------------------------------------

</div>

<div class="line alt1">

  -------------------------------------------------------------------------------------------
  `    `{.spaces}`100%`{.value} `{ transform: rotate(`{.plain}`15`{.value}`deg); }`{.plain}
  -------------------------------------------------------------------------------------------

</div>

<div class="line alt2">

  -------------
  `}`{.plain}
  -------------

</div>

</div>

</div>

</div>

\

6. Combining Multiple Icons
---------------------------

A huge limitation to icon fonts is that they use SVG assets to create
the icons, which do not support transparency or multiple colors. One way
around this is placing icons directly on top of each other and styling
each icon as desired.

<div class="boxed"
style="height:64px; text-align:center; padding: 40px 20px;">

<span class="icon-laptop stacked"></span><span
class="icon-cloud stacked"></span>

</div>

\

To achieve this affect I have stacked two icons by giving them absolute
positioning and center aligning the two. Below is the HTML and CSS used
to create this demo.

<div class="boxed">

<div id="highlighter_292179" class="syntaxhighlighter nogutter">

<div class="lines">

<div class="line alt1">

  ----------------
  `HTML`{.plain}
  ----------------

</div>

<div class="line alt2">

  -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  `<`{.plain}`span`{.keyword} `class`{.color1}`=`{.plain}`"icon-laptop stacked"`{.string}`></`{.plain}`span`{.keyword}`><`{.plain}`span`{.keyword} `class`{.color1}`=`{.plain}`"icon-cloud stacked"`{.string}`></`{.plain}`span`{.keyword}`>`{.plain}
  -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

</div>

</div>

</div>

<div id="highlighter_96270" class="syntaxhighlighter nogutter">

<div class="lines">

<div class="line alt1">

  ---------------
  `CSS`{.plain}
  ---------------

</div>

<div class="line alt2">

  ----------------------
  `.stacked {`{.plain}
  ----------------------

</div>

<div class="line alt1">

  -------------------------------------------------------------------------------
  `    `{.spaces}`position`{.keyword}`: `{.plain}`absolute`{.value}`; `{.plain}
  -------------------------------------------------------------------------------

</div>

<div class="line alt2">

  -------------------------------------------------------------------------------
  `    `{.spaces}`text-align`{.keyword}`: `{.plain}`center`{.value}`; `{.plain}
  -------------------------------------------------------------------------------

</div>

<div class="line alt1">

  -----------------------------------------------------------------------
  `    `{.spaces}`width`{.keyword}`: `{.plain}`84px`{.value}`;`{.plain}
  -----------------------------------------------------------------------

</div>

<div class="line alt2">

  -------------
  `}`{.plain}
  -------------

</div>

<div class="line alt1">

  ---
   
  ---

</div>

<div class="line alt2">

  -------------------------
  `.icon-laptop{`{.plain}
  -------------------------

</div>

<div class="line alt1">

  ---------------------------------------------------------------------------
  `    `{.spaces}`font-size`{.keyword}`:`{.plain}`64px`{.value}`; `{.plain}
  ---------------------------------------------------------------------------

</div>

<div class="line alt2">

  -----------------------------------------------------------
  `    `{.spaces}`color`{.keyword}`:`{.plain}`#BBB`{.value}
  -----------------------------------------------------------

</div>

<div class="line alt1">

  -------------
  `}`{.plain}
  -------------

</div>

<div class="line alt2">

  ---
   
  ---

</div>

<div class="line alt1">

  -------------------------
  `.icon-cloud {`{.plain}
  -------------------------

</div>

<div class="line alt2">

  ---------------------------------------------------------------------------
  `    `{.spaces}`font-size`{.keyword}`:`{.plain}`32px`{.value}`; `{.plain}
  ---------------------------------------------------------------------------

</div>

<div class="line alt1">

  -----------------------------------------------------------------------------
  `    `{.spaces}`line-height`{.keyword}`:`{.plain}`58px`{.value}`; `{.plain}
  -----------------------------------------------------------------------------

</div>

<div class="line alt2">

  --------------------------------------------------------------
  `    `{.spaces}`color`{.keyword}`:`{.plain}`#318EC3`{.value}
  --------------------------------------------------------------

</div>

<div class="line alt1">

  -------------
  `}`{.plain}
  -------------

</div>

</div>

</div>

</div>

\

Using Icon Fonts in Desktop Applications
----------------------------------------

![iconfont-photoshop](https://cdn.elegantthemes.com/blog/wp-content/uploads/2014/01/iconfont-photoshop.jpg)

Icon Fonts are also compatible with desktop applications. This is great
if you are wanting to use icons in your website mock-ups. As long as the
font is available in a .ttf format, follow the steps below.

**1. Download the .ttf version of the font to your computer.** If you
are one a Mac, double click the .ttf file and you will be prompted to
download it to your fonts directory. If you are on a Windows machine, if
double clicking the .ttf file doesnt work, you will need to place the
.ttf file in your ‘Fonts’ folder found in Control Panel.

**2. Create a text box in whichever desktop application you are working
in** and select your icon font from the fonts menu.

**3. If the the icons were assigned latin characters, then you will be
able to type ‘a’, for example, and the character that was assigned to
‘a’ will appear.** Many icon fonts, however, assign Unicodes to each
character (i.e. U+e000). To type this out on a keyboard you will need to
hold down the Alt (option on a Mac) key while typing the four digits
following U+. So to type out a character with unicode U+e000 you will
hold Alt and type e000. Note: On a Mac you will need to enable Unicode
Hex Input in keyboard settings.

This font, along with [Elegant
Icons](http://www.elegantthemes.com/blog/resources/elegant-icon-font "The Elegant Icon Font – 360 Of The Best Free Icons For The Modern Web")
uses Unicodes. We have provided the HTML codes for you (i.e.
&\#x**e000**). The four digits that follow &\#x in the hmtl codes are
the same last four digits you will need for typing out unicodes (if
there only two digits after &\#x, type 00 before the two digits).

For even more convenience, for the font we are releasing today, we have
provided a list of every icon, its class name, and its html code below.
You can simply copy an icon and past it into your your desktop
application.

ET-Line Icons Class Names and Unicodes
--------------------------------------

<div id="codes">

<div class="icongrid">

<span class="etline codes"></span> .icon-mobile [&\#xe000;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-laptop [&\#xe001;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-desktop [&\#xe002;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-tablet [&\#xe003;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-phone [&\#xe004;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-document [&\#xe005;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-documents [&\#xe006;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-search [&\#xe007;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-clipboard [&\#xe008;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-newspaper [&\#xe009;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-notebook [&\#xe00a;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-book-open [&\#xe00b;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-browser [&\#xe00c;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-calendar [&\#xe00d;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-presentation [&\#xe00e;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-picture [&\#xe00f;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-pictures [&\#xe01;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-video [&\#xe011;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-camera [&\#xe012;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-printer [&\#xe013;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-toolbox [&\#xe014;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-briefcase [&\#xe015;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-wallet [&\#xe016;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-gift [&\#xe017;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-bargraph [&\#xe018;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-grid [&\#xe019;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-expand [&\#xe01a;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-focus [&\#xe01b;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-edit [&\#xe01c;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-adjustments [&\#xe01d;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-ribbon [&\#xe01e;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-hourglass [&\#xe01f;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-lock [&\#xe020;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-megaphone [&\#xe021;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-shield [&\#xe022;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-trophy [&\#xe023;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-flag [&\#xe024;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-map [&\#xe025;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-puzzle [&\#xe026;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-basket [&\#xe027;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-envelope [&\#xe028;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-streetsign [&\#xe029;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-telescope [&\#xe02a;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-gears [&\#xe02b;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-key [&\#xe02c;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-paperclip [&\#xe02d;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-attachment [&\#xe02e;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-pricetags [&\#xe02f;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-lightbulb [&\#xe030;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-layers [&\#xe031;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-pencil [&\#xe032;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-tools [&\#xe033;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-tools-2 [&\#xe034;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-scissors [&\#xe035;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-paintbrush [&\#xe036;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-magnifying-glass [&\#xe037;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-circle-compass [&\#xe038;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-linegraph [&\#xe039;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-mic [&\#xe03a;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-strategy [&\#xe03b;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-beaker [&\#xe03c;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-caution [&\#xe03d;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-recycle [&\#xe03e;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-anchor [&\#xe03f;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-profile-male [&\#xe040;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-profile-female [&\#xe041;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-bike [&\#xe042;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-wine [&\#xe043;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-hotairballoon [&\#xe044;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-glob [&\#xe045;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-genius [&\#xe046;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-map-pin [&\#xe047;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-dial [&\#xe048;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-chat [&\#xe049;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-heart [&\#xe04a;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-cloud [&\#xe04b;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-upload [&\#xe04c;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-download [&\#xe04d;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-traget [&\#xe04e;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-hazardous [&\#xe04f;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-piechart [&\#xe050;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-speedometer [&\#xe051;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-global [&\#xe052;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-compass [&\#xe053;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-lifesaver [&\#xe054;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-clock [&\#xe055;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-aperture [&\#xe056;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-quote [&\#xe057;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-scope [&\#xe058;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-alarmclock [&\#xe059;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-refresh [&\#xe05a;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-happy [&\#xe05b;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-sad [&\#xe05c;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-facebook [&\#xe05d;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-twitter [&\#xe05e;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-googleplus [&\#xe05f;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-rss [&\#xe060;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-tumblr [&\#xe061;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-linkedin [&\#xe062;]

</div>

<div class="icongrid">

<span class="etline codes"></span> .icon-dribbble [&\#xe063;]

</div>

</div>

These are just a few things you can do with icon fonts, so I hope that
this post has given you the tools you need to start using them in your
own websites and maybe even make an icon font of your own!

<span class="et_social_bottom_trigger"></span>

<div class="post-author">

![](https://secure.gravatar.com/avatar/e3c34d74a6ed6d0a9a0492e7d5fde682?s=48&r=g)
<div>

### By Kenny Sing

Kenny is a lead graphic designer here at Elegant Themes. When he's not
designing new themes, he often creates free resources for our readers.

</div>

</div>

[![download
divi](//cdn.elegantthemes.com/images/blog-footer-divi-2.jpg)](http://www.elegantthemes.com/gallery/divi/?utm_source=footer&utm_medium=divi&utm_campaign=blog)
