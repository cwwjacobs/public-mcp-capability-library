# Tool-Use Checklist

Use this before accepting agent tool use.

## Before Tool Use

- [ ] Tool is needed for the task.
- [ ] Tool purpose is clear.
- [ ] Tool arguments are scoped.
- [ ] Tool does not require secrets unless explicitly approved.
- [ ] Tool does not write externally unless explicitly approved.

## After Tool Use

- [ ] Result was summarized accurately.
- [ ] Relevant evidence was preserved.
- [ ] Errors were not hidden.
- [ ] Output did not cause task drift.
- [ ] Follow-up action is justified.

## Hold Conditions

Hold for review if the tool would:

- alter remote state
- publish, deploy, or send data
- access credentials
- delete files or data
- change security settings
- modify payment, account, or user information
