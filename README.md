# scrappy
**S**ony **C**amera **R**emote **AP**i **PY**thon, a python wrapper for communicating with Sony cameras.

The [Sony API](https://developer.sony.com/develop/cameras/) for cameras uses http and json for communication. *scrappy* provides a python wrapper around the Sony API, so Sony cameras can be seamlessly integrated into Python projects.

# Comparison of camera APIs

For hacking and cobbling together fun, DIY Python projects, Sony's API is awesome due to its relative simplicity and embrace of common protocols made ubiquitous by the internet. However, this requires having Sony hardware. Other leading camera manufacturers provide SDKs for their cameras, but the Python support is varied and often using the SDK directly requires signing up for their respective developers programs. The table below summarizes some of the popular camera makers and their Python support. For what it is worth, Sony seems to have the lowest barrier to entry.

| Camera Manufacturer | Language or Protocol | Python Projects | Comments |
| --- | --- | --- | --- |
| Canon | DLL (Win) and DYLIB (Mac) | [piggyphoto](https://github.com/alexdu/piggyphoto) | Canon has support from external firmware projects like [Magic Lantern](https://www.magiclantern.fm/) or [CHDK](http://chdk.wikia.com/wiki/CHDK) |
| [Nikon](https://sdk.nikonimaging.com/apply/) | C and C++, DLL (Win) and DYLIB (Mac) |  | Nikon does not appear to have a lot of Python support. |
| [Sony](https://developer.sony.com/develop/cameras/) | HTTP and JSON-RPC | [here](https://github.com/karhohs/scrappy) and [pysony](https://github.com/Bloodevil/sony_camera_api)| The Sony API uses protocols that work on all platforms making it the most flexible. |
