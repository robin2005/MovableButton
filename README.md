# MovableButton

![image](https://github.com/robin2005/MovableButton/blob/master/screenpot/screenpot_1.jpg)

## Installation

* Drag the @FBMovableButton/FBMovableButton@ folder into your project.  
* @#import "FBMovableButton.h"@

<pre>
 FBMovableButton *movableButton = [FBMovableButton buttonWithType:UIButtonTypeCustom];
 movableButton.frame = CGRectMake(100, 200, 74, 82);
 [movableButton addTarget:self action:@selector(shareAction:) forControlEvents:UIControlEventTouchUpInside];
 [movableButton setImage:[UIImage imageNamed:@"icon_share_safuli"] forState:UIControlStateNormal];
 [self.view addSubview:movableButton];
</pre>