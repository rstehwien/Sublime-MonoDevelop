Sublime-MonoDevelop
===================

Sublime Configuration for MonoDevelop.  This package recognizes .sln and .csproj as being for MonoDevelop.  It then provides the ability to build the solution in your project folder.  The build can be kicked from a C# file in any subdirectory or from one of the MonoDevelop files.

Prerequisites
-------------
MonoDevelop's "mdtool" must be on your path; or you must edit the "cmd" in MonoDevelop.sublime-build

Installation
------------

* Not added to Package Control yet (beta)
* You need to manually install it using git
	* Go to your packages directory and type:
		* git clone git://github.com/rstehwien/Sublime-MonoDevelop.git MonoDevelop
* To update to the latest commit, use this command in the MonoDevelop directory:
	* git pull

Once installed you should be able to run the Sublime build on any C# or MonoDevelop solution file where you have a Sublime project saved at the root level of the solution.

License
-------

This plugin is using the zlib license

Copyright (c) 2012 Robert Stehwien

This software is provided 'as-is', without any express or implied
warranty. In no event will the authors be held liable for any damages
arising from the use of this software.

Permission is granted to anyone to use this software for any purpose,
including commercial applications, and to alter it and redistribute it
freely, subject to the following restrictions:

1. The origin of this software must not be misrepresented; you must not claim that you wrote the original software. If you use this software in a product, an acknowledgment in the product documentation would be appreciated but is not required.
2. Altered source versions must be plainly marked as such, and must not be misrepresented as being the original software.
3. This notice may not be removed or altered from any source distribution.