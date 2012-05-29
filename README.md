# Hackernews API

Restful news.ycombinator.com API written in Coffeescript for node.js.

## Required Files
Modules: *express* & *jsdom*, Files: *jquery 1.6+*

## Developers
We have included a makefile with convenience methods for working with the Bootstrap library.

+ **dependencies** 
Our script depends on jsdom and express. To install, just run the following commands in npm:
```
$ npm install express
```

```
$ npm install jsdom
```

## Examples
get frontpage: http://localhost:1337/news

get next page: http://localhost:1337/news/pageid

get user profile: http://localhost:1337/user/username

get user submissions: http://localhost:1337/user/username/submissions

## Author(s)

**Eric Lewis**

+ http://twitter.com/ericlewis
+ http://github.com/ericlewis

## Copyright and license
Copyright 2012 boxyco, LLC.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this work except in compliance with the License. You may obtain a copy of the License in the LICENSE file, or at:

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.