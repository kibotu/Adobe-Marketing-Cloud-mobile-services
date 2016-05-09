Adobe-Marketing-Cloud/mobile-services [![Build Status](https://travis-ci.org/kibotu/Adobe-Marketing-Cloud-mobile-services.svg?branch=master)](https://travis-ci.org/kibotu/Adobe-Marketing-Cloud-mobile-services) [![](https://jitpack.io/v/kibotu/Adobe-Marketing-Cloud-mobile-services.svg)](https://jitpack.io/#kibotu/Adobe-Marketing-Cloud-mobile-services)
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Workaround for having latest version of adobe adobeMobileLibrary.jar and adobeMobileScene7.jar instead of having to put them manually into repository.

Only downside is that it has a small overhead because we put two jars into a android library project. But it should be fairly small and as you can see it's empty.
 
    
### How to install

    ### How to install
    	
    	repositories {
    	    maven {
    	        url "https://jitpack.io"
    	    }
    	}
    		
    	dependencies {
                 compile 'com.github.kibotu:Adobe-Marketing-Cloud-mobile-services:-SNAPSHOT'
        }
        
### How to build

    gradle clone
    
    gradle copyTask
    
    gradle build