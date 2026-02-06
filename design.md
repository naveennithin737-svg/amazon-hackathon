System Overview

The system consists of six major layers:

User & Sensor Layer

Data Ingestion Layer

Preprocessing Layer

AI/ML Layer

Adaptive Content Engine

Streaming & Analytics Layer

The architecture is designed to be scalable, modular, and low-latency.

High-Level Architecture
User & Sensor Layer

EEG headband

Heart rate monitor

Camera for facial emotion detection

OTT player / Theater display

This layer captures physiological and visual sign

AWS IoT Core (secure device connectivity)

Amazon Kinesis Data Streams (real-time streaming)

API Gateway (secure API routing)

Scene Variant Repository (Amazon S3)

Decision Engine API

Rendering Service (EC2 / Fargate)

Function:

Map emotion classification to content variations

Adjust:

Scene intensity

Background music

Lighting effects

Story branch selection
