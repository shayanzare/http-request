# Http_request

This is a simple header for easy to send http request in Qt!

## Use
Add header to your project and add this code in your .pro file :

```cpp
QT += network
```

## Get Request

```cpp
Get("http://google.com");
```

## Post Request

```cpp
Post("http://google.com/", "header1=one&header2=two");
```