# New Project Template

This repository contains a template you can use to see a repository for a
new open source project.

See go/releasing (available externally at
https://opensource.google.com/docs/releasing/) for more information about
releasing a new Google open source project.

This template uses the Apache license, as is Google's default.  See the
documentation for instructions on using alternate license.

## How to use this template

1. Check it out from GitHub.
    * There is no reason to fork it.
1. Create a new local repository and copy the files from this repo into it.
1. Develop your new project!

``` shell
git clone https://github.com/google/new-project
mkdir my-new-thing
cd my-new-thing
git init
cp ../new-project/* .
git add *
git commit -a -m 'Boilerplate for new Google open source project'
```

## Source Code Headers

Every file containing source code must include copyright and license
information. This includes any JS/CSS files that you might be serving out to
browsers. (This is to help well-intentioned people avoid accidental copying that
doesn't comply with the license.)

Apache header:

    Copyright 2017 Google Inc.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        https://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
