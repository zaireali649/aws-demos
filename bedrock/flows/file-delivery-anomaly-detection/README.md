# File Delivery Anomaly Detection

Bedrock Flow that monitors client file deliveries from Kafka/Snowflake and detects anomalies based on learned patterns.

## Overview
- Learns each client's delivery schedule automatically
- Detects missing/late files within tight time windows (±5-10 min)
- Creates Jira tickets with intelligent severity levels
- Handles recovery scenarios when late files arrive

## Quick Start
1. Import flow to Bedrock console
2. Test with provided test cases
3. See `demo-script.md` for full walkthrough

## Structure
- `nodes/` - Individual node configurations
- `test-cases/` - JSON test inputs
- `architecture/` - Diagrams and production setup
- `demo-script.md` - 20-minute demo guide