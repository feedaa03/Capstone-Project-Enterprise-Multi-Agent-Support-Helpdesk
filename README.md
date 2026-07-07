# Capstone-Project-Enterprise-Multi-Agent-Support-Helpdesk

Developer: Feda Mohammed Alyahya

Track: Generative AI & LLM Production Engineering

Environment: Google Colab Production Environment

🏗️ Project Architecture Overview & Core Framework

This Capstone project delivers a high-performance, production-grade Multi-Agent Helpdesk Orchestrator designed to process enterprise employee requests with mathematical validation, dynamic tool routing, and strict fact-grounding (RAG).

The system completely bypasses single-prompt monolithic patterns, replacing them with a modular framework built strictly around the SDAIA Capstone Grading Rubric Requirements:

Multi-Agent Orchestration (25%): Built with two specialized, collaborating personas: a Level-1 Support Router (intent parsing) and a Knowledge Support Analyst (context synthesis).
RAG Implementation (25%): Fully operational dense document ingestion powered by ChromaDB and semantic vector embeddings (all-MiniLM-L6-v2) ensuring zero hallucinations.
Tool Calling & Pydantic Schemas (20%): Execution of a localized native Python function via the structured Two-Call Tool Protocol mapped with explicit Pydantic-compliant constraints.
DeepEval Mathematical Integration (20%): Complete algorithmic logic verification running strict evaluation test cases (Answer Relevancy and Faithfulness) yielding quantifiable production metrics.
Colab Execution & Tracing (10%): Seamless, error-free runtime utilizing unified abstraction fail-safes via LiteLLM with secure, isolated environment tracking configuration (os.environ).
🗺️ Architectural Workflow Map

The diagram below illustrates the comprehensive request flow, mapping how incoming queries are dynamically isolated, routed via native tools, or contextualized using vector-database token retrieval
