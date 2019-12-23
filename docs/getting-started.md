---
id: getting-started
title: Getting Started
sidebar_label: Getting Started
---

Quickly find text in files. `quick-find-in-files` recursively searched sub-directories in a high-performance manner by leveraging the speed of c++.

## Usage

```ts
import { quickFindInFiles } from 'quick-find-in-files'

const result = quickFindInFiles(process.cwd(), 'needle')
```