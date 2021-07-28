# MyLibraryGithub
My library github
>Step 1. Add the JitPack repository to your build file
``` gradle
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  ```
  >Step 2. Add the dependency
  ```gradle
  dependencies {
	       implementation 'com.github.reimboyevQuvonchbek:MyLibraryGithub:1.0.0'
	}
  ```
