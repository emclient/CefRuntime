# CefRuntime

Build scripts for automation of CEF builds on our self-hosted build runners. The GitHub Action flow has to be invoked manually and it produces a release in this repository with all the artifacts for our supported platforms (currently Windows x86 and x64). The Cef.Runtime NuGet package on our GitHub Packages feed is also created, which is consumed by [CefGlue2](https://github.com/emclient/CefGlue2).
