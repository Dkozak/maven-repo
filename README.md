How to use
========

Simply add the repository to your build.gradle file:

```groovy
repositories {
    maven {
        url 'https://github.com/Dkozak/maven-repo/raw/master/'
    }
    mavenCentral()
}
```

And you can use the artifacts like this:

```groovy
dependencies {
    compile "com.android.support:support-v4:21.0.0"
    compile "com.android.support:cardview-v7:21.0.0"
    compile "com.android.support:recyclerview-v7:21.0.0"
    compile "com.android.support:appcompat-v7:21.0.0"
    compile "org.apache.commons:commons-io:1.3.2"
    compile "com.j256.ormlite:ormlite-android:4.45"
    compile "com.google.code.gson:gson:2.2.4"
    compile fileTree(dir: 'libs', include: '*.jar',)
    compile "com.android:volley:1.0"
    compile "com.actionbarsherlock:viewpagerindicator:2.4.1"
}
```


License:
--------
The licenses are provided by the individual libary owner. This "maven-repo" utilizes these libaries and
won´t provide any support, responsibility or licenses itself.
