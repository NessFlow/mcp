# Tools

Generated from the live server catalogue. A connection only lists the tools its rights, plan and enabled modules allow.

| Tool | Title | Kind | Read only | Destructive | Idempotent | Open world | Scopes | From plan |
|---|---|---|---|---|---|---|---|---|
| `nessflow_whoami` | Who am I | read | yes | no | yes | no |  | Starter |
| `nessflow_operations_list` | List running operations | read | yes | no | yes | no | `projects:read` | Starter |
| `nessflow_projects_list` | List projects | read | yes | no | yes | no | `projects:read` | Starter |
| `nessflow_project_get` | Get a project | read | yes | no | yes | no | `projects:read` | Starter |
| `nessflow_project_scorecard_get` | Get the health scorecard | read | yes | no | yes | no | `projects:read` | Starter |
| `nessflow_campaigns_list` | List campaigns | read | yes | no | yes | no | `projects:read` | Starter |
| `nessflow_campaign_get` | Get a campaign | read | yes | no | yes | no | `projects:read` | Starter |
| `nessflow_crawls_list` | List crawls | read | yes | no | yes | no | `crawls:read` | Starter |
| `nessflow_crawl_get` | Get a crawl | read | yes | no | yes | no | `crawls:read` | Starter |
| `nessflow_issues_list` | List issue occurrences | read | yes | no | yes | no | `crawls:read` | Starter |
| `nessflow_issues_summary_get` | Summarise issues | read | yes | no | yes | no | `crawls:read` | Starter |
| `nessflow_pages_list` | List crawled pages | read | yes | no | yes | no | `crawls:read` | Starter |
| `nessflow_page_get` | Get a page by URL | read | yes | no | yes | no | `crawls:read` | Starter |
| `nessflow_crawl_pagespeed_get` | Read PageSpeed results | read | yes | no | yes | no | `crawls:read` | Starter |
| `nessflow_crawl_geo_get` | Read the AI-answer readiness report | read | yes | no | yes | no | `crawls:read` | Starter |
| `nessflow_crawl_accessibility_get` | Read the accessibility report | read | yes | no | yes | no | `crawls:read` | Starter |
| `nessflow_crawl_eeat_get` | Read the trust foundation report | read | yes | no | yes | no | `crawls:read` | Starter |
| `nessflow_crawl_structure_get` | Read the internal linking report | read | yes | no | yes | no | `crawls:read` | Starter |
| `nessflow_crawls_compare` | Compare two crawls | read | yes | no | yes | no | `crawls:read` | Starter |
| `nessflow_recommendations_get` | Read recommendations | read | yes | no | yes | no | `recommendations:read` | Starter |
| `nessflow_export_get` | Get an export | read | yes | no | yes | no | `crawls:read` | Starter |
| `nessflow_positions_get` | Read rank tracking | read | yes | no | yes | no | `positions:read` | Starter |
| `nessflow_search_console_get` | Read Search Console data | read | yes | no | yes | no | `search_console:read` | Starter |
| `nessflow_backlinks_get` | Read the backlink profile | read | yes | no | yes | no | `backlinks:read` | Pro |
| `nessflow_security_get` | Read security signals | read | yes | no | yes | no | `security:read` | Starter |
| `nessflow_logs_get` | Read server log analysis | read | yes | no | yes | no | `logs:read` | Starter |
| `nessflow_project_create` | Create a project | write | no | no | no | yes | `projects:write` | Pro |
| `nessflow_project_update` | Update a project | destructive | no | yes | yes | no | `projects:write` | Pro |
| `nessflow_campaign_create` | Create a campaign | write | no | no | no | no | `projects:write` | Pro |
| `nessflow_campaign_update` | Update a campaign | write | no | no | yes | no | `projects:write` | Pro |
| `nessflow_campaign_delete` | Delete a campaign | destructive | no | yes | yes | no | `projects:write` | Pro |
| `nessflow_crawl_launch` | Launch a crawl | billed | no | no | no | yes | `crawls:write` | Pro |
| `nessflow_crawl_stop` | Stop a crawl | write | no | no | yes | no | `crawls:write` | Pro |
| `nessflow_recommendations_generate` | Generate recommendations | billed | no | no | no | yes | `recommendations:write` | Pro |
| `nessflow_export_create` | Request an export | write | no | no | no | no | `exports:write` | Pro |
| `nessflow_keywords_track` | Track keywords | billed | no | no | no | yes | `positions:write` | Pro |
| `nessflow_keywords_untrack` | Stop tracking keywords | write | no | no | yes | no | `positions:write` | Pro |
| `nessflow_keywords_pause` | Pause keywords | write | no | no | yes | no | `positions:write` | Pro |
| `nessflow_keywords_resume` | Resume keywords | billed | no | no | no | yes | `positions:write` | Pro |
| `nessflow_keyword_check_now` | Check a keyword now | billed | no | no | no | yes | `positions:write` | Pro |
