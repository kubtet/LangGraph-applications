# LangGraph-applications

# Conversational AI Workflows: Graphs, Memory & Message Management

## Overview

This project explores the implementation of conversational AI workflows using graph-based architectures. It focuses on building and understanding the core components required to create stateful AI applications, including graph construction, message management, and memory persistence.

The project is organized into practical Jupyter notebooks, each demonstrating a specific concept or implementation. Together, they provide a hands-on exploration of how conversational systems can maintain context, manage conversation history, and structure interactions through graph-based workflows.

## Project Objectives

The main objectives of this project are to:

- Understand the fundamentals of graph-based AI workflows.
- Explore graph construction and conditional execution.
- Implement message management using state and reducer functions.
- Learn how to control conversation history through message trimming and summarization.
- Understand the differences between short-term and long-term memory.
- Explore thread-level persistence for maintaining conversational state.


## Topics Covered

### 1. Graph Components and Implementation

Explores the fundamental building blocks of graph-based workflows.

| Notebook | Description |
|---|---|
| `Simple_graph.ipynb` | Introduction to graph construction and basic graph execution. |
| `Conditional_graph.ipynb` | Implementation of conditional logic and branching within a graph. |

### 2. Message Management

Focuses on managing messages and conversation state within AI applications.

| Notebook | Description |
|---|---|
| `MessagesState_class.ipynb` | Exploring the MessagesState class for managing conversation messages. |
| `Annotated_construct_and_reducer_function.ipynb` | Understanding Annotated types and reducer functions for state updates. |
| `Trimming_messages.ipynb` | Managing conversation history by trimming unnecessary messages. |
| `Summarizing_messages.ipynb` | Exploring message summarization to maintain manageable conversation context. |

### 3. Thread-Level Persistence and Memory

Explores how conversational applications maintain information across interactions.

| Notebook | Description |
|---|---|
| `Short_term_memory.ipynb` | Exploring short-term memory and maintaining context within a conversation thread. |
| `Long_term_memory.ipynb` | Exploring long-term memory and retaining information beyond individual interactions. |

## Technologies

The project uses a notebook-based Python environment and explores concepts related to:

- **Python** – Primary programming language.
- **Jupyter Notebook** – Interactive development and experimentation.
- **LangGraph concepts** – Graph-based workflow construction, state management, and persistence.
- **Conversational AI** – Message handling, context management, and memory.


## Key Learning Outcomes

- How graph-based workflows are constructed and executed.
- How conditional edges control workflow execution.
- How state and reducer functions manage application data.
- How messages are stored and manipulated during conversations.
- How conversation history can be trimmed or summarized.
- How short-term memory differs from long-term memory.
- How thread-level persistence supports stateful conversational applications.


