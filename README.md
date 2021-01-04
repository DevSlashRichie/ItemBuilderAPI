# ItemBuilderAPI
API to build an ItemStack on CraftBukkit or Spigot.

  <a href="https://github.com/RicardormDev/ItemBuilderAPI/releases" target="_blank">
    <img alt="downloads" src="https://img.shields.io/github/v/release/RicardormDev/ItemBuilderAPI?color=56bcd3" />
  </a>
  <a href="https://github.com/BiscuitDevelopment/SkyblockAddons/releases" target="_blank">
    <img alt="downloads" src="https://img.shields.io/github/downloads/RicardormDev/ItemBuilderAPI/total?color=56bcd3" />
  </a>
  <a href="https://github.com/RicardormDev/ItemBuilderAPI/blob/master/LICENSE" target="_blank">
    <img alt="license" src="https://img.shields.io/github/license/RicardormDev/ItemBuilderAPI?color=56bcd3" />
  </a>
  
  
## Features
* Easier way to build ItemStacks
* Forget about the messy code.
* Manipulate data easy.
* Personalize items with placeholders.
* Build from configuration. Forget about parsers.
  
## Usage
To use the ItemBuilder API:
- Build with Maven or Gradle.
- Add the following code to build.gradle or pom.xml
  
Build it into your project.
### Gradle
```gradle
repositories {
    maven { url 'https://jitpack.io' }
}

dependencies {
    compile 'com.github.RicardormDev:ItemBuilderAPI:1.0'
}
```

### Maven
```xml
	<repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>

	<dependency>
	    <groupId>com.github.RicardormDev</groupId>
	    <artifactId>ItemBuilderAPI</artifactId>
	    <version>Tag</version>
	</dependency>
```

## TODO
* Add some Javadocs
* Serialize Items
* Upload version for newer Minecraft versions.
* Add ModelData supporrt.
