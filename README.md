# Mobile-Tab-Navigation

https://composer0.github.io/Mobile-Tab-Navigation/


Draw in the class items of content to allow the manipulation of the banner image based on which icon is selected.
Draw in the specific nav items/icons to allow click events to manipulate the banner image.

forEach is used as the contes and listItems are arrays due to the amount of inputs that are present and can be rotated through. Total amount 4. For the listItems the 'item' will listen for a 'click' before running two functions hideAllContents and hideAllItems. This is followed immediatly by the items selected have teh class of 'active' added to it. contents then searches through the idx of the item selected it and applies the class 'show' to the index of the listItem that was selected. Once the idx is matched the correct image is displayed. If no image is available for the idx will default to the image of the following idx number unless there is no image after that number.

functions that are created are also forEach as they will filter through all like class and perform the action. In the case of our two functions it removes the class of 'show' from the content and 'active' from the nav item.
