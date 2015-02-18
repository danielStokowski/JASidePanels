JASidePanels + status bar animation
===

If you don’t know what is JASidePanels - check [original github](https://github.com/gotosleep/JASidePanels)
Demo
---
![iPhone center](http://s13.postimg.org/4f237xtvb/JASide_Panel1.png)
![iPhone left](http://s13.postimg.org/4qjjkpabb/JASide_Panel2.png)


Usage
---
Usage is the same as in original JASidePanels. The only difference is that it uses extra category from [Frank](https://github.com/TestingWithFrank/Frank) (UIApplication+FrankAutomation) to get UIWindow that contains status bar


Requirements
---

JASidePanels requires iOS 5.0+ and Xcode 4.3+ The projects uses ARC, but it may be used with non-ARC projects by setting the: ` -fobjc-arc ` compiler flag on ` JASidePanelController.m `. You can set this flag under Target -> Build Phases -> Compile Sources

License
---

```

 Permission is hereby granted, free of charge, to any person obtaining a copy of
 this software and associated documentation files (the "Software"), to deal in
 the Software without restriction, including without limitation the rights to
 use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
 of the Software, and to permit persons to whom the Software is furnished to do
 so, subject to the following conditions:
 
 The above copyright notice and this permission notice shall be included in all
 copies or substantial portions of the Software.
 
 Consider contribution to any open-sourced project :)
 
 THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
 IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
 FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 SOFTWARE.
 
 ```

Credits
---
Links that helped:

* JASidePanels - [https://github.com/gotosleep/JASidePanels](https://github.com/devhttps://github.com/gotosleep/JASidePanels)
* Frank - [https://github.com/TestingWithFrank/Frank](https://github.com/mystcolor/Jhttps://github.com/TestingWithFrank/Frank) - array of all windows in application
