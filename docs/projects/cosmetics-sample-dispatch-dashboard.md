[프로젝트 노트 목록](README.md)

> 기존 공개 저장소 `cosmetics-sample-dispatch-dashboard`의 프로젝트 소개를 모은 문서입니다. 이 문서 자체에는 실행 코드나 원본 데이터가 포함되어 있지 않습니다.

# Cosmetics Sample Dispatch Dashboard

Local operations dashboard for cosmetics sample dispatch analysis.

## Overview

This demo reads a sample-dispatch Excel file, loads it into SQLite, and provides a browser dashboard with filtering, report generation, and rule-based question answering. It does not depend on external GPT APIs.

## Features

- Excel-to-SQLite data ingestion
- sample dispatch status dashboard
- product/person comparison reports
- generated Excel reports
- rule-based query screen
- local server and optional temporary public tunnel

## Stack

- Python
- SQLite
- vanilla JavaScript
- HTML/CSS
- Excel report generation

## Security Notes

The real Excel file may contain contacts, addresses, names, and delivery information. Do not upload the original Excel, generated reports, SQLite DB, server logs, or public tunnel URLs.

For GitHub, include only:

- source code
- README
- synthetic demo data
- screenshots with private fields removed
- `.gitignore`
