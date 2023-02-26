# OpenXTalk Apple Imaging Library
![OXTAnimation](images/OXT_animated1.gif)

#### Extension Builder Library with bindings for using Apple's Core Image (Filters) and to do a few other things with NSImage protocols.

OXT Apple Imaging Lib is a library of handlers and foreign function bindings for using some of Apple's Core Image API, Image Filtering in particular, as  well as a few general use NSImage protocol capabilities such as format conversions (GIF to TIFF for example) and pulling in image data from Apple's NSNamedImages, which are macOS standard icons and graphical interface elements (including some undocumented ones). Obviously this library module will only be useful to xTalk scripts that are running on Apple platforms. I'm writing on and have only tested on macOS, and the lib may need modifications (UIImage instead of NSImage) for iOS usability. Core Image Filters have been part of macOS since OS X Tiger release (sometime around 2005).] and so it is a well tested and sturdy workhorse of an API.

In the future I may try to write another library to wrap the also well seasoned (20+ years of development) ImageMagick library, which is a cross-platform, free and open-source library that has all sorts of practical uses from research to production, and image filtering capabilities similar to these Core Image filters and includes its own image scripting language.
