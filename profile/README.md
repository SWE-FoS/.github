🥔 Potato Savoir

Also a talking potato? Come join us!

Potato Savoir is a creative engineering organization exploring human–AI interaction, real-time speech systems, and experimental UX design.
Our flagship project is FOS (Focus on Speaking) — a real-time AI presentation & meeting assistant.

🔥 Main Project: FOS (Focus on Speaking)

FOS is a real-time AI prompter designed to seamlessly integrate with smart displays (e.g., LG signage).
It supports the entire presentation and meeting flow — before, during, and after — using advanced speech analysis and AI-driven feedback.

🧩 Key Features

Real-time teleprompter with fast, stable STT

Script–speech synchronization using KoSentence-BERT + LLM

Keyword omission detection & missing content recovery

Real-time script reconstruction for more natural follow-up delivery

Presenter dashboard: speaking speed, progress tracking, clarity score

Meeting Mode (Agenda Map)

Real-time utterance intent tagging (idea / decision / action item / question / issue)

Topic clustering & agenda flow visualization

Decision–Action Item auto-tracking

Fact-check widget (RAG or web search 기반)

Automated meeting summary & key insights extraction

🚀 Live Demo

FOS is deployed on Vercel:
https://focusonspeaking.vercel.app/

(로그인이 필요한 기능은 비활성화될 수 있음)

🧱 Project Documentation
1. Overview Paper (IEEE-style)

프로젝트 개요, 요구사항, 시스템 아키텍처는 다음 문서에 정리되어 있습니다:
docs/fos_paper.tex

2. Architecture Diagram

전체 시스템 구조 (Frontend / Meeting AI / Teleprompter Engine / Dashboard / Back-end)
→ 프로젝트 README 또는 문서 내 다이어그램 참고

3. Repository Structure

전체 코드 구조는 아래 문서 참고:
structure.md

🛠 Tech Stack

Frontend

React + Vite

Tailwind / shadcn UI

Web Speech API

Recharts & custom visualization modules

AI / Backend

LLM pipeline (OpenAI / Gemini)

KoSentence-BERT for sentence alignment

FastAPI or Node (depending on deployment)

RAG-based fact-check pipeline

Vercel Edge Functions

Supabase / Mongo / Firebase (선택적)

🥔 Organization Mission

실시간 AI 기반 발표·회의 경험 혁신

직관적이고 자연스러운 Human–AI Interaction 연구

학술적 가치 + 실용적 UX를 모두 갖춘 AI 엔지니어링

창의적인 프로젝트를 자유롭게 실험하는 공간
