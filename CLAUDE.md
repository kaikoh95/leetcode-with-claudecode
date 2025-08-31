# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Development Commands

- **Test**: `npm run test` - Currently aliases to `npm run dev`

## LeetCode Workflow

This repository follows a structured approach for solving LeetCode problems:

### 1. Problem Setup
- Paste the LeetCode problem statement into `BRIEF.md`
- Include examples, constraints, test cases, and starter code

### 2. Task Processing
- Read `BRIEF.md` and format it according to `TEMPLATE.md` structure
- Write the formatted task into `TASK.md`

### 3. Implementation Flow
- Create detailed implementation plan in `PLAN.md`
- Implement the solution in `src/index.ts`
- Write a summary of the approach in `SUMMARY.md`

### File Structure
- `BRIEF.md` - Raw problem statement from LeetCode
- `TEMPLATE.md` - Standard template format for problem structure
- `TASK.md` - Formatted problem with task, examples, constraints, test cases, and code template
- `PLAN.md` - Detailed algorithmic approach and implementation strategy
- `src/index.ts` - Final TypeScript implementation
- `SUMMARY.md` - Post-implementation summary with data structures and algorithms used

## TypeScript Configuration

- Target: ES2020 with CommonJS modules
- Output directory: `dist/`
- Source directory: `src/`
- Strict type checking enabled
- Source maps and declarations generated

## Generated Files

The following files are auto-generated and should not be manually edited (as indicated in .gitignore):
- `TASK.md`
- `PLAN.md`
- `SUMMARY.md`
- `src/index.ts`

These files are regenerated for each new problem and represent the current working solution.