# common-code
Thinnk about trying to write code that will compile on Objective-C and also on JAVA.

To create a color;

Objective-C

 topColor = [UIColor colorWithRed:94/255.0 green:234/255.0 blue:_piBlue/207.0 alpha:1.0];


Android:

topColor = Color.argb(1.0, 94, 234, 207);

My way:  

        piRed = 94;
        piGreen = 234;
        piBlue = 207;
        topColor = makeColor();
        
  OR FOR Objective-C
  
        piRed = 94;
        piGreen = 234;
        piBlue = 207;
        topColor = [self makeColor];  // using a small code conversion program I wrote.
        


