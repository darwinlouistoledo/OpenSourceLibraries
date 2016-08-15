# Open Source Libraries
This contains a list of all the Open Source Library I'm using in Android App Development.


##The List

**[Android Support Library](https://developer.android.com/topic/libraries/support-library/index.html)**

The Android Support Library offers a number of features that are not built into the framework. These libraries offer backward-compatible versions of new features, provide useful UI elements that are not included in the framework, and provide a range of utilities that apps can draw on.

---

**[Glide](https://github.com/bumptech/glide)**

Glide is a fast and efficient open source media management and image loading framework for Android that wraps media decoding, memory and disk caching, and resource pooling into a simple and easy to use interface.

Glide supports fetching, decoding, and displaying video stills, images, and animated GIFs. Glide includes a flexible API that allows developers to plug in to almost any network stack. By default Glide uses a custom HttpUrlConnection based stack, but also includes utility libraries plug in to Google's Volley project or Square's OkHttp library instead.

Glide's primary focus is on making scrolling any kind of a list of images as smooth and fast as possible, but Glide is also effective for almost any case where you need to fetch, resize, and display a remote image.

---

**[ButterKnife](http://jakewharton.github.io/butterknife/)**

Field and method binding for Android views which uses annotation processing to generate boilerplate code for you.

Eliminate findViewById calls by using *@BindView* on fields.
Group multiple views in a list or array. Operate on all of them at once with actions, setters, or properties.
Eliminate anonymous inner-classes for listeners by annotating methods with *@OnClick* and others.
Eliminate resource lookups by using resource annotations on fields.

---

**[OkHttp](http://square.github.io/okhttp/)**

An HTTP & HTTP/2 client for Android and Java applications.

---

**[LeakCanary](https://github.com/square/leakcanary)**

A memory leak detection library for Android and Java.

---

**[Stetho](http://facebook.github.io/stetho/)**

Stetho is a sophisticated debug bridge for Android applications. When enabled, developers have access to the Chrome Developer Tools feature natively part of the Chrome desktop browser. Developers can also choose to enable the optional dumpapp tool which offers a powerful command-line interface to application internals.

---

**[Retrofit](http://square.github.io/retrofit/)**

Type-safe HTTP client for Android and Java by Square, Inc.

---

**[Ormlite-Android](https://github.com/j256/ormlite-android)**

Object Relational Mapping Lite (ORM Lite) provides some simple, lightweight functionality for persisting Java objects to SQL databases while avoiding the complexity and overhead of more standard ORM packages.

ORMLite Android functionality used in conjunction with ormlite-core http://ormlite.com/

---

**[Gson](https://github.com/google/gson)**

A Java serialization/deserialization library that can convert Java Objects into JSON and back.

---

**[Joda-Time](https://github.com/JodaOrg/joda-time)**

Joda-Time provides a quality replacement for the Java date and time classes. The design allows for multiple calendar systems, while still providing a simple API. The 'default' calendar is the ISO8601 standard which is used by XML. The Gregorian, Julian, Buddhist, Coptic, Ethiopic and Islamic systems are also included, and we welcome further additions. Supporting classes include time zone, duration, format and parsing.

---

**[Otto](http://square.github.io/otto/)**

Otto is an event bus designed to decouple different parts of your application while still allowing them to communicate efficiently.

Forked from Guava, Otto adds unique functionality to an already refined event bus as well as specializing it to the Android platform.

---

**[RxJava](https://github.com/ReactiveX/RxJava)**

RxJava – Reactive Extensions for the JVM – a library for composing asynchronous and event-based programs using observable sequences for the Java VM.

***Note: I'm still learning more about RxJava.***

---

**[RxAndroid](https://github.com/ReactiveX/RxAndroid)**

Android specific bindings for RxJava.

This module adds the minimum classes to RxJava that make writing reactive components in Android applications easy and hassle-free. More specifically, it provides a Scheduler that schedules on the main thread or any given Looper.

***Note: I'm still learning more about RxAndroid.***
