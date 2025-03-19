# Stream-Data-Pipeline-Kafka

In this project, I developed a real-time audio streaming pipeline using Kafka, consisting of a Producer and a Consumer.

- The Producer captured live audio data using PyAudio and streamed it to a Kafka topic.
- The Consumer, subscribed to this Kafka topic, processed the incoming audio in real time.
- For transcription, Whisper was used, and for speaker diarization, PyAnnote Audio was utilised to identify different speakers in the audio stream.

Kafka served as the backbone of this pipeline, ensuring reliable message delivery, data consistency, and fault tolerance while enabling seamless real-time data processing.
