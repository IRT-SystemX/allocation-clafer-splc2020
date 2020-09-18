# allocation-clafer-splc2020
SPLC2020 conference, Clafer modeling contents for the allocation case study

## SPLC 2020 - Clafer modeling content - Allocation case study

This repository contains the published domain case studies found in our submitted work to SPLC2020 (https://http://splc2020.net)
Using [Clafer](http://clafer.org), v0.4.3 (https://gsd.uwaterloo.ca/clafer-tools-binary-distributions.html), 
Developed within the [ISC2 Project] (https://www.irt-systemx.fr/en/projets/isc/).

Reference of the article: Towards Facilities for Modeling and Synthesis of Architectures for Resource Allocation Problem in Systems Engineering
DOI: https://doi.org/10.1145/3382025.3414963

The repository is structured as follows:
* root - final model (and branchings)
* xp1 - body related to modeling strategies to encoding the deployment problem in an heterogeneous context
* xp2 - body related to improving the resolution thanks to customized resolution strategy
* xp3 - body related to improving the resolution thanks to customized resolution strategy (domain constraints added)
* xp4 - body related to improving the constraints for resolution (redundancy constraints)

Some commands: 

.\clafer deplCasebA.cfr -m choco -m graph --validate --sr
java -jar .\chocosolver.jar --file deplCasebA.js --time --maxint 10000000

## License

These models are made available under the terms of the Eclipse Public License v2.0, which is available at: 
https://www.eclipse.org/legal/epl-v20.html

## Contributors

* [Stephen Creff] IRT SystemX
* [Jerome Le Noir] Thales Research and Technology
