[프로젝트 노트 목록](README.md)

> 기존 공개 저장소 `nvidia-nemotron-reasoning`의 프로젝트 소개를 모은 문서입니다. 이 문서 자체에는 실행 코드나 원본 데이터가 포함되어 있지 않습니다.

# NVIDIA Nemotron Reasoning LoRA Experiments

Public-safe summary of NVIDIA Nemotron Model Reasoning Challenge experiments.

## Overview

This project explores LoRA/PEFT adapter strategies for a reasoning-model Kaggle challenge. The work focuses on verifier audits, failure taxonomy, independent model-family discovery, adapter diversity, and model merging rather than small single-parameter tweaks.

## Problem Structure

The challenge includes reasoning families such as:

- Bit Manipulation
- Equation Transformation
- Gravitational Constant
- Numeral Conversion
- Text Encryption
- Unit Conversion

Local audits showed that Equation Transformation was the main bottleneck, while Text Encryption and Numeral Conversion had stronger rule/verifier coverage.

## What Was Built

- Baseline and champion adapter integrity audits
- Failure taxonomy and verifier coverage analysis
- D4 numeric equation solver audit
- Candidate diversity audit for LoRA adapters
- TIES/DARE/model-soup experimentation plan
- Public-score tracking notebooks and submission packaging checks

## Notable Local Audit Result

The D4 numeric equation solver audit selected 68 exact rows with 0 wrong rows in the local audit, giving selected precision of 1.0. This was used as a safe candidate signal rather than blindly adding noisy rows.

## Methods Explored

- LoRA/PEFT adapter submission packaging
- Solver repair and preserve SFT
- Verifier-filtered training data
- Adapter diversity analysis
- TIES/DARE/model soup
- Independent trained-adapter family acquisition
- Paper-inspired candidate diversity strategies

## Public Sharing Notes

Do not upload:

- Kaggle input data if redistribution is restricted
- model weights or submission zips unless allowed
- private leaderboard logs or credentials
- downloaded external models with unclear license

Upload only notebooks/scripts that are safe to share and include enough explanation for reproducibility.
