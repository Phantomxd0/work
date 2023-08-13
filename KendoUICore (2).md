<h1 id="KUC"><a href="KUC" style="text-decoration: none; color:black" > Kendo UI Core </a> </h1>
<br>
<h2 id="AKUC"><a href="AKUC" style="text-decoration: none; color:black" >About Kendo UI Core </a> </h2>
Kendo UI is everything you need to build sites and apps with HTML5 & JavaScript. Kendo UI Core is the free and open-source version of Kendo UI that provides access to the web's best UI widgets and key framework features, essential for developing great experiences for the web and mobile.
<br>
<h2 id="FOK"><a href="FOK" style="text-decoration: none; color:black" >Features of Kendo UI Core </a> </h2>
Kendo UI Core is a free and open-source subset of Kendo UI. The following table details the widgets and features available in Kendo UI Core, as well as the additional features available via a commercial Kendo UI license.
<br>
<h2 id="CAR"><a href="CAR" style="text-decoration: none; color:black" >Compatibility and Requirements</a> </h2>
Kendo UI Core depends on the following libraries:
<br>

* [jQuery](http://www.jquery.com/) v1.9.1+

Kendo UI Core has not been tested against any other versions of these libraries. You may find that versions other than these are compatible with Kendo UI Core. However, we make no claims to support those versions, and will not troubleshoot issues that arise when using those versions.
<br>
<h2 id="BKUC"><a href="BKUC" style="text-decoration: none; color:black" >Building Kendo UI Core</a> </h2>
<br>

There are two ways to get the source code for Kendo UI Core. You can either download a pre-built zip from [telerik.com](https://www.telerik.com/kendo-ui/open-source-core) , or build the source yourself using Gulp. The latter approach includes a option for building a distribution of Kendo UI Core that includes only the widgets and framework features required by your app.
<br>
<h3 id="ID"><a href="ID" style="text-decoration: none; color:black" >Installing Dependencies</a> </h3> 

<br>
In order to build Kendo UI Core, you need to have **Node.js 14.x** and **git 2.x.**

For Windows you have to download and install [Git for Windows](https://git-for-windows.github.io/) and [Node.js](http://nodejs.org/download/) and [Visual C++ Build Tools](http://landinghub.visualstudio.com/visual-cpp-build-tools).

Mac OS users should install [Homebrew](http://mxcl.github.com/homebrew/). Once Homebrew is installed, run ```brew install git``` to install git, and ```brew install node@14``` to install Node.js.

Linux users can use the [distributions provided by NodeSource](https://github.com/nodesource/distributions) or their package managers to install ```git``` and ```nodejs```
<br>
<h3 id="HTB"><a href="HTB" style="text-decoration: none; color:black" >How to build Kendo UI Core
</a> </h3>
<br>
Clone a copy of the repository by running

 ```
 git clone https://github.com/telerik/kendo-ui-core.git git clone https://github.com/telerik/kendo-ui-core.git
```
Enter the repository directory
```
cd kendo-ui-core
```
Initialize the submodule repository
``` 
git submodule update --init
```
Run the build script:
```
npm run build
```
The minified version of the scripts and styles of Kendo UI Core will be put in the ```dist/``` subdirectory.

There are several other tasks available:
```
npx gulp --tasks
```
<h3 id="BOWY"><a href="BOWY" style="text-decoration: none; color:black" >Building only what you need
</a> </h3>
<br>

The npm script ```npm run scripts:modules``` will create two folders (```cjs``` and ```esm```) in the dist folder, which includes the bundled modules.
<h3 id="dev"><a href="dev" style="text-decoration: none; color:black" >Development
</a> </h3>
<br>

* Run the dev script in order to compile both modules and js files in ```dist/dev``` and ```dist/mjs``` folder

  ```npm run scripts:dev``` or ```npm run scripts:dev -- -w```

* Run the tests by running ```npx gulp tests```

<h2 id="sca"><a href="sca" style="text-decoration: none; color:black" >Source Code and Downloads
</a> </h2>
<br>

If you want to skip building Kendo UI Core yourself, head on over to [Telerik.com](http://www.telerik.com/kendo-ui/open-source-core) to grab the full source.

<h2 id="uku"><a href="uku" style="text-decoration: none; color:black" >Using Kendo UI Core via the Kendo Static CDN
</a> </h2>
<br>

You can also easily include Kendo UI Core in your site or application by using the Kendo CDN:
```
<link href="http://kendo.cdn.telerik.com/2014.2.716/styles/kendo.common.min.css" rel="stylesheet" />
<link href="http://kendo.cdn.telerik.com/2014.2.716/styles/kendo.default.min.css" rel="stylesheet" />
<script src="http://kendo.cdn.telerik.com/2014.2.716/js/jquery.min.js"></script>
<script src="http://kendo.cdn.telerik.com/2014.2.716/js/kendo.ui.core.min.js"></script><link href="http://kendo.cdn.telerik.com/2014.2.716/styles/kendo.common.min.css" rel="stylesheet" />
<link href="http://kendo.cdn.telerik.com/2014.2.716/styles/kendo.default.min.css" rel="stylesheet" />
<script src="http://kendo.cdn.telerik.com/2014.2.716/js/jquery.min.js"></script>
<script src="http://kendo.cdn.telerik.com/2014.2.716/js/kendo.ui.core.min.js"></script>
```
The main advantage of the CDN approach is that your users may be able to leverage a primed cache version of Kendo UI Core if they've visited other sites using the framework.
<h2 id="dok"><a href="dok" style="text-decoration: none; color:black" >Documentation
</a> </h2>
<br>

For complete Kendo UI Documentation, including Kendo UI Core, please visit [https://docs.telerik.com/kendo-ui](https://docs.telerik.com/kendo-ui).

<h2 id="htc"><a href="htc" style="text-decoration: none; color:black" >How to Contribute
</a> </h2>
<br>

Kendo UI Core is free and open-source. We encourage and support an active, healthy community that accepts contributions from the public. We'd like you to be a part of that community.

Before contributing to Kendo UI Core, please:

1. Read and sign the [Kendo UI Core Contribution License Agreement](https://www.telerik.com/kendo-ui/cla), to confirm you've read and acknowledged the legal aspects of your contributions, and
2. Read our [contribution guide](https://github.com/telerik/kendo-ui-core/blob/master/CONTRIBUTING.md), which houses all of the necessary info to:
* submit bugs,
* request new features, and
* walk you through the entire process of preparing your code for a Pull Request.
<h2 id="htc"><a href="htc" style="text-decoration: none; color:black" >Getting Help
</a> </h2>
<br>

* Use the [issues list](https://github.com/telerik/kendo-ui-core/issues) of this repo for bug reports, related both to Kendo UI Core and Kendo UI Professional

* Get help on [Stack Overflow](http://stackoverflow.com/questions/tagged/kendo-ui) or the [Kendo UI Premium Forums](https://www.telerik.com/forums/kendo-ui-framework)

* File feature requests on [User Voice](https://feedback.telerik.com/kendo-jquery-ui)
As a fully-open source project, Kendo UI Core is a primarily community-supported project, As such, you are encouraged to use forums like Stack Overflow to post questions, and the issues list of this repo to report bugs.

The Kendo UI team does not provide formal support for Kendo UI Core, except to those customers who have purchased a [commercial license for Kendo UI](https://www.telerik.com/kendo-ui) (Professional, UI for MVC, etc.) or a support-only package from Telerik.com. Please do not create support requests for this project in the issues list for this repo, as these will be immediately closed. You'll be directed to post your question on a community forum.
<h2 id="rn"><a href="rn" style="text-decoration: none; color:black" >Release Notes
</a> </h2>
<br>

For change logs and release notes, see the [online release notes at Telerik.com](https://www.telerik.com/support/whats-new/kendo-ui/release-history).
<h2 id="li"><a href="li" style="text-decoration: none; color:black" >License Information
</a> </h2>
<br>

This project has been released under the [Apache License, version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html), the text of which is included below. This license applies ONLY to the source of this repository and does not extend to any other Kendo UI distribution or variant, or any other 3rd party libraries used in a repository. For licensing information about Kendo UI, see the [License Agreements page](https://www.telerik.com/purchase/license-agreement/kendo-ui) at [Telerik.com](https://www.telerik.com/).
>Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

>[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

>Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

*Copyright © 2023 Progress Software Corporation and/or its subsidiaries or affiliates. All Rights Reserved.*

*Progress, Telerik, and certain product names used herein are trademarks or registered trademarks of Progress Software Corporation and/or one of its subsidiaries or affiliates in the U.S. and/or other countries.*








