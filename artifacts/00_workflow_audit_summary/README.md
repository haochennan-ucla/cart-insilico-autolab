# Workflow Audit Summary

This directory contains a public, post-processed workflow audit summary. It maps recorded artifacts into reviewer-facing stages, but it is not a real-time scheduler trace and it did not drive workflow execution.

The actual workflow control flow is executed by Python (`AutolabOrchestrator.run_all` and the AutoResearch workflow wrapper). LLM agents contribute to selected steps such as goal parsing, hypothesis generation, parameter proposal, simulation-sensitivity refinement, and refinement-loop decision.

