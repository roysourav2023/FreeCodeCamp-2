CSS BOX Model - 
    CSS treats each element as its own box. The default layout is called the normal flow. 

Different position types -
    1) Relative
        When the position of an element is set to relative,it allows you to specify how CSS should move it relative to 
        its current position in the normal flow of the page. It pairs with the CSS offset properties of 
        left or right, and top or bottom.
       
        Changing an element's position to relative does not remove it from the normal flow - other elements around it 
        still behave as if that item were in its default position.
        
    2) Absolute
        When the position is set to absolute ,it locks the element in place relative to its nearest positioned ancestor
        This removes the element from the normal flow of the document, so surrounding items ignore it

    3) Static
        These elements are not affected by top,bottom,left,right and are always positioned according to the normal flow
        
    4) Fixed
        These elements are positioned relative to the viewport and will stay in the same place even if the page is scrolled

    5) Sticky
        Theu are positioned based on the user's scroll position.
        It is positioned relative until a given offset position is met in the viewport then it "sticks" in place (like position:fixed).