# draft metadata model for lists and trees

## introduction 

We are trying to develop a metadata model for phylotastic lists and trees.  The purpose for disseminating metadata is two-fold: 
* provide information on sources and methods useful to users for purposes of evaluation
* to provide credit and make resources discoverable by linking a tree to supporting phylogeny studies

To develop and implement this model we need

1. a description of the kinds of metadata required, e.g. MIAPA
1. a serialization format for metadata instances, e.g. json
1. a formal or informal language to capture the semantics of metadata

We need to think about metadata in 3 contexts 
* phylotastic service returns useful metadata 
* phylotastic client returns useful metadata, including workflow as appropriate
* phylotastic portal creates, updates, displays and exports metadata for lists and trees

A semantic scheme for tree metadata is potentially available via the MIAPA ontology.  See the MIAPA checklist 

 https://github.com/miapa/miapa/blob/master/checklist/MIAPA-checklist.md
 
and related resources. 

## process

repeat as needed
* revise model
* implement token examples 
* evaluate via feedback

## needed from OT

* induced subtree "supporting_studies" includes study but not tree within study.  
   * add trees to metadata

## criteria

1. covers all relevant workflow operations
   * calibration
   * name resolution 
   * image harvest 
   * and so on
1. compatible with relevant standards and best practices
   * MIAPA
   * CDAO
   * NeXML? 
1. has a sensible serialization 
   * json?  nexml? 

## metadata for lists 

* Title : brief title 
* Description : narrative description 
* Keywords : comma-separated list of keywords
* Author : list author 
* Creation date : date initially created
* Curator : list curator 
* Modified date : date of most recent update
* Source : URI or other source description 
* Focal group : focal clade or taxon where relevant 
* Comment :  anything else 

## metadata for trees

MC = MIAPA checklist 

* topology (MC)
   * semantic anchor
   * identifier
      * induced tree: synth tree ID? 
      * source tree: OT tree ID or other source ID (TreeBase)
* gene or species tree (MC)
   * this is a species tree
* It is a tree or a network? (MC)
   * fully connected directed graph with maximum order 1 for edges entering a node
* Is topology rooted or not? (MC)
   * rooted
* The type of consensus if this a consensus topology
   * not consensus.  
* OTUs (MC)
   * sciName, ottID 
   * optional: vernacularName, other IDs
* Branch lengths (MC)
   * options
      * none
      * provided by DateLife
      * provided by BOLD scaling
* Branch support (MC)
* Character matrix (MC)
   * induced tree: not applicable
* Alignment method (MC)
   * induced tree: not applicable
* Tree inference method (MC)
   * induced tree: narrative description of how tree is derived 
