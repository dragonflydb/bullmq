<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bullmq](./bullmq.md) &gt; [QueueSchedulerListener](./bullmq.queueschedulerlistener.md) &gt; [failed](./bullmq.queueschedulerlistener.failed.md)

## QueueSchedulerListener.failed property

Listen to 'failed' event.

This event is triggered when a job has thrown an exception.

<b>Signature:</b>

```typescript
failed: (jobId: string, failedReason: Error, prev: string) => void;
```