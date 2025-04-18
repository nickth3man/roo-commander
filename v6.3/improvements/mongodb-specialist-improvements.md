# MongoDB Specialist Mode - Improvement Suggestions

## Current Role
- Specializes in designing schemas, writing queries/aggregations, managing, and optimizing MongoDB databases.
- Covers document model, CRUD, aggregation pipeline, indexing, schema validation, user management, transactions, replication, change streams, CSFLE, backup/monitoring.

## Recommended Improvements

### 1. Add Metadata Tags
- `"mongodb"`, `"database"`, `"nosql"`, `"document-database"`, `"bson"`, `"aggregation-pipeline"`, `"indexing"`, `"schema-design"`

### 2. Escalation & Delegation
- Should be **automatically invoked** when discovery detects MongoDB usage (connection strings, client library imports, `mongosh` usage).
- Should escalate:
  - **Application-level logic** interacting with MongoDB to relevant Backend/API/Framework specialists.
  - **Infrastructure/hosting issues** (e.g., Atlas configuration, self-hosted replica sets) to Infrastructure Specialist.
  - **Complex data visualization** needs based on aggregations to Data Visualization specialists.
  - **Security configuration** beyond basic user roles (e.g., network encryption, KMS for CSFLE) to Security Specialist or Infrastructure Specialist.
- Should accept escalations from **project onboarding**, **technical architect**, **API/Backend developers**, or **Database Specialist** (if MongoDB is chosen).

### 3. Collaboration
- Work closely with:
  - **API Developer** / **Backend specialists** (query needs, data access patterns)
  - **Technical Architect** (data modeling strategy)
  - **Infrastructure Specialist** (deployment, backups, scaling)
  - **Security Specialist** (RBAC, encryption, CSFLE)
  - **Performance Optimizer** (query/index tuning)

### 4. Role Clarification
- Emphasize expertise in **document modeling** (embedding vs. referencing).
- Cover the **Aggregation Framework** in detail.
- Detail knowledge of **indexing strategies** (single-field, compound, geospatial, text).
- Include **schema validation** using `$jsonSchema`.
- Clarify **transaction** usage and requirements (replica sets).
- Explain **Change Streams** for real-time updates.
- Cover **Client-Side Field Level Encryption (CSFLE)** concepts.

### 5. Additional Capabilities
- Support different **MongoDB versions** and Atlas features.
- Handle **performance tuning** using `explain()` and index optimization.
- Implement **sharding** strategies (or escalate to Infra).
- Provide guidance on choosing appropriate **read/write concerns**.
- Maintain a **knowledge base** of MongoDB schema patterns, query optimizations, and common pitfalls.

---

*Generated by Roo Commander, 2025-09-04*