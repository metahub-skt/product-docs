---
layout: default
title: "MetaHub"
---
# MetaHub

데이터 레이크를 위한 통합 메타데이터·카탈로그·정책 플랫폼입니다. 단일 Helm chart 로 메타데이터 플랫폼(DataHub),
Iceberg REST 카탈로그(Apache Polaris), 정책 엔진(OPAL/OPA), 카탈로그 API 게이트웨이, 관리 콘솔, AI 도구 연동(MCP)을
배포·운영합니다. 통합 chart 버전이 곧 제품 릴리즈입니다.

## Release Notes

최신 릴리즈부터 나열합니다. 각 노트는 What's New · Features · Improvements · Fixes · Known Issues · Breaking Changes ·
Deprecations · Upgrade Notes 순서입니다.

| 버전 | 발행일 | 요약 |
|---|---|---|
| [0.5.6](releases/v0.5.6.md) | 2026-10-15 | 빈 PostgreSQL 에서 chart 만으로 Polaris 설치 가능(dbInit, 기본 꺼짐) · Catalog Gateway 요청 이력 로그 누락 수정 |
| [0.5.0](releases/v0.5.0.md) | 2026-10-07 | 메타데이터 플랫폼 코어 DataHub v1.7.0.1 업그레이드 · MCP 전송 방식 선택(sse/http) · 폐쇄망 UI 수집 |

0.5.1 ~ 0.5.5 와 0.5.7 의 상품 노트는 준비 중입니다. 그 사이 변경은 0.5.6 노트의 Upgrade Notes 에 요약되어 있습니다.
