# shttp

semple http call

## To integrate Shttp into your Android project, follow these steps:

### Step 1: Add JitPack Repository

Add the JitPack repository to your project's root `settings.gradle` file:

```groovy
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        maven { url = uri("https://jitpack.io") }
    }
}
```

## Step 2: Add the Dependency

Add the Jummania-Slider dependency to your app module's `build.gradle` file:

 ```gradle
ddependencies {
	        implementation 'com.github.sarowarhosen03:shttpApi:1.3'
	}
```

## jitpack
[![](https://jitpack.io/v/sarowarhosen03/shttpApi.svg)](https://jitpack.io/#sarowarhosen03/shttpApi)
