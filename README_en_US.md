

**Project Name:**
 **AiTcmFun: AI-Powered Traditional Chinese Medicine Annotation System**

**Project Overview:**
 This project aims to integrate classical Traditional Chinese Medicine (TCM) texts with modern technology to create an intelligent system that combines *annotation and interpretation*, *smart Q&A*, *real-time reminders*, and *knowledge graphs*. It specifically addresses the obscure and easily forgotten knowledge points in TCM textbooks and classical literature. By leveraging the philosophical framework of the *I Ching* and advanced AI techniques, the system translates complex concepts into accessible modern language prompts, enhancing learning efficiency and clinical applicability.

The goal is to drive a transformation of TCM from “experience-based transmission” to “data-driven development,” empowering young doctors, grassroots practitioners, and general users to grasp complex TCM knowledge with minimal learning barriers.

**Key Features:**

- 🌿 Semantic reconstruction and knowledge association using the structure of the *I Ching*;
- 📚 Integration with TCM knowledge graphs to unify terminology and enhance annotation consistency;
- 🤖 Automatic generation of plain-language annotations using knowledge-enhanced large language models (e.g., Gemma);
- 💬 Intelligent Q&A and scenario-based medication advice for end-users;
- ⏰ Built-in real-time reminder and memory assistance mechanisms to create a “warm” AI TCM assistant.

**AI Technologies Used:**

- Knowledge-enhanced large language model (Gemma 3 + RAG)
- OCR + NER to extract entities and terms from PDF versions of classical TCM texts
- Vector database for semantic indexing and fast Q&A
- TCM-specific ontology construction + knowledge graph reasoning
- Lightweight local C++ interaction interface inspired by ChatUI

**AI Models Employed:**
 The primary engine is the Gemma3:27b model, responsible for annotation generation, semantic reasoning, and natural language Q&A.

**Project Positioning and Social Value:**
 Current TCM educational materials are highly specialized and difficult to understand, limiting their accessibility and application. AiTcmFun uses AI to make TCM knowledge more approachable, memorable, and widely spread, helping bring TCM into everyday life as a form of “digital herbalism” for the modern era.