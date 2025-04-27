##This repository contains all the samples files for Urovo Android Smart POS Payment Terminal;Handheld Data Terminal, including the revision history.
##Need more information about getting started with Urovo Android device? Check the [official docs][getting-started].

> 如何使用scannerapi依赖项目

>Add it in your root setting.gradle at the end of repositories:
~~~JAVA

dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
        repositories {
        	mavenCentral()
            maven { url 'https://jitpack.io' }
    }
}

~~~
> Add the dependency
~~~JAVA

dependencies {
    implementation 'com.github.urovosamples:scannerapi:5.2.6'
}
~~~
