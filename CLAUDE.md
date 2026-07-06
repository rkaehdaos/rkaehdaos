# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

This is GeunChang Ahn's GitHub **profile repo** — a special repository named identically to the
GitHub username (`rkaehdaos/rkaehdaos`), whose `README.md` is rendered on the user's public GitHub
profile page. It is not an application: there is no build system, package manifest, lint config,
or test suite, and none should be assumed or added unless the user explicitly asks for one.

## Repository contents

- `README.md` — the profile page content shown on github.com/rkaehdaos. Edits here are user-facing
  and public; changes should be made carefully since they display real hardware/model details the
  user has chosen to share (e.g. current MacBook specs).
- `MasterFeature.md`, `test.md` — informal scratch/working notes, not tied to any build process.
- `keycloak_spring_auth.md` — a personal comparison note (Keycloak vs. Spring Authorization Server),
  written in Korean, unrelated to this repo's own content.
- `persons.json` — a large (~5MB) sample/fake dataset (randomuser.me-style records). It is scratch
  data, not consumed by any code in this repo.

## Working conventions

- Most content in this repo, including commit history and notes, is written in Korean; match that
  when editing existing files.
- There is no code to compile, lint, or test — do not introduce a build toolchain speculatively.
- Treat `README.md` edits as public-facing: verify Markdown/image-link syntax renders correctly
  (this repo's recent history includes fixes for broken image link formatting).
