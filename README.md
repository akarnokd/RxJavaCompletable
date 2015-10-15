RxJavaCompletable
==============

A Completable class that allows valueless event composition (aka continuation style) within RxJava.

Import
------

Gradle:

```
compile 'com.github.akarnokd:rxjava-completable:1.0.0'
```

Gradle with ignoring the referenced RxJava version

```
compile ('com.github.akarnokd:rxjava-completable:1.0.0') {
    exclude module: 'rxjava'
}
```

Ivy:

```xml
<dependency org="com.github.akarnokd" name="ixjava" rev='1.0.0'/>
```

Ivy with ignoring the referenced RxJava version:

```xml
<dependency org="com.github.akarnokd" name="ixjava" rev='1.0.0'>
    <exclude name="rxjava"/>
</dependency>
```

Releases
--------

<a href='https://travis-ci.org/akarnokd/RxJavaCompletable/builds'><img src='https://travis-ci.org/akarnokd/RxJavaCompletable.svg?branch=master'></a>