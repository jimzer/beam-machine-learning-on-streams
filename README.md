# Machine Learning on Streams with Apache Beam

This is a workshop for the Start Hack [Start Hack](https://www.starthack.eu/) 2021. 

It's originally intended to be run in a Google Colab notebook. Here is the read-only link to it: [notebook](https://colab.research.google.com/drive/1RWtxEWsjzlrltbx4zrKMYOUt_P0KCkwA?usp=sharing)



## What will we build ?

In this workshop, we will learn how to use Apache Beam to detect potential disasters occurring in the world. We will receive a stream of Tweets as input, use machine learning to detect anomalies, and send alert events in an output stream. These alerts can be consumed in real-time by any service of interest.

## Topics

Two main topics in this workshop: streaming data processing and Apache Beam.

### Streaming Data Processing

Data processing is either offline or online. There are a lot of applications    from streaming/online machine learning, where you receive a continuous flux of data to transform. The output can then be either stored or directly sent to another output stream.
For instance, detecting anomalies in a continuous stream of events (IoT sensors, transactions, ...) and sending alterts to an output stream.


### Apache Beam

**Apache Beam** is a unified programming model to define batch and **streaming** data processing jobs. It's compatible with multiple executor engine such as *Apache Spark*, *Apache Flink* or *Google DataFlow*. It follows the philosopy "Write once, run everywhere" and has SDK in multiple languages, i.e **Python**, Java and Go.
