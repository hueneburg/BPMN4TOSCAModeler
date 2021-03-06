# BPMN4TOSCA 2.0 Modeler

This project is an implementation of a BPMN4TOSCA plan modeler for creating and maintaining [TOSCA] compatible management plans.

It is based on the thesis [Ein Modellierungswerkzeug für BPMN4TOSCA] by Thomas Michelbach.

## Installation

A current pre-build version can be found in the dist folder!

1. Install Grunt CLI via `npm install -g grunt-cli`
2. Fetch dependencies using `npm install`
3. Build using `grunt` / `grunt watch`

## Run

Open index.html from dist folder with correct HTTP GET params:

repositoryURL (e.g. http://dev.winery.opentosca.org/winery/)
namespace (e.g. http://www.example.org/ServiceTemplates)
id (e.g. PlanDemonstration)
plan (e.g. Test)

## More Information on Winery

https://projects.eclipse.org/projects/soa.winery

## License
Copyright (c) 2015 Thomas Michelbach.
Copyright (c) 2015 University of Stuttgart.

All rights reserved.
This program and the accompanying materials are made available under the terms of the [Eclipse Public License v1.0] and the [Apache License v2.0] which both accompany this distribution,
and are available at http://www.eclipse.org/legal/epl-v10.html and http://www.apache.org/licenses/LICENSE-2.0.

## Literature

### About TOSCA
* Binz, T., Breiter, G., Leymann, F., Spatzier, T.: Portable Cloud Services Using TOSCA. IEEE Internet Computing 16(03), 80--85 (May 2012). [DOI:10.1109/MIC.2012.43]
* Topology and Orchestration Specification for Cloud Applications Version 1.0. 25 November 2013. OASIS Standard. http://docs.oasis-open.org/tosca/TOSCA/v1.0/os/TOSCA-v1.0-os.html
* OASIS: Topology and Orchestration Specification for Cloud Applications (TOSCA) Primer Version 1.0 (2013)

See http://www.opentosca.org/#publications for a list of publications in the OpenTOSCA ecosystem.

 [Apache License v2.0]: http://www.apache.org/licenses/LICENSE-2.0.html
 [DOI:10.1109/MIC.2012.43]: http://dx.doi.org/10.1109/MIC.2012.43
 [Eclipse Public License v1.0]: http://www.eclipse.org/legal/epl-v10.html
 [Ein Modellierungswerkzeug für BPMN4TOSCA]: http://elib.uni-stuttgart.de/opus/volltexte/2015/9943/
 [TOSCA]: https://www.oasis-open.org/committees/tosca/
