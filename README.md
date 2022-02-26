# Week-4-Industrial-IoT-with-Google-Cloud-Quiz
Week 4

Quiz 1: Pub/Sub

1. What is a topic?

Ans: A resource that accepts messages sent by publishers.


2. What is a subscription? 

Ans: A resource of streaming messages from a single topic. 


3. A topic can have _______ publishers. 

Ans: many


4. How many topics can a subscriber subscribe to?

Ans: one


5. What happens to messages if they cannot be delivered?

Ans: Messages remain in the message store until they are delivered and acknowledged.



Quiz 2: Cloud IoT Core

1. What are the steps for connecting devices to Google Cloud Platform?

Ans: Create a registry, add a topic to it, and add the device.


2. On how many topics can a registry publish?

Ans: many


3. Which communication protocol can use Cloud IoT Core's last known heartbeat?

Ans: MQTT



Quiz 3: Google Cloud Storage

1. You are designing an IoT network and would like to store the streaming data on Google Cloud Storage. You'll need to access the data several times when it first arrives, but then not at all after that. Which storage class should you use when creating the bucket?

Ans: Standard for frequently accessed data. Archive for long-term storage.


2. Which of these statements is a characteristic of Google Cloud Storage

Ans: Google Cloud Storage buckets must have globally unique names.
     Bucket permissions can be set to allow anyone on the internet access to the bucket. 
     Data in Google Cloud Storage is encrypted with a Google managed key.


3. You are designing a website to show streaming videos. Which Cloud Storage class would be best for the video content?

Ans: Standard



Quiz 4: Dataflow

1. Dataflow jobs can be created with Google supplied templates. What are the steps for setting up a 'Pub/Sub-to-GCS text' pipeline?

Ans: Create a Pub/Sub topic, a storage bucket, select the Pub/Sub-to-GCS text template. 


2. Which of the following statements is a characteristic of Dataflow?

Ans: Custom templates and Google supplied templates use an environment that includes Apache Beam SDK. 
     You can create your own templates, use Google supplied templates, or do a traditional job execution. 
