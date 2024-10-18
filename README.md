# match_complete.xml script generator

The original.xml file, is a excerpt from the match_complete.xml file from release 102.0, containing 492 proteins and slightly modified to avoid having the non-protein objects found at the beginning of it.

Execute all the cells in the notebook and you'll end up with three more additional files:
- processed.xml: an even more edited version of original.xml, obtained by removing 'ipr' objects and the representative attribute from locations;
- output.xml: the generated xml file;
- differences.txt: containing a list of the differences between "processed.xml" and "output.xml". Right now, excluding the representative attribute and ipr entries, the only differences are the model_ac(s).

