# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

**Canopy** is a Lua script for nornsvember. This is an early-stage project currently in the initial setup phase.

## Technology Stack

- **Primary Language:** Lua
- **Build System:** Potentially luarocks (based on .gitignore configuration)
- **Platform:** Designed for Norns (a sound computer/synthesizer platform)

## Project Structure

This is a newly initialized repository. The main files currently are:
- `.gitignore` - Configured for Lua projects with potential C extensions
- `README.md` - Basic project description

Source code files will be added as development progresses. Typical Norns scripts follow this structure:
- Main script file (usually matching the project name, e.g., `canopy.lua`)
- `lib/` directory for modules and utilities (if needed)
- `docs/` directory for documentation (if added)

## Development Commands

The project does not yet have build scripts or development tooling configured. As the project develops, this section should be updated with:
- How to run/test the script on Norns hardware or in maiden (Norns web editor)
- Any luarocks dependencies and installation commands
- Testing procedures

## Architecture Notes

Norns scripts are typically structured as:
- An `init()` function that runs when the script loads
- An `enc()` function for encoder input
- A `key()` function for key input
- A `redraw()` function for screen updates
- Engine integration if using SuperCollider engines

This project's specific architecture will be documented here as development progresses.

## Git Workflow

- Development branch: `claude/planning-011CUceJDXCFZGZSSHAofXZB`
- Always commit with descriptive messages
- Push using: `git push -u origin <branch-name>`
