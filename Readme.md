# Sentiment Analysis Kafka Project

This project demonstrates a simple sentiment analysis pipeline using Kafka, Docker, and Python. It consists of the following components:

1. **Zookeeper**: Manages Kafka brokers.
2. **Kafka Broker**: Manages the messaging system.
3. **Sentence Producer**: Generates random sentences and produces them to a Kafka topic.
4. **Sentiment Analyzer**: Consumes sentences from the Kafka topic and performs sentiment analysis.

# Generating random words
https://wonderwords.readthedocs.io/en/latest/quickstart.html#the-randomsentence-class

# How to
1. Run `python -m venv env` to create virtual environment
2. Activate Python virtual environment `.\env\Scripts\activate`
3. Run `pip install -r requirements.txt` to install Python packages
4. Run `docker-compose up` to spin up Kafka broker
5. Run `python sentences_producer.py` to run the producer to produce data
6. Run `python analytics.py` to get the data stream from Kafka and run the sentiment analysis

