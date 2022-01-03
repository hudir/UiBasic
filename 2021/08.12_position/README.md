  div{$}*4

    <div>1</div>
    <div>2</div>
    <div>3</div>
    <div>4</div>
    
## position fixed
fixed --- relative to viewport
the element is removed from the flow of the document.

## center a item

    position: fixed;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
 
transform will target element itself.
    transform: translate(x, y);

## position absolute
the element is positioned relative to its nearest parent with a ___relative-type positioning___.

body by default has a relativ positioning.

## z-index default auto-0
z-index only work on positioned elements.

# Position: sticky;
  top:0;
  if i scroll down and pass the sticky, it will stay at top: 0; fixed position.

  sticky pull the element form the original position to the fixed position you seted(like top:10px;)
