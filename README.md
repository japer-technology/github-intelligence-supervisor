# 🚨 github-intelligence-supervisor

Providing account wide intelligent repo supervisor master control.

Amongst many things:

- A central GitHub-native scheduler that reads repo-owned declarative config from .github-cron, maintains an indexed registry, and dispatches jobs to repositories via repository_dispatch.
