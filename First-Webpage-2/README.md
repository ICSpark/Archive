# My First (Or Second?) WebPage 2 Electric Boogaloo
Use HTML and CSS to create a basic webpage.
## Objective
Practice using basic HTML and CSS.
## Main Quest
1. Pick a Web Theme 
  * Anime
  * Rock music
  * Video games 
  * Musicals
  * Short autobiography 
  * Other
2. Format as: <br />
````

<! DOCTYPE html> 

   <html>   
     <head> 
       <title> insert title here </title> 
          </head>  
        <body>  
           Insert everything else here 
        </body>  
        
     </html> 
  ```` 
   ** Note: using a document type declaration, <html> tag, and <title> tag,  aren’t necessary for codepen, but it is typically required for HTML documents.

   ** Note 2: there can only be one <body> element in an HTML document.

   ** For more information on basic HTML described above, click [here](https://www.w3schools.com/html/html_intro.asp).
   
 3. Below are some of the most commonly used HTML tags.  You must use at least one of               
             each in your HTML page.
      * Use at least one [heading](https://www.w3schools.com/tags/tag_hn.asp)  (use at least h1).  Headings go from h1 to h6, with h6 being the smallest.  
      * [Paragraph](https://www.w3schools.com/tags/tag_p.asp)  (p)
      * Bold ([strong](https://www.w3schools.com/tags/tag_strong.asp) or [b](https://www.w3schools.com/tags/tag_b.asp) -- in this project, can use either one).  Note: while both strong and b do almost the same thing, strong is typically used for important text while bold is used to highlight text without showing that text is important.  
      * Italics ([em](https://www.w3schools.com/tags/tag_em.asp) or [i](https://www.w3schools.com/tags/tag_i.asp) --in this project, can use either one).  Note: em and i almost do the same thing, but using em is preferable for emphasized text while i is only used when no other element is more fitting.
      * [Deleted/crossed-out text](https://www.w3schools.com/tags/tag_del.asp) (del).

      * [Line break](https://www.w3schools.com/TAGS/tag_br.asp) (br). 

      * [Link](https://www.w3schools.com/tags/tag_a.asp) (a) --no not the one from Zelda.

      * [Button](https://www.w3schools.com/tags/tag_button.asp) (button).  Note: This button won’t do anything in this project.  You haven’t learned JavaScript yet.
      
  4. Use at least four of the following properties in your CSS to style your HTML:
      * [color](https://www.w3schools.com/cssref/css_colors.asp)
      * [background-color](https://www.w3schools.com/CSSref/pr_background-color.asp)
      * [background-image](https://www.w3schools.com/cssref/pr_background-image.asp)
      * [width](https://www.w3schools.com/CSSref/pr_dim_width.asp)
      * [height](https://www.w3schools.com/cssref/pr_dim_height.asp)
      * [opacity](https://www.w3schools.com/CSSref/css3_pr_opacity.asp)
      * [font-weight](https://www.w3schools.com/csSref/pr_font_weight.asp)
      
 ## Stretch Goal
1. Add [padding](https://www.w3schools.com/csS/css_padding.asp)
   * Add some padding to at least one of your selectors.
   * Note (this is specifically for the shorthand way):
     * Adding only one padding will apply to all sides.  Ex. padding: 10px; → 10px padding will be added on all sides.

     * Adding 2 values means the top and bottom will have the first value and the left and right will have the second value.  Ex. padding: 10px, 0px; 
       -->top and bottom will have 10px while left and right have none (0px).

     * Adding 3 values means the top will get the first value, both left and right will get the second value, and bottom will get the last value.  Ex. padding: 10px, 20px, 30px; → top will get 10px, left and right will get 20px, and bottom will get 30px.

     * Adding 4 values means that there will be one value for each side in clockwise order: top, right, bottom, left.  Ex: 10px, 20px, 30px, 40px; → top will get 10px, right will get 20px, bottom will get 30px, and left will get 40px.


2. Add at least one class and one id.
   * [Classes](https://www.w3schools.com/cssref/sel_class.asp)
     * Change specific tab(s) with selector.

      * In CSS, code you write on the bottom will override what is written above it, but if the code above specifies a class, the code below it cannot override it (unless the code below has an id--more on that later). This is because class is more specific, and thus takes precedence over the other code.

      * Multiple tabs can have the same class.  

      * If you want to change every tab with the same class, you would put in CSS .(class name) { insert code here }.  

      * If you only want to change particular tabs within a class, you put           (tab name).(class name) { insert code here }.  For example, if there is a class called “name1”, and in CSS you put: <br />
       p.name1{ <br />
                  background: yellow; <br />                                                                          
              }  <br />
              It will only change paragraphs (p) in your HTML with the class “name1”.
              
   * [Ids](https://www.w3schools.com/htmL/html_id.asp#:~:text=The%20id%20attribute%20is%20used%20to%20point%20to,define%20the%20CSS%20properties%20within%20curly%20braces%20%7B%7D.)
     * Change one tab on a site (can’t be used for more than one element on a site).

     * Just as classes override things without classes, ids override classes.

     * In CSS, use #(id name) { … } to change something with that id name.




      
      




      
      

      



