Stylesheet Activity 1

1) First, make a template file that standardizes the common page elements, then use that for all site files.

2) Add an inline style to the h1 element to color the font: #E6E6FA.

3) Add an inline style using a span tag that applies the rule for color #6A6AA7 to the text: Trillium Media Design 
   on any occurences in a paragraph tag- not in heading tags. Style the font size to be 120%.

4) Add an embedded style in the head section for the h1 element with the background color #191970. 
   Delete the inline color and put that in the embedded style definition.

5) Now remove all inline and embedded styles from all pages.

6) Create the file: trillium.css.
   Add a link to it in all site pages.

   Add the style definitions to the css file- deleting any redundant inline or embedded definitions:

body 
background color #FFFFFF
      
color #191970 


h1  
background color #191970
    
color #E6E6FA


h2 
color #6A6AA7


nav
background color #E2E2EF


footer 
color #666666


7) Create a class called company-name that defines a style rule of: color #6A6AA7.
   Make the span element around instances of Trillium Media Design reference this class.


8) Create an ID style definition called page-content that includes a style rule for font family sans serif.
     Use the <div> element in the html pages to reference this style.

9) Now create a descendant style for the paragraph tag in the footer section of the pages. The style rule will
    specify italic font for this element.





