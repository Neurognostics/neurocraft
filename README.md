# Neurocraft || The Microscale Neuro-engineering Platform

[![Downloads](https://img.shields.io/github/downloads/Neurocraft/Neurocraft/total)](https://github.com/Neurocraft/neurocraft/releases)

[Neurocraft](http://neurocraft.co.uk) is a platform featuring peer-reviewed methodology for feature extraction and modelling of electrophysiological data. It runs on MATLAB and its beta release will also be available on Windows and Mac OS X as stand-alone applications.

- **SOTA** Powered by a wavelet coherence engine, Neurocraft is able to push the envelope with ultra-high temporal and frequency resolution of neuronal dynamics. All actions (e.g. layout, filter, drag) run in real-time.
- **Simple** Easy to install and [get started](https://www.neurocraft.co.uk/#get_started). An UI that is centered around the visualization. Like Photoshop™ for brain networks.
- **Comprehensive**  A wide variety of analytics and modelling offers thorough data exploration

  :point_right:  network evolution maps around event of interest\
  :point_right:  influence analysis of nodes/areas\
  :point_right:  propagation model for annotated brain activity


[Download Neurocraft](https://www.neurocraft.co.uk/#download) for Mac OS X and MATLAB and consult the [release notes](https://github.com/Neurognostics/neurocraft/wiki/Releases). Example datasets can be found on our [wiki](https://github.com/Neurognostics/neurocraft/wiki/Datasets).

![image](https://user-images.githubusercontent.com/429321/136833826-d945a76b-1829-4e20-b93e-7b2b9a859f3e.pngf)

## Install and use neurocraft

Download and [Install](https://neurocraft.github.io/users/install/) neurocraft on your computer. 

Get started with the [Quick Start](https://github.com/Neurognostics/neurocraft/wiki/quick-start/) and follow the [Tutorials](https://github.com/Neurognostics/neurocraft/wiki/Tutorials/). Load a sample [dataset](https://github.com/Neurognostics/neurocraft/wiki/Datasets) and start to play with the data.

If you run into any trouble or have questions consult our [forum](https://neurocraft.talkyard.net/).

## Latest releases

### Stable

- Latest stable release on [neurocraft.co.uk](https://www.neurocraft.co.uk/#download).

### Nightly builds

Current version is 0.9.3-SNAPSHOT

- [gephi-0.9.3-SNAPSHOT-windows.exe](https://oss.sonatype.org/service/local/artifact/maven/content?r=snapshots&g=org.gephi&a=gephi&v=0.9.3-SNAPSHOT&c=windows&p=exe) (Windows)

- [gephi-0.9.3-SNAPSHOT-macos.dmg](https://oss.sonatype.org/service/local/artifact/maven/content?r=snapshots&g=org.gephi&a=gephi&v=0.9.3-SNAPSHOT&c=macos&p=dmg) (Mac OS X)

- [gephi-0.9.3-SNAPSHOT-linux.tar.gz](https://oss.sonatype.org/service/local/artifact/maven/content?r=snapshots&g=org.gephi&a=gephi&v=0.9.3-SNAPSHOT&c=linux&p=tar.gz) (Linux)

- [gephi-0.9.3-SNAPSHOT-sources.tar.gz](https://oss.sonatype.org/service/local/artifact/maven/content?r=snapshots&g=org.gephi&a=gephi&v=0.9.3-SNAPSHOT&c=sources&p=tar.gz) (Sources)

## Developer Introduction

Neurocraft is developed in MATLAB and uses OpenGL for its visualization engine. Neorocraft follows a loosely-coupled, modular architecture philosophy. Neurocraft is split into modules. Plugins can reuse existing APIs, create new services and even replace a default implementation with a new one.

### Requirements

- Java JDK 8. Note: Neurocraft does not currently work with JDK newer than 8. Work needs to be done yet in order to support newer java versions.

- [Apache Maven](http://maven.apache.org/) version 3.2.2 or later

## License

Neurocraft main source code is distributed under the dual license [CDDL 1.0](http://www.opensource.org/licenses/CDDL-1.0) and [GNU General Public License v3](http://www.gnu.org/licenses/gpl.html). Read the [Legal FAQs](http://neurocraft.github.io/legal/faq/)  to learn more.
	
Copyright 2021 Neurocraft Consortium. All rights reserved.


