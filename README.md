<!--
Copyright 2022 Adobe. All rights reserved.
This file is licensed to you under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License. You may obtain a copy
of the License at http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under
the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR REPRESENTATIONS
OF ANY KIND, either express or implied. See the License for the specific language
governing permissions and limitations under the License.
-->

# commerce-events-ext-tpl

App Builder Template for Commerce Event-Driven Extension

# Prerequisites
- `nodejs` (v14) and `npm` installed locally - https://nodejs.org/en/
- `aio` command line tool - https://github.com/adobe/aio-cli, https://developer.adobe.com/runtime/docs/guides/tools/cli_install/
- Project in Adobe developer console
- Credentials in the project from previous point
- I/O Management API

# Usage
1. `git clone <template-url>` & `npm install`
2. `aio app init <your-project-name> --template <relative-path-to-template-folder-from-project-root>`
    OR
   `aio app init <your-project-name> --template <absolute-path-to-template-folder>`
3. Check your `app.config.yaml` file to see if the actions and event codes are set up correctly.
4. `aio app deploy` & `aio app undeploy` will take care of the event registration/subscription if `aio-cli-plugin-extension` is installed.

# Contributing
Contributions are welcomed! Read the [Contributing Guide](CONTRIBUTING.md) for more information.


# Licensing

This project is licensed under the Apache V2 License. See [LICENSE](LICENSE) for more information.
