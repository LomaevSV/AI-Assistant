# AI-Assistant — Project Overview

## Concept

AI-Assistant is being developed as a personal digital assistant that can understand user messages, maintain structured context and execute actions safely. Time planning is the first mature domain, not the boundary of the product.

## Problem

An LLM can understand language well, but free-form model output should not become the source of truth for calendars, memory or other user data. The project therefore separates language understanding from action execution.

The LLM interprets. Code performs calculations, validates constraints, enforces rules, executes transactions and persists state.

## Current functional focus

The system is designed around events, tasks, deadlines, recurring schedules, reminders, people and related facts, time conflicts, travel constraints and user planning preferences.

## Direction

The architecture is intended to support additional domains and services without making the LLM a direct executor of operations. New capabilities should connect through validated application/domain interfaces and execution policies.

## Reliability

Key engineering principles include deterministic time and conflict calculations, provenance for important data, transactional mutations, idempotency, separation of Proposal and Policy, and multi-level automated testing.

## Public version

This repository is intended to demonstrate the project and its architecture. It does not contain production source code, secrets, user data or operational configuration.
