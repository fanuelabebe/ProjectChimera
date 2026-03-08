# Technical Specification

## API Contracts

### Create Content Task

Endpoint

POST /api/tasks

Request JSON

{
  "topic": "AI influencers",
  "platform": "TikTok",
  "persona": "Tech educator"
}

Response

{
  "taskId": "12345",
  "status": "CREATED"
}