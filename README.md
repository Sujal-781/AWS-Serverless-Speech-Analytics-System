# AWS Audio Intelligence Pipeline 🎧☁️

A serverless AWS pipeline that converts uploaded audio into transcripts,
detects exciting moments, and generates highlight scripts using GenAI.

Built as a 4-week hands-on AWS learning project (2 hrs/day).

---

## 🧠 What This System Does

1. User uploads audio to S3
2. Lambda triggers transcription (Amazon Transcribe)
3. Transcript is parsed and stored
4. Highlight-worthy segments are detected
5. GenAI generates short highlight scripts
6. Orchestration handled using Step Functions

---

## 🛠 AWS Services Used

- IAM
- S3
- Lambda (Python, boto3)
- CloudWatch
- Amazon Transcribe
- Amazon Bedrock
- Step Functions

---

## 🏗 Architecture (Current)

![Architecture Diagram](architecture/v2.png)

---

## 📅 Learning Timeline

- **Week 1:** AWS fundamentals, IAM, S3, Lambda
- **Week 2:** Speech-to-text pipeline (Amazon Transcribe)
- **Week 3:** Highlight detection + GenAI (Bedrock)
- **Week 4:** Production-ready orchestration & monitoring

---

## 📈 Status

✅ Actively built and documented  
✅ Focused on real-world backend pipelines
