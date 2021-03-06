# Initial test cases 
 
## Purpose and format
 
 The idea here is to start identifying specific cases to use in testing and exploring performance.  
 
## Cases
 
 * Allometry of milk intake at peak lactation (article)
    * resource: PDF downloaded from [https://www.researchgate.net/publication/233851685_Allometry_of_milk_intake_at_peak_lactation](https://www.researchgate.net/publication/233851685_Allometry_of_milk_intake_at_peak_lactation) 
    * description: PDF article with text, figures, and table listing species used 
    * size: 42 species in analysis plus others listed in text
    * comment: this is a subtree from the Bininda-Emonds supertree of 4K mammals.  Arlin has a complete set of files for the expected output. 
    * contributor: Arlin Stoltzfus
    
 * Modeling body size evolution in Felidae under alternative phylogenetic
 hypotheses (article)
    * resource: [http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3032953/pdf/gmb-32-1-170.pdf](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3032953/pdf/gmb-32-1-170.pdf)
    * description: open-access PDF article with text, figugres, and table listing species of felids used in analysis
    * size: 35 species 
    * comment: nice to use because they do the same analysis with a subtree from the Bininda-Emonds supertree of 4K mammals, and with a felid-specific tree from Johnson, et al.  This allows us something to validate against.  Note also that this paper lists several other papers (mostly same authors) that use the Bininda-Emonds tree
    * contributor: Arlin Stoltzfus
 
 * Wikipedia:ants (web page)
    * resource:  [https://en.wikipedia.org/wiki/Ant](https://en.wikipedia.org/wiki/Ant)
    * description: the wikipedia “ants” page with various sections describing biology, distribution, etc. 
    * size: 140 species of ants are listed, according to a GNRD scraping
    * comment:  the page also lists some non-ant species like Ursus arctos (eats ants) and Vicia faba (attracts ants), so we might want to figure out how to screen those out.
    * contributor: Arlin Stoltzfus
    
 * Several large trees in NEXUS or Newick format (online repository)
    * resource: [https://github.com/phylotastic/phylotastic.github.io/tree/master/data](https://github.com/phylotastic/phylotastic.github.io/tree/master/data)
    * description: repository with large trees (from phylotastic hackathon) in text formats
    * size: smallest tree has 893 (Westneat), largest has >100K (Goloboff) 
    * comment: you can get direct URLs for these files (e.g.,  https://raw.githubusercontent.com/phylotastic/phylotastic.github.io/master/data/Bininda-emonds_2007_mammals.nex), but I tried this with GNRD and it didn't work 
    * contributor: Arlin Stoltzfus
 
 * Functional diversity responses to changing species richness in reef fish communities (article)
    * resource: [http://www.int-res.com/articles/suppl/m364p147_app.pdf](http://www.int-res.com/articles/suppl/m364p147_app.pdf)
    * description: appendix of Halpern, Benjamin S., and Sergio R. Floeter. "Functional diversity responses to changing species richness in reef fish communities." Marine Ecology Progress Series 364 (2008): 147-156.
    * size:  estimate 1620 species in column 1 of table A2
    * comment: 
    * contributor: Brian Sidlauskas
 
 * Endangered marine species under NOAA jurisdiction (web page)
    * resource: [http://www.nmfs.noaa.gov/pr/species/esa/listed.htm](http://www.nmfs.noaa.gov/pr/species/esa/listed.htm)
    * description: web page, html table with binomials or trinomials, no semantics
    * size: about 130 species names 
    * comment: includes common names; different sections of table for inverts, fish, reptiles, mammals 
    * contributor: Brian Sidlauskas
 
 * Oregon's native freshwater fish (web page)
    * resource: [http://www.dfw.state.or.us/fish/crp/freshwater.asp](http://www.dfw.state.or.us/fish/crp/freshwater.asp)
    * description: web page, html table with common names, no semantics
    * size: about 50 species designated 
    * comment:  common names will make this a challenge
    * contributor: Brian Sidlauskas
 
