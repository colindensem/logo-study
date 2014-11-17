Logo Study
===

A logo text selector tool. A single page packed with google fonts, and example text /styles applied.
  
Scanning the options, should reveal a logo font that "is right".  

This uses Bootstrap & Google fonts, a selection on popular ones.



Requires
---
  [less](http://lesscss.org/) compiler.
  
  Watch ./less compile to ./css

Getting Started
---
  
 Example text, A sample text is used and is split into a head(h) and tails(t) word(s). To control styling/design we apply styles to head, tail or both. Use padding-left/right to control h/t spacing.
  
 Examples: 
  
 *   Head: 'talk' Tail: 'Mountains'
 
           talkMountains
 
 *    Head: 'Helix' Tail: 'App'
 
          HelixApp
 
 *    Head: 'Mercedes' Tail: 'Racing Division'
 
          MercedesRacing Division
         
         
 *    Sample Row        
         
         <div class="col-sm-3">
           <h2 class="logo logo-1">
             <h>talk</h><t>Mountains</t>
           </h2>
         </div>
          
Files to edit, all three of them:
  
  *   style.less Make changes to fonts requested
  *   logo-study.html to edit the text and css font classes tested.
  *   logo.less Make changes to the styles for each combination of logo-##
  
  
Todo: Automate the font/container styling ( dry ).

Todo: Add text font snippet/combinations.

Influencers
---
I struggled on fonts till I began following and reading [Jarrods] [1] work. Watching a [video] [2] made the light bulb come on. 


[1]: http://studiofellow.com/ "Jarrod StudioFellow"
[2]: https://www.youtube.com/watch?v=n-EcpXbkKyc "Design a logo video"


LICENSE
---
MIT
