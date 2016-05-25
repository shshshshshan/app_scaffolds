*Use of this software is subject to important terms and conditions as set forth in the License file*

# Iframe App Template

## Description
This repo contains a template to help developers build Iframe apps for Zendesk products.

## Owners
The project is maintained by the Quokka / Vegemite team, ping us with [@zendesk/vegemite on GitHub](https://github.com/orgs/zendesk/teams/vegemite).

## Getting Started

### Setup
1. Clone or fork this repo
2. Run `npm install`

### Running locally
To run your app locally in Zendesk, you need the [Zendesk Apps Tools (ZAT)](https://github.com/zendesk/zendesk_apps_tools).

After installing ZAT, you typically need two separate command-line interface tabs to develop an app locally. Use the first tab to run the `zat server --path=./dist` command to start the local web server. Use the second tab to run the `webpack --watch` command to build the project whenever you change the files.

## Testing
WIP

## Contribute
* Put up a PR into the master branch.
* CC and get a +1 from @zendesk/vegemite.

## Bugs
Submit Issues via [GitHub](https://github.com/zendesk/iframe_app_template/issues/new) or email vegemite@zendesk.com.

## Useful Links
Links to maintaining team, confluence pages, Datadog dashboard, Kibana logs, etc
- https://developer.zendesk.com/
- https://github.com/zendesk/zendesk_apps_tools
- https://webpack.github.io

## Copyright and license
Copyright 2016 Zendesk

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License.

You may obtain a copy of the License at
http://www.apache.org/licenses/LICENSE-2.0
Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.