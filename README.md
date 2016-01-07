# Frame Animation Bug

When a sprite with frame-based animation is loaded into a scene the sprites are incorrectly positioned/sized.

![iPhone 6+](iphone.png)

* iPhone
* iOS 9.2.1
* sprite atlas

Note that this does not manifest on an iPad.

![iPad mini](ipad.png)

To me it looks like under some circumstances when the sprite sheet is loaded in the iPhone case, the texture rect information is being incorrectly applied as the individual sprite is being fetched from the sheet wrongly in the iphone case.