# Week 9 Project: Honeypot

Time spent: **11** hours spent in total

## Deployed Honeypot(s) 

I deployed three honeypots using the [Modern Honey Network](https://github.com/threatstream/mhn#honeypot) as following. Also deployed f1-micro instances on Google Compute Engine running Ubuntu 14.04 Trusty.

   - [ ] [Dionaea](https://github.com/rep/dionaea) (honeypot-1)
   - [ ] [Snort](https://github.com/threatstream/mhn/wiki/Snort-Sensor) (honeypot-2)
   - [ ] [p0f](https://github.com/threatstream/mhn/wiki/p0f-Sensor) (honeypot-3)

## Encountered Issues

It took me a while to troubleshoot issues regarding connecting to MHN Server.

## Summary of Data

I kept the deployed honeypots open for about 6 hours. Below is the summary of the data collected:

  - [ ] There were **1100** total attacks across all three honeypots (dionaea: 544, snort: 200, p0f: 356).
  
  - [ ] GIF Walkthrough:  <img src="https://media.giphy.com/media/xAvskvijkmNXOQJXih/giphy.gif" width="800">

 I uploaded the json export of the data I collected in this repository.

## Unresolved questions raised by the data collected
N/A














## License

    Copyright [2018] [Mahshid Mehrayin]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
