# AIDF Architecture

## Overview
AIDF is built as a modular multi-agent autonomous development framework integrated into IDE environments.

## System Layers
1. IDE Layer
2. AIDF Core Layer
3. Agent Layer
4. Memory & Artifact Layer
5. Deployment Layer

## Core Components
- Flow Orchestrator
- Agent Router
- Memory Graph Engine
- Artifact Vault
- Repo Indexer
- Security Sandbox

## Memory Graph
Stores relationships:
Decision → Component → File → Test → Build → Deployment

## Agent Model
Stateless agents operate on persistent memory.

## Security
RBAC, encrypted secrets, immutable audit logs.

## Scalability
Supports multi-project parallel pipelines.
