# Example consuming WMTS
A short example of how to consume Lantmäteriets (Swedish National Land Survey) open geodata from a web map tile service (WMTS).
## Running the Example
To get map data from the wmts you need to get an API key and insert it into the code:

* First you need to create a [user account](https://opendata.lantmateriet.se/#register) (web page in swedish only) to acquire your API-key.

* Then you need to update the apiKey constant in index.html with your API key:
```
//TODO Insert your API key here
const apiKey = 'My key';
```
* Now you can open index.html in a web browser and hopefully see a map of Sweden

## License
Copyright 2016 Lantmäteriet

Licensed under the Apache License, Version 2.0 (the License);
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an AS IS BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
