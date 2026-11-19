# Oligarchy

Oligarchy is an automation harness for testing Omarchy releases in QEMU guests. The client interacts with the guest, while the control plane records test runs and session results.

| Task | Guide |
| --- | --- |
| Inspect a guest, send input, or capture its screen | [Guest client](client.md) |
| Define a test and inspect its results | [Control plane](ctrl.md) |
| Investigate a failed session | [Diagnosis](ctrl-diagnose.md) |
| Work on the harness itself | [Development guide](development.md) |

For a first read, follow the client and control-plane guides together. A guest screenshot shows what happened on screen. The session record connects that observation to a particular test run.
