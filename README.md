[ ![Download](https://api.bintray.com/packages/bastienpaulfr/maven/Treessence/images/download.svg) ](https://bintray.com/bastienpaulfr/maven/Treessence/_latestVersion)

# Treessence
Some trees for Timber lib

## Set up

**build.gradle**

```
repositories {
    jcenter()
    maven { url "https://dl.bintray.com/bastienpaulfr/maven" }
}

dependencies {
    //Treessence does not include Timber
    implementation 'com.jakewharton.timber:timber:4.6.0'
    implementation('fr.bipi.treessence:treessence:0.0.1') {
        exclude group: 'com.android.support'
    }
}
```

### Usage

  1. Checkout [Timber](https://github.com/JakeWharton/timber)
  2. Add any trees you like
