# ecqm_data_elements

This GitHub repository can be used with the [SHR Command-Line Interface](https://github.com/standardhealth/shr-cli) a Node.js command-line interface for parsing SHR text definitions and exporting them as FHIR profiles, CIMCORE JSON serialized files, JSON schema, ES6 classes, or a JSON document (for website generation).

# Exporting ECQM Data Elements

After setting up SHR Command-Line Interface, run the shr-cli tool using the following commands:

```
cd ~/cimpl/shr-cli
node . ../ecqm_data_elements/cimpl -o ../ecqm_data_elements/out
```

# License

Copyright 2018 The MITRE Corporation

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
