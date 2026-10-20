[프로젝트 노트 목록](README.md)

> 기존 공개 저장소 `medical-cdm-explorer`의 프로젝트 소개를 모은 문서입니다. 이 문서 자체에는 실행 코드나 원본 데이터가 포함되어 있지 않습니다.

# Medical CDM Explorer

Research-support system for exploring clinical CDM data and generating cohort definitions from natural language, papers, and PDFs.

## Overview

This project was developed as part of a medical AI/CDM research workflow. The goal was to help researchers move from unstructured clinical questions to structured cohort conditions that can be reviewed, modified, and connected to OMOP CDM concepts.

## Role

- AI engineer for the cohort-generation pipeline
- Designed the flow from natural language/PDF input to structured cohort criteria
- Coordinated with teammates across frontend, backend, and data components
- Reorganized work ownership when progress slowed and interface assumptions diverged

## Core Ideas

- Extract disease, medication, test, time-window, and inclusion/exclusion conditions
- Translate clinical intent into reviewable structured JSON
- Connect extracted concepts to OMOP CDM concept identifiers where possible
- Keep AI output traceable and reviewable instead of treating it as a final answer

## What I Learned

Clinical data is difficult before modeling begins. Patient group definitions, missingness, treatment timing, and physician interpretation must be clarified first. I learned to fill unfamiliar domain gaps by reading papers, checking multiple LLM outputs, asking domain experts, and aligning system behavior with how researchers actually review data.

## Public Sharing Notes

Do not upload hospital data, patient-level records, private CDM tables, credentials, or partner-specific documents. This repository should contain only public-safe architecture notes, synthetic examples, and sanitized code.
