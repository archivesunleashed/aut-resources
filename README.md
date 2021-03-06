# Archives Unleashed Toolkit (AUT) Resources

This is the resource repository for the Archives Unleashed Toolkit (AUT), [which you can find here](https://github.com/archivesunleashed/aut). AUT is an open-source platform for analyzing web archives. Tight integration with Hadoop provides powerful tools for analytics and data processing via Apache Spark. Our full documentation can be found at <http://archivesunleashed.org/aut/>.

The Archives Unleashed Toolkit is part of the broader [Archives Unleashed project](http://archivesunleashed.org/).

## Getting Started

Follow the instructions on the [main AUT repository](https://github.com/archivesunleashed/aut), and consult the [detailed documentation available here](http://archivesunleashed.org/aut/).

This repository contains supporting resources that you need for some of the commands, such as:
- Named Entity Recognition;
- Sample WARC and ARC files for protoyping

## Contents

- `/ner/english.all.3class.distsim.crf.ser.gz`: This classifier is trained on English-language locations, organizations, and people. It is a central part of the [Spark: Named Entity Recognition](http://archivesunleashed.org/aut/#named-entity-recognition) recipie.
- Sample Data: In the `/sample-data/` directory, we have one ARC and one WARC file from the University of Toronto's Canadian Political Parties collection. They're indicative of the kind of data you'll find within the Internet Archive or Archive-It.

## Acknowledgments

This work is primarily supported by the [Andrew W. Mellon Foundation](https://uwaterloo.ca/arts/news/multidisciplinary-project-will-help-historians-unlock). Additional funding for the Toolkit has come from the U.S. National Science Foundation, Columbia University Library's Mellon-funded Web Archiving Incentive Award, the Natural Sciences and Engineering Research Council of Canada, the Social Sciences and Humanities Research Council of Canada, and the Ontario Ministry of Research and Innovation's Early Researcher Award program. Any opinions, findings, and conclusions or recommendations expressed are those of the researchers and do not necessarily reflect the views of the sponsors.