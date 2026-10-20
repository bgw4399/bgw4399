[프로젝트 노트 목록](README.md)

> 기존 공개 저장소 `stock-news-analysis-desk`의 프로젝트 소개를 모은 문서입니다. 이 문서 자체에는 실행 코드나 원본 데이터가 포함되어 있지 않습니다.

# Stock News Analysis Desk

Local market-news and price-analysis dashboard for U.S. stocks.

## Overview

This project is a personal decision-support tool that brings together price snapshots, news feeds, market briefing data, and AI-assisted classification. It is designed to help a human review news faster, not to make unsupervised live trading decisions.

## Features

- Yahoo Finance-based quote snapshots
- Google News RSS and leader/company post collection
- positive/negative/neutral news classification
- source-link and evidence preservation
- market briefing dashboard
- portfolio/watchlist rails
- report-style UI for repeated review

## Design Principle

AI outputs are treated as review aids. The system should preserve:

- original source link
- classification label
- contributing keywords/events
- uncertainty or reason for classification

## Stack

- PowerShell server scripts
- JavaScript dashboard
- HTML/CSS
- local JSON state files
- optional VPS deployment scripts

## Public Sharing Notes

Do not upload personal trading state, account data, API keys, or private deployment endpoints. If sharing screenshots, remove portfolio values and any personal financial data.
