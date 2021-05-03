# Layouts-floats-clearfix
Understanding floats and clear fix
## Container
* Set the container element to 100%;
- e.g `main {width:100%} `
* Apply clearfix to main container
`.clearfix::after{`
    `content:"";`
    `display:block;`
    `clear:both;`
`}`
 
## Float
* Float block elements to the right or left
    * I prefer floating to the left when applying `clearfix` to the container.
    * Set explicitly the width of the containing elements in `percentages` too. 
    - e.g setting 4 elements: section, article, section, with widths `20%, 12%, 30%`;
    -The last element which is an aside for example has to be set explicitly to `100%` irrespective of the element.
    - Setting the last element to 100% occupies all space left in the grid.
    * I realised the last element in the clearfix container does not need a float inorder to work well.
    ### Project screenshot
   
     ![Results of float and clearfix](https://github.com/Tochiskool/layouts-floats-clearfix/blob/main/assets/image/screenshot.jpg?raw=true)

   
[Link to Github pages](https://tochiskool.github.io/layouts-floats-clearfix/)
