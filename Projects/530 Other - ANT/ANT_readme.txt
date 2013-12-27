AIR for Android instructions

1. Configuration:
	- install ant on your computer:
	    http://ant.apache.org/
	- install ant plugin for FlashDevelop on your computer:
	    https://code.google.com/p/fd-ant-plugin/
	- edit 'bat\SetupANT.bat' for paths to ANT
		set ANT_DIR=<Full Path to ANT Folder including ANT folder name>
	- enable "ANT Plugin" in your project:
	    Change obj\antPluginData.txt put there full path to build.xml
		<Full path to Current Project>\<Package Directories>\build.xml

2. Build from FlashDevelop as usual (F8)

3. Run/debug the application on the desktop as usual (F5 or Ctrl+Enter)

P.S. Please update your template from https://github.com/vovchik33/FlashDevelop