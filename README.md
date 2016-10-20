Taverna Tutorials
=================

Tutorials and training material for using the [Taverna workbench](http://www.taverna.org.uk/).

[![DOI](https://zenodo.org/badge/doi/10.5281/zenodo.11590.png)](http://dx.doi.org/10.5281/zenodo.11590)


This material is a suggestion for a 2 or 3-day course, targeting bioinformaticians training at MSc level, but can be adjusted for the audience and scientific domains. Tutorial slides are per topic (e.g. Nested workflows), and can be used individually, although many tutorials naturally build upon others.

It is assumed students have access to individual workstations or laptops, as most parts of the tutorials are lab exercises where students progress at their own pace, with help and guidance from tutors and each other.

Last updated for: BioExcel Workflow Training, 2016-10-20

## Overview

 * Getting started with Taverna Workbench
 * Finding services and building simple workflows
 * Sharing and reusing workflows from [myExperiment](http://www.myexperiment.org/)
 * Using different types of services in a workflow
   * REST, Beanshell, Spreadsheet, XPath, R, External Tools, user interactions
   * Nested workflows and Components
 * Advanced workflow features
  * List handling, Looping, Asynchronous services, Control links, Retries, Parallel invocations
 * Integrations
  * Taverna command line tool, Taverna Online, Running workflows in a Portal
 * Workflows in practice
  *  Biodiversity research example
  *  Build your own workflows
    

## Agenda and materials

See the [suggested agenda](AGENDA.md) for a listing of the material and how we suggest scheduling this over a 2- 3-day training workshop.


## License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Taverna Tutorials</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://www.mygrid.org.uk/" property="cc:attributionName" rel="cc:attributionURL">myGrid, University of Manchester</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/taverna/taverna-tutorials" rel="dct:source">https://github.com/taverna/taverna-tutorials</a>.

This essentially means you are free to download, redistribute, adapt and most importantly use this material for your own Taverna training, as long as you include the above notion and provide links to the modified source materials (e.g. your Github fork).


## Tutor checklist

* Can Taverna Workbench be installed to lab machine? 
  * Which platform? (32/64 bit)
  * Taverna can be installed without admin rights
    * hould students without admin rights install to C:\Users\Fred\Taverna  or X:\Taverna ?
  * If students are using laptops:
    * Power extension cables and pads - most laptops don't have 8 hour battery
    * WiFi access - tested with 20 concurrent users
    * Cabled network (Ethernet) as fallback?
  * Download speed of Taverna tested
    * Fall back to memory sticks?
  * If sysadmins are pre-installing Taverna
    * Double-check the *version* (e.g. 2.5.0) and *edition* (e.g. Bioinformatics)
      * Test the installation with the first two tutorials
    * Modify/skip Installation slide - avoid two installations!
    * Will the workstations go into "Install new software management" lock-down for the first 40 minutes of tutorial?
      * Pre-warm them the night before.
* Run through all tutorials, ideally together with someone who is new to Taverna
  *  Are services working as they should?
  *  What problems are you likely to run in to?
  *  Update slides as needed (Fork on Github)
  *  Any firewall issues from lab machines?
  *  Are workstation monitors big enough (or dual monitors) to have tutorial PDF open at the same time as Taverna?
    *  Or should the tutorials be printed?
      *  2x2 slides pr paper sheet.
*  Does lab room have a working projector for showing introduction/demo material?
  *  Check connectivity from presenter's machine
    *  Are you able to do the Day 3 demonstrations?
    * Or do you need a separate room for presenting? Rearrange schedule if needed.

