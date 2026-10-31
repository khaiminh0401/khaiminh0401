# Engineering case studies

[Back to profile](README.md)

The extended studies are available in my [engineering portfolio](https://github.com/khaiminh0401/engineering-portfolio). All three remain drafts where professional implementation details and measurements have not yet been supplied.

| Study | Confirmed professional scope | Public evidence and limits |
|---|---|---|
| [Backend API performance](https://github.com/khaiminh0401/engineering-portfolio/blob/main/case-studies/backend-api-performance.md) | API optimization, bottleneck investigation and unexpected traffic spikes at VNPT | FlowDesk has [PostgreSQL integration tests](https://github.com/khaiminh0401/flowdesk/blob/d4b7895e4722e565c32b62d2ee162f610e5bc59e/apps/api/src/test/java/io/flowdesk/FoundationIT.java); it has no demonstrated high-throughput workload or benchmark results. |
| [Angular rendering performance](https://github.com/khaiminh0401/engineering-portfolio/blob/main/case-studies/angular-rendering-performance.md) | Frontend architecture and rendering improvements at VNPT | FlowDesk has [lazy routing](https://github.com/khaiminh0401/flowdesk/blob/d4b7895e4722e565c32b62d2ee162f610e5bc59e/apps/web/src/app/app.routes.ts) and [explicit connection states](https://github.com/khaiminh0401/flowdesk/blob/d4b7895e4722e565c32b62d2ee162f610e5bc59e/apps/web/src/app/features/dashboard/system-status.component.ts); no measured rendering improvement or SSR implementation is claimed. |
| [Production LLM integration](https://github.com/khaiminh0401/engineering-portfolio/blob/main/case-studies/llm-application-integration.md) | Content generation and context-aware application workflows at VNPT | No LLM runtime was found in FlowDesk. The extended study presents a proposed safe integration, not a reconstruction of undisclosed production architecture. |

Public code supports the limited behaviors above. It does not independently verify employer-specific outcomes. Each extended draft uses ten sections covering context, problem, constraints, reasoning, options, approach, implementation, trade-offs, validation and lessons.
