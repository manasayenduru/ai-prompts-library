# 📝 Meeting Intelligence Summarizer

## Overview

The **Meeting Intelligence Summarizer** transforms raw meeting transcripts into structured business intelligence reports.

Instead of producing a basic summary, this prompt extracts:

* Executive insights
* Key discussion topics
* Decisions made
* Action items
* Risks and blockers
* Follow-up questions
* Next-step recommendations

This prompt is useful for:

* Team Meetings
* Client Calls
* Project Reviews
* Sprint Retrospectives
* Stakeholder Discussions
* Workshops
* Interviews
* Strategy Sessions

---

## Prompt

```text
Act as a Meeting Intelligence Analyst and Executive Documentation Specialist.

Your task is to analyze a meeting transcript and transform it into a structured decision-making report.

Do not simply summarize the conversation.

Instead, identify business intelligence hidden within the discussion.

Perform the following analysis:

## Stage 1: Meeting Overview

Identify:

- Meeting Purpose
- Meeting Type
- Participants
- Business Context

## Stage 2: Executive Summary

Provide a concise summary of the meeting in 5–10 bullet points.

Focus only on the most important information.

## Stage 3: Key Discussion Topics

For each major topic discussed:

- Topic Name
- Summary
- Important Insights

## Stage 4: Decisions Made

Extract all decisions.

For each decision provide:

- Decision Description
- Status (Approved, Rejected, Deferred)
- Impact

## Stage 5: Action Items

Create a table containing:

- Task
- Owner
- Priority
- Due Date
- Dependencies

## Stage 6: Risks and Concerns

Identify:

- Risks
- Blockers
- Challenges
- Unresolved Issues

Explain why each issue matters.

## Stage 7: Follow-Up Questions

List unanswered questions that require clarification.

## Stage 8: Next Steps

Generate a prioritized action plan for the team.

## Output Format

1. Meeting Overview
2. Executive Summary
3. Key Discussion Topics
4. Decisions Made
5. Action Items
6. Risks and Concerns
7. Follow-Up Questions
8. Next Steps

Think like an executive assistant, business analyst, and project manager simultaneously.
```

---

## Expected Output Structure

### 1. Meeting Overview

* Meeting Purpose
* Meeting Type
* Participants
* Business Context

### 2. Executive Summary

* Key Point 1
* Key Point 2
* Key Point 3

### 3. Key Discussion Topics

| Topic      | Summary            | Insights    |
| ---------- | ------------------ | ----------- |
| Topic Name | Discussion Summary | Key Insight |

### 4. Decisions Made

| Decision             | Status                         | Impact          |
| -------------------- | ------------------------------ | --------------- |
| Decision Description | Approved / Rejected / Deferred | Business Impact |

### 5. Action Items

| Task             | Owner              | Priority            | Due Date | Dependencies  |
| ---------------- | ------------------ | ------------------- | -------- | ------------- |
| Task Description | Person Responsible | High / Medium / Low | Date     | Related Tasks |

### 6. Risks and Concerns

| Risk             | Impact          | Recommendation   |
| ---------------- | --------------- | ---------------- |
| Risk Description | Business Impact | Suggested Action |

### 7. Follow-Up Questions

* Question 1
* Question 2
* Question 3

### 8. Next Steps

1. Immediate Actions
2. Short-Term Actions
3. Long-Term Actions

---

## Key Features

* Extracts actionable insights
* Detects hidden business decisions
* Generates project-ready action items
* Identifies risks and blockers
* Creates executive-friendly reports
* Improves meeting accountability
* Supports project management workflows

---

## Best Use Cases

* Executive Meetings
* Product Planning Sessions
* Client Discovery Calls
* Team Standups
* Retrospectives
* Strategic Planning Meetings
* Cross-Functional Workshops
* Stakeholder Reviews

---

## Prompt Category

**Summarization Technique → Meeting Intelligence Summarizer**
