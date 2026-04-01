---
name: bullspot-developer
description: Development workflow for Bullspot engineers - code review, GitHub workflow, debugging.
category: engineering
bullspot_agent: Frank, Nova
---

# Bullspot Developer Skill

## Tech Stack
- Railway deployment
- Supabase: vwizzzmcescljw
- OpenRouter, Anthropic

## GitHub
- Token: Use GITHUB_TOKEN environment variable (do not hardcode)
- Repo: Check Paperclip for current repo URL

## GitHub Workflow
- Branch: feature/description or fix/issue-number
- Commits: feat:, fix:, docs:, refactor:, test:
- Include issue number: feat: add feature (#BUL-123)

## Code Review Checklist
- [ ] Style guide followed
- [ ] Tests passing
- [ ] No hardcoded secrets (use env vars)
- [ ] Error handling proper
- [ ] Security scan clean

## Debugging
1. Reproduce exact error
2. Isolate failing component
3. Analyze logs/traces
4. Fix
5. Verify fix
6. Add test

## Railway
- Token: Use RAILWAY_TOKEN env var (do not hardcode)
- Check logs if deployment fails
- Rollback if critical
