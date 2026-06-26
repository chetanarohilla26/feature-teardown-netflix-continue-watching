## Analytics Instrumentation

To evaluate feature performance, I would track the following events.

| Event | Description |
|---------|---------|
| continue_watching_impression | User sees row |
| continue_watching_click | User resumes content |
| archive_auto_triggered | Content archived automatically |
| archived_content_restored | User restores archived content |
| session_started | Viewing session begins |
| episode_completed | Episode completed |

### Funnel

Continue Watching Impression

↓

Continue Watching Click

↓

Session Started

↓

Episode Completed

↓

Return Visit

---

## Event Definitions

1. continue_watching_impression

Triggered when the row becomes visible.

2. continue_watching_click

Triggered when a user resumes content.

3. archive_auto_triggered

Triggered when content is automatically archived.

4. archived_content_restored

Triggered when archived content is restored.

---

## Dashboard Metrics

Product Team Dashboard

- Continue Watching CTR
- Resume Completion Rate
- Archive Rate
- Restore Rate
- Session Starts
- Viewing Hours Per User
