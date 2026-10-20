[프로젝트 노트 목록](README.md)

> 기존 공개 저장소 `neurogolf-2026`의 프로젝트 소개를 모은 문서입니다. 이 문서 자체에는 실행 코드나 원본 데이터가 포함되어 있지 않습니다.

# NeuroGolf 2026 Graph Surgeon Experiments

Public-safe summary of The 2026 NeuroGolf Championship experiments.

## Overview

This project studies task-level optimization for NeuroGolf 2026 using graph/ONNX profiling, component blending, score-cost audit tables, and compact graph-surgeon style submissions.

## Key Ideas

- Task-level profiling instead of one global rule
- ONNX/task asset inspection
- Component blending with audit tables
- Score-cost tradeoff tracking
- Public-score resistant validation thinking

## Tracked Score Progression

| Stage | Score | Method |
| --- | ---: | --- |
| baseline | 6310.86 | trusted task-level baseline |
| audited fusion | 6364.78 | audited solver components |
| clean baseline | 6368.30 | audited fusion plus graph cleanup |
| compact fusion | 6405.31 | compact solver family fusion |
| graph surgeon | 6405.61 | compact graph surgeon |

## Repository Contents

Recommended public-safe contents:

- `README.md`
- selected notebooks with outputs cleared
- `score_progression.csv`
- `component_mix.csv`
- `task_gain_audit.csv`
- lightweight scripts for profiling and blending

Do not upload competition data or private leaderboard artifacts if the license does not allow redistribution.
