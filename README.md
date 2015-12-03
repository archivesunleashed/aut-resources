# Warcbase Resources

This is the resource repository for Warcbase, [which you can find here](https://github.com/lintool/warcbase). Warcbase is an open-source platform for managing web archives built on Hadoop and HBase. The platform provides a flexible data model for storing and managing raw content as well as metadata and extracted knowledge. Tight integration with Hadoop provides powerful tools for analytics and data processing via Spark.

## Getting Started

Follow the instructions on the [main Warcbase page](https://github.com/lintool/warcbase), and consult the [detailed documentation available here](http://lintool.github.io/warcbase-docs/).

This repository contains supporting resources that you need for some of the commands, such as:
- Named Entity Recognition;
- Sample WARC and ARC files for protoyping

## Contents

- `/ner/english.all.3class.distsim.crf.ser.gz`: This classifier is trained on English-language locations, organizations, and people. It is a central part of the [Spark: Named Entity Recognition](https://github.com/lintool/warcbase/wiki/Spark:-Named-Entity-Recognition) recipie.
- Sample Data: In the `/sample-data/` directory, we have one ARC and one WARC file from the University of Toronto's Canadian Political Parties collection. They're indicative of the kind of data you'll find within the Internet Archive or Archive-It..
