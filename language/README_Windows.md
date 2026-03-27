![Ring](https://ring-lang.github.io/images/theringlogo.jpg)

# Ring Programming Language (MonoRing build)

## Building using Microsoft Windows 

### Get the source code

	git clone https://github.com/idrassi/MonoRing.git
	
### Build Ring (Compiler/VM)
	
	cd MonoRing\language\build
	buildvc.bat

### Build Ring2EXE 

	cd MonoRing\tools\ring2exe
	build.bat

### Build RingPM

	cd MonoRing\tools\ringpm
	build.bat

### To be able to call ring from any folder 
	
	cd MonoRing\bin
	install.bat
	
#### Add Ring/bin to System path

	Hit "windows key".
	Type "Edit the System environment variables"
	Select "Advanced" tab.
	Click on "Environment Variables..."
	Double click on "Path"
	Add at the end the new path separated by semicolon. 
		;C:\Ring\Bin
	
