# Zakat Assistant Widget

**An embeddable website interface for a Zakat assistant workflow.**

## The problem

An assistant sitting inside a builder is not much help to a visitor on a different website. The visitor needs somewhere to ask the question.

This project supplies that missing interface: a small widget that connects a website to the configured assistant workflow.

## The solution

A Next.js integration that creates ChatKit sessions on the server and exposes both a full-page assistant and a floating embeddable widget.

## What it does

- Full-page chat interface.
- Floating widget with open/close controls.
- External embed script for another website.
- Server-side ChatKit session creation.
- Connection to a configured Agent Builder workflow.

## Engineering highlights

Connects a lightweight website loader to server-side session creation, keeping provider credentials on the backend. The same integration supports a standalone chat page and a floating widget embedded in another website.

## Technology

Next.js, TypeScript, OpenAI ChatKit, Agent Builder workflow integration, JavaScript embed loader.

## Source code

This repository documents the project, its capabilities, and the engineering behind it. The application source code is maintained privately.

