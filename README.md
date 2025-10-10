# What does `adb lolcat` do?

These are the slides for the [talk at DroidKaigi 2019](https://youtu.be/WZhFPHj-twU?si=N-MNqfMzNRuIvhYg) on the internals of `adb` (discussed via the `adb lolcat` command).

This talk is a deep dive into the Android Debug Bridge (ADB), breaking down its fundamental components – the client, server, and daemon.
Learn how these pieces interact through transports and a surprisingly simple protocol, and discover the inner workings of commands 
like `adb logcat`, including host authentication and service execution. Perfect for a deeper understanding of the daily tools of 
Android development.

## Original Blurb
> If you've been an Android developer for any length of time, sooner or later you will have encountered adb -- the Android Debug Bridge.
> Part of the Android SDK, it is most commonly used to view the logs continuously being emitted within a device (via adb lolcat) or to
> run commands directly on device via a shell. But it is, as its name suggests and as you might already know, also a bridge to a
> variety of other functionality and information.

> Have you ever wondered how adb does its magic? Or what actually happens when you type in `adb shell`? In this session, we'll dive
> right into the deep end and take a peek under the hood to understand how every Android developer's favorite tool works.
