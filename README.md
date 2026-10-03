ACS Guardian

A runtime kill switch for AI agents, built on the OWASP Agent Control Standard (ACS).

The Problem: 88% of organizations have experienced an AI agent security incident. Companies are giving AI agents access to databases, emails, and payment systems without runtime controls.

The Solution: This tool implements the toolCallRequest hook to evaluate agent actions in real-time and return ALLOW or DENY. If an agent tries to do something outside its declared scope, it gets blocked.

Tech Stack: Python, YAML

Status: MVP in development.
# acs-guardian