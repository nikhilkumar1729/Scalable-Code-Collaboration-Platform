# Scalable-Code-Collaboration-Platform
Client (React / Next.js)
        |
API Gateway
        |
----------------------------------
| Auth Service                  |
| Repo Service                  |
| Commit Service                |
| PR Service                    |
| CI/CD Worker Service          |
----------------------------------
        |
PostgreSQL (metadata)
Object Storage (code files)
Redis (cache + queue)
Worker Nodes (CI jobs)
