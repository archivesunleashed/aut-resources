# Archives Unleashed Toolkit (AUT) Resources

This is the resource repository for the Archives Unleashed Toolkit (AUT), [which you can find here](https://github.com/archivesunleashed/aut). AUT is an open-source platform for analyzing web archives. Tight integration with Hadoop provides powerful tools for analytics and data processing via Apache Spark. Our full documentation can be found at <http://docs.archivesunleashed.io/>.

## Getting Started

Follow the instructions on the [main AUT repository](https://github.com/archivesunleashed/aut), and consult the [detailed documentation available here](http://docs.archivesunleashed.io/).

This repository contains supporting resources that you need for some of the commands, such as:
- Named Entity Recognition;
- Sample WARC and ARC files for protoyping

## Contents

- `/ner/english.all.3class.distsim.crf.ser.gz`: This classifier is trained on English-language locations, organizations, and people. It is a central part of the [Spark: Named Entity Recognition](http://docs.archivesunleashed.io/Spark-Named-Entity-Recognition/) recipie.
- Sample Data: In the `/sample-data/` directory, we have one ARC and one WARC file from the University of Toronto's Canadian Political Parties collection. They're indicative of the kind of data you'll find within the Internet Archive or Archive-It.
