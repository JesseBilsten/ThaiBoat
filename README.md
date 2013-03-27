# Thai Boat SLO's website

Thai Boat SLO's website is affectionately maintained by [Jesse Bilsten](http://twitter.com/lostangel).

## Contributing

Please submit all pull requests against *-wip branches. If your pull
request contains JavaScript patches or features, you must include
relevant unit tests. All HTML and CSS should conform to the Bootstrap [Code Guide](http://github.com/mdo/code-guide), maintained by [Mark Otto](http://github.com/mdo).

## Dependencies
This code base now uses [Yeoman](http://yeoman.io/) for builds, deploys
and code management in general.  This includes the following:

+ Grunt
+ Node
+ Bower
+ Ruby (for Compass)

Yeoman is still in beta so there may be some issues, but since this
isn't a mission critical project, it shouldn't be an issue.

## Workflow

+ git branch <whatever's clever>
+ mvim . (or your text editing equivalent)
+ Add/edit/remove files
+ git add .
+ git commit -m "your message here."
+ git checkout master
+ git merge <whatever's clever>
+ git push origin master

I deploy the '/dist' directory to the live site, so make sure you've
properly compiled the site before checking in code.

Thanks!

## Authors

**Jesse Bilsten**

+ http://twitter.com/lostangel
+ http://github.com/jessebilsten

**Tony Gines**

+ http://twitter.com/tgines
+ http://github.com/tgines

## Copyright and license

Copyright 2013 Jesse Bilsten

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this work except in compliance with the License.
You may obtain a copy of the License in the LICENSE file, or at:

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
