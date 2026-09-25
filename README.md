# RAG-based-Enterprise-Knowledge-Assistant

# Project Scope & Progress

## Phase 1 — RAG Foundation

* [x] Load PDF documents
* [x] Split documents into chunks
* [x] Generate embeddings
* [x] Create and persist ChromaDB vector store
* [x] Configure retriever
* [x] Format retrieved documents into context
* [x] Create RAG prompt
* [x] Integrate chat model
* [x] Build RAG chain with LCEL
* [x] Add output parser
* [x] Verify basic question answering

## Phase 2 — Conversation & State

* [ ] Learn LangGraph fundamentals
* [ ] Define conversation state
* [ ] Add message history
* [ ] Add `thread_id` / conversation persistence
* [ ] Integrate retrieval into LangGraph
* [ ] Handle follow-up questions using conversation context
* [ ] Test multi-turn conversations

## Phase 3 - Model Evaluation
* [ ] Evaluate retrieval quality
* [ ] Evaluate answer correctness
* [ ] Test questions with no answer in the documents
* [ ] Test irrelevant/ambiguous questions
* [ ] Experiment with chunk size and overlap
* [ ] Experiment with retrieval `k`
* [ ] Document evaluation results 

## Phase 3 — Application Structure

* [ ] Move notebook logic into Python modules
* [ ] Create clean project structure
* [ ] Separate configuration from application code
* [ ] Create document ingestion pipeline
* [ ] Create vector-store initialization process
* [ ] Make application runnable without the notebook
* [ ] Add environment-variable configuration
* [ ] Add proper `.gitignore`
* [ ] Document local setup

## Phase 4 — Backend

* [ ] Build FastAPI application
* [ ] Create chat endpoint
* [ ] Add request/response Pydantic models
* [ ] Connect FastAPI → LangGraph → RAG
* [ ] Add conversation/thread handling
* [ ] Add input validation
* [ ] Add error handling
* [ ] Return source/document information with answers

## Phase 5 — Testing & Evaluation

* [ ] Create test questions from the source document
* [ ] Add unit tests
* [ ] Add API/integration tests


## Phase 6 — Production-Oriented Improvements

* [ ] Add structured logging
* [ ] Add request/error tracking
* [ ] Track retrieval and LLM latency
* [ ] Track token usage/cost
* [ ] Add appropriate timeouts
* [ ] Handle LLM/API failures gracefully
* [ ] Add basic security considerations
* [ ] Review prompt-injection risks
* [ ] Add caching where appropriate

## Phase 7 — Containerization & Deployment

* [ ] Create Dockerfile
* [ ] Containerize the backend
* [ ] Configure production environment variables
* [ ] Deploy backend
* [ ] Configure persistent storage/database
* [ ] Verify deployed RAG system
* [ ] Document deployment architecture

## Phase 8 — Frontend

* [ ] Build simple chat interface
* [ ] Connect frontend to FastAPI
* [ ] Display conversation history
* [ ] Display retrieved sources/citations
* [ ] Handle loading/error states
* [ ] Test complete frontend → backend → RAG flow

## Phase 9 — Final Project

* [ ] Clean up code
* [ ] Remove notebook-only/unused code
* [ ] Add complete README
* [ ] Add architecture diagram
* [ ] Document technical decisions
* [ ] Document evaluation results
* [ ] Document limitations
* [ ] Add setup instructions
* [ ] Add screenshots/demo
* [ ] Final end-to-end test
* [ ] Deploy final version
