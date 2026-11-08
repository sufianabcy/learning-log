# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repo is

A personal learning log in plain Markdown for a month-long course that started 2 Nov 2026. Topics so far: subnetting, SQL, Python, Java and Linux. There is no code, build, lint or test step. The only tooling is git.

## Layout

- `log/week-NN.md`: one file per week (zero-padded, e.g. `week-01.md`). The title is `# Week N · <date range>` (e.g. `# Week 1 · 2–8 Nov 2026`). Sections:
  - `## Baseline scores (<date>)`: score per topic (e.g. `Subnetting: 1/20`), plus notes on which questions were missed and why.
  - `## Retro`: bullets labelled `Learned`, `Built`, `Confused` and `Explain-back`. Explain-back is the user explaining a concept in their own words.
- `notes/<topic>.md`: running reference notes, one file per topic (e.g. `linux.md`). The title is `# <Topic> notes`. Each session gets a dated `##` heading (e.g. `## Linux Upskill Day 1: get to know your server (9 Nov 2026)`). Commands are bullets: `` `command`: what it does ``.

## Conventions

- Dates are written as `9 Nov 2026`.
- Commit messages use a scope prefix, e.g. `log: week 1 retro and baseline scores`.
- The entries, especially explain-backs and self-ratings, are the user's own record of what they understand. Don't rewrite or "correct" them unless asked. If an explanation looks wrong, point it out in chat.

## Lab environment

Linux practice runs on an OrbStack VM with Ubuntu 26.04.1 LTS. Log in with `ssh learn@orb`.
