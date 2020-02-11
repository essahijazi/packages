# packages

benefits of packages

packages provide organization
packages follow a standard naming convention
affect the source code file structure

********************************

package naming conventions
- all lowercase
- use reversede domain name to assure global uniqeness
e.g. package com.pluralsight;
- add further qualifiers to assure uniqueness within company
e.g. package com.pluralsight.myproject;
package com.pluralsight.accounting.myproject;
package com.pluralsight.coursemanagement.myproject;

once we put classes inside these packages, the class is not just referred to by its name but package com.pluralsight.Main

********************************
package name and source file structure

- java requires no correlation between package names and source code file structure
- most IDE's require a subfolder for each part of the package name

e.g. 

main class not in package
src -> Main.java

main class in package named package com.pluralsight.example
src -> com > pluralsig ht -> example -> Main.java
