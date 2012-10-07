# NXC Lib
A collection of useful functions and libraries written in [Not eXactly C](http://bricxcc.sourceforge.net/nxc).
Feel free to fork and submit pull requests. You will be recognized as the author of code which you contribute to or submit.

## Usage
You can use NXT Lib by downloading a zip of the master branch and then unzip it into a folder of your choice. To include a library in one of your NXC programs, add the following code close to the top of the program file:

	#include "C:/Path/to/NXC/Lib/CenterText.Lib.nxc"

Remember to replace `C:/Path/to/NXC/Lib/` with the directory NXC Lib was extracted to previously, and `CenterText.Lib.nxc` with the filename of your chosen library.

To simplify this process further, you can specify an include directory in [Bricx Command Center](http://bricxcc.sourceforge.net)'s settings, like so:

![](https://sourceforge.net/apps/phpbb/mindboards/download/file.php?id=430&t=1)

Now, you only have to include the library filename in the include statement:

	#include "CenterText.Lib.nxc"

If you need help, please [create an issue](https://github.com/bungeshea/nxc-lib/issues), or make a post in the [Mindboards forums](https://sourceforge.net/apps/phpbb/mindboards/viewtopic.php?f=4&t=1627t)

## Libraries

### NXC Lib
A collection of generic macros and functions to use in your code.
- **Author:** [Shea Bunge][bungeshea]
- **Use:**
     `#include "lib.nxc"`
	
### Center Text
Allows you to display text in the center of the NXT screen.
- **Author:** [Shea Bunge][bungeshea]
- **Use:**
     `#include "CenterText.Lib.nxc"`
	
### Choose Number
Prompts the user to enter a number using the NXT buttons
- **Author:** [Shea Bunge][bungeshea]       
- **Use:**
    `#include "ChooseNum.Lib.nxc"`
	
### Screen Print
A single function that can display text on every line of the NXT screen.
- **Author:** [Shea Bunge][bungeshea]    
- **Use:**
     `#include "ScreenPrint.Lib.nxc"`
	
[bungeshea]: http://robotics.bungeshea.com