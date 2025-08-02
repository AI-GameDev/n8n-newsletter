# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This repository contains documentation for setting up and configuring an n8n workflow system for automated newsletter management. The project integrates multiple services:

- **n8n Workflow Automation**: Main automation platform (https://gpters-n8n.org)
- **Google Sheets**: For data storage and management
- **Naver Mail**: For sending automated emails
- **Typebot**: For creating interactive forms

## Key Configuration Areas

### 1. n8n Workflow Configuration
- Main workflow documentation in `n8n 워크플로우.md`
- Contains setup for welcome emails and automated 2nd-round emails
- Uses visual workflow builder with node-based configuration

### 2. Google Cloud Console Integration
- Requires Google Cloud Console project setup
- Google Sheets API must be enabled
- Service account credentials needed for authentication
- Documentation in `구글시트 사용을 위한 설정 방법.md`

### 3. Email Service Configuration
- Uses Naver Mail for sending automated emails
- Requires SMTP configuration with app-specific password
- Setup instructions in `네이버 메일 설정.md`

### 4. Typebot Form Integration
- Interactive form builder for collecting newsletter signups
- Integrates with Google Sheets for data storage
- Configuration steps in `타입봇 설정.md`

## Working with Documentation

All documentation is written in Korean and uses Markdown format with embedded screenshots. The screenshots are stored in the `99 Attachments/` directory and referenced using standard Markdown image syntax (`![](99%20Attachments/filename)`).

When updating documentation:
- Maintain the existing Korean language
- Keep screenshot references intact
- Follow the established structure of step-by-step instructions with visual aids

## Important Notes

- This is a documentation-only repository with no executable code
- All configuration is done through web interfaces of the respective services
- The project focuses on no-code/low-code automation using n8n's visual workflow builder

## Claude Interaction Guidelines

- 최종 답변은 항상 한국어로 출력해줘.