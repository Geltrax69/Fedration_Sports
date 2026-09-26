# Federation Sports Platform — Roadmap & Status

Legend:
- [x] DONE
- [~] IN PROGRESS
- [ ] PLANNED
- [!] BLOCKED
- [-] DEFERRED

## Repository / Documentation

[x] Create platform specification
[x] Define Graphviz architecture map
[x] Define Graphviz data map
[x] Define implementation status model
[x] Document source repositories and reuse strategy

## Platform Foundation

[ ] Create monorepo/application structure
[ ] Create Go API
[ ] Create PostgreSQL migrations
[ ] Create organizations/sites/districts tables
[ ] Create tenant middleware
[ ] Create PostgreSQL RLS policies
[ ] Create authentication
[ ] Create RBAC/permissions
[ ] Create domain resolution
[ ] Create private object storage adapter
[ ] Create audit logging

## Public Website

[ ] Migrate reusable public components from IND-SepakTraw
[ ] Create shared design system
[ ] Create theme architecture
[ ] Create Royal Editorial homepage
[ ] Create Federation Classic homepage
[ ] Create Athletic Modern homepage
[ ] Create Championship homepage
[ ] Create Institutional homepage
[ ] Implement CMS
[ ] Implement news
[ ] Implement notices
[ ] Implement events
[ ] Implement results
[ ] Implement documents
[ ] Implement gallery
[ ] Implement officials
[ ] Implement compliance
[ ] Implement RTI
[ ] Implement elections
[ ] Implement anti-doping
[ ] Implement history
[ ] Implement contact pages

## Registration

[ ] Player registration
[ ] Coach registration
[ ] Referee registration
[ ] Draft save
[ ] Document upload
[ ] Upload validation
[ ] Registration submission
[ ] Review workflow
[ ] Approval workflow
[ ] Rejection workflow
[ ] Change request workflow
[ ] Member profile
[ ] Member ID generation

## Federation Admin

[ ] Dashboard
[ ] Registration queue
[ ] Player management
[ ] Coach management
[ ] Referee management
[ ] District management
[ ] Event management
[ ] Result management
[ ] CMS management
[ ] Document management
[ ] Official management

## Super Admin

[ ] Federation creation
[ ] Federation lifecycle
[ ] District creation
[ ] Administrator creation
[ ] Domain management
[ ] Theme management
[ ] Platform audit viewer

## Performance

[ ] Public/admin bundle separation
[ ] Route-level lazy loading
[ ] Responsive image pipeline
[ ] LCP optimization
[ ] Font optimization
[ ] Public aggregate API
[ ] Query optimization
[ ] Database indexes
[ ] Tenant-aware caching
[ ] CDN strategy
[ ] Performance CI checks
[ ] Real-device performance verification

## Security

[ ] Argon2id password hashing
[ ] Tenant authorization tests
[ ] RLS integration tests
[ ] File access authorization
[ ] Private storage
[ ] MIME/signature validation
[ ] Malware scanning
[ ] Rate limiting
[ ] Security headers
[ ] Audit trails
[ ] Backup/restore validation

## Graphviz

[ ] Keep docs/architecture.dot synchronized with major architecture changes
[ ] Keep docs/data-model.dot synchronized with schema changes
[ ] Render PNG/SVG diagrams in CI or as documentation artifacts

## Git Workflow

Each completed feature should:
1. include code
2. include migration changes if applicable
3. include tests
4. update documentation
5. update Graphviz when relationships change
6. update this roadmap
7. be committed with a focused commit message
