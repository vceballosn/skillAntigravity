---
name: Quarkus Docker Multi-Stage Builds
description: Consult the Quarkus Docker Multi-Stage Builds NotebookLM notebook for container image optimization, multi-stage build strategies, and Dockerfile selection for Quarkus apps.
---

# Quarkus Docker Multi-Stage Builds

## Overview

This skill connects you to the **Quarkus Docker Multi-Stage Builds** NotebookLM notebook, covering architectural optimization of Quarkus applications through Docker multi-stage builds, image size reduction, and container best practices.

## When to Use

- When creating or modifying **Dockerfiles** for Quarkus applications (JVM, native, native-micro, legacy-jar)
- When optimizing **container image size** for OpenShift/Kubernetes deployment
- When choosing between **distroless**, **UBI-minimal**, and standard base images
- When configuring **multi-stage builds** with GraalVM native compilation
- When troubleshooting **native build failures** in Docker containers

## How to Use

Query the notebook using the NotebookLM MCP tool:

```
ask_question(
  notebook_id="quarkus-docker-multi-stage-bu",
  question="Your question here"
)
```

### Example Queries

- "What is the recommended Dockerfile for a Quarkus native application?"
- "How do I reduce Docker image size for a Quarkus JVM app?"
- "What are the differences between Dockerfile.jvm, native, and native-micro?"
- "How do I configure a multi-stage build for GraalVM native compilation?"
- "What base image should I use for production Quarkus containers on OpenShift?"

## Notebook Details

| Field       | Value                                                                                     |
|-------------|-------------------------------------------------------------------------------------------|
| **ID**      | `quarkus-docker-multi-stage-bu`                                                           |
| **URL**     | https://notebooklm.google.com/notebook/eae3f120-b883-4f69-b22d-9e9b24f1c89f               |
| **Topics**  | Docker Multi-Stage Builds, Quarkus Containers, Image Optimization, Distroless, UBI Minimal |

## Important Notes

- Requires NotebookLM authentication (`setup_auth`) to query the notebook
- If authentication is not available, you can still reference this skill for topic awareness and manually consult the notebook URL
- The BIAN sample projects include 4 Dockerfile variants — this skill helps understand when to use each one
