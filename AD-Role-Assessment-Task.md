# Advanced Delivery Role - Technical Assessment Task

**Format:** Take-home assignment  
**Objective:** Evaluate candidate's ability to handle end-to-end delivery with technical depth and architectural thinking

---

## Scenario

You are the Advanced Delivery engineer assigned to a **National Emergency Response System** project for a government agency. The system needs to:

- Track emergency incidents in real-time across the country
- Display incidents on an interactive map
- **Calculate optimal routes for responders to reach incidents**
- **Show service areas (isochrones) for emergency response coverage**
- Allow field responders to update incident status via mobile devices
- Integrate with existing legacy dispatch system (SOAP API)
- Support 10,000+ concurrent users during peak emergencies
- Provide real-time notifications to command centers

---

## Part 1: System Architecture & Design

### Task
Design the technical architecture for this system. Provide:

1. **Architecture Diagram**
   - Create a system architecture diagram showing all components
   - Include: frontend, backend, database, GIS services, integrations, caching, real-time communication
   - Show data flow between components

2. **Technology Stack Justification**
   - List your chosen technologies for each component
   - Justify why you selected each technology
   - Explain how they address the requirements (real-time, scalability, GIS)

3. **Scalability Strategy**
   - How will you handle 10,000+ concurrent users?
   - What caching strategy will you implement?
   - How will you ensure high availability?

### Deliverables
- Architecture diagram (any format: draw.io, Mermaid, hand-drawn and scanned)
- Technology stack document (Markdown)
- Scalability strategy document (Markdown)

---

## Part 2: Database Design

### Task
Design the database schema for the emergency incident system.

**Requirements:**
- Store incidents with location (latitude/longitude)
- Track incident status changes over time
- Support spatial queries (find incidents within radius)
- **Store road network data for routing**
- **Support network topology for shortest path calculations**
- Link incidents to assigned responders
- Store incident types and priorities

### Deliverables
Provide:

1. **Database Schema**
   - SQL CREATE TABLE statements for PostgreSQL with PostGIS and pgRouting
   - Include all necessary tables, columns, data types
   - Define primary keys, foreign keys, and indexes
   - Add spatial indexes for location-based queries
   - **Include road network schema with topology**

2. **Sample Queries**
   - Write 4 SQL queries:
     1. Find all active incidents within 5km of a given point
     2. Get incident history with status changes for a specific incident
     3. List top 10 responders by number of resolved incidents
     4. **Calculate shortest route from responder location to incident using pgRouting**

---

## Part 3: API Design

### Task
Design the REST API for the emergency incident system.

### Deliverables
Provide an **OpenAPI/Swagger specification** (YAML or JSON) that includes:

1. **Core Endpoints:**
   - `POST /api/incidents` - Create new incident
   - `GET /api/incidents` - List incidents (with filtering and pagination)
   - `GET /api/incidents/{id}` - Get incident details
   - `PATCH /api/incidents/{id}/status` - Update incident status
   - `GET /api/incidents/nearby` - Find incidents near location
   - **`GET /api/routing/shortest-path` - Calculate optimal route to incident**
   - **`GET /api/routing/service-area` - Calculate response coverage area**

2. **For Each Endpoint:**
   - Request/response schemas
   - Query parameters
   - Authentication requirements
   - Error responses

3. **Real-Time Events:**
   - Describe how you'll implement real-time incident updates
   - What WebSocket events will you emit?
   - How will clients subscribe to updates?

---

## Part 4: Integration Challenge

### Task
The legacy dispatch system provides a SOAP API to retrieve dispatch records. You need to integrate it with your modern REST API.

**Legacy SOAP Endpoint:**
```xml
<soapenv:Envelope>
  <soapenv:Body>
    <GetDispatchRecords>
      <StartDate>2024-01-01</StartDate>
      <EndDate>2024-01-31</EndDate>
    </GetDispatchRecords>
  </soapenv:Body>
</soapenv:Envelope>
```

### Deliverables

1. **Integration Architecture**
   - How will you integrate the SOAP API with your system?
   - Will you use a middleware/adapter pattern?
   - How will you handle data transformation?

2. **Code Sample**
   - Write pseudocode or actual code (Node.js or Java) for:
     - Calling the SOAP API
     - Transforming SOAP response to JSON
     - Exposing it via your REST API

3. **Error Handling**
   - How will you handle SOAP API failures?
   - What retry strategy will you implement?
   - How will you monitor integration health?

---

## Part 5: Deployment & DevOps

### Task
Design the deployment strategy for this system.

### Deliverables

1. **Docker Compose Configuration**
   - Write a `docker-compose.yml` file that includes:
     - Backend service (Node.js or Java)
     - PostgreSQL with PostGIS
     - GeoServer
     - Redis (for caching)
     - Any other necessary services

2. **CI/CD Pipeline**
   - Describe your GitLab CI/CD pipeline stages
   - What tests will run in the pipeline?
   - How will you handle database migrations?
   - What is your deployment strategy? (blue/green, rolling, etc.)

3. **Monitoring Strategy**
   - What metrics will you monitor?
   - How will you implement logging?
   - What alerts will you set up?

---

## Part 6: Workflow Automation

### Task
Design a workflow for incident escalation using Camunda.

**Business Process:**
1. New incident created
2. Auto-assign to nearest available responder
3. If not acknowledged within 5 minutes → escalate to supervisor
4. If not resolved within 30 minutes → escalate to regional command
5. When resolved → notify command center and close incident

### Deliverables

1. **BPMN Diagram**
   - Create a BPMN 2.0 process diagram for the escalation workflow
   - Include: start event, service tasks, timer events, gateways, end event
   - Label all tasks clearly

2. **Service Task Implementation**
   - Describe how you'll implement the "Auto-assign responder" service task
   - What API will it call?
   - How will you handle failures?

---

## Part 7: Problem Solving & Trade-offs

### Task
Answer the following questions:

1. **Performance vs. Consistency**
   - The system needs to show incident counts on a dashboard. Would you prioritize real-time accuracy or performance? Why?
   - How would you implement this?

2. **Security Consideration**
   - Field responders use mobile devices on public networks. How will you secure the API?
   - What authentication mechanism will you use?

3. **Data Retention**
   - The agency wants to keep incident data for 10 years for analysis. How will you handle database growth?
   - What archival strategy would you recommend?

---

## Evaluation Criteria

### Technical Depth (40%)
- ✅ Correct use of technologies (PostgreSQL/PostGIS, GeoServer, WebSockets, etc.)
- ✅ Proper database schema design with spatial indexes
- ✅ RESTful API design best practices
- ✅ Understanding of integration patterns

### Architectural Thinking (30%)
- ✅ Scalability and high availability considerations
- ✅ Appropriate use of caching and real-time communication
- ✅ Clear separation of concerns
- ✅ Consideration of trade-offs

### DevOps & Deployment (15%)
- ✅ Practical Docker Compose configuration
- ✅ Realistic CI/CD pipeline
- ✅ Monitoring and observability strategy

### Problem Solving (15%)
- ✅ Thoughtful answers to trade-off questions
- ✅ Practical solutions to real-world challenges
- ✅ Security awareness

---

## Submission Instructions

1. Create a ZIP file or GitHub repository containing:
   - All architecture diagrams
   - All Markdown documents
   - Code samples
   - Docker Compose file
   - BPMN diagram
   - OpenAPI specification

2. Include a `README.md` with:
   - Overview of your solution
   - Instructions to run Docker Compose setup (if applicable)
   - Any assumptions you made
   - Time spent on each part

3. Submit via email or share GitHub repository link

---

## Notes for Candidates

- **Use the AD Career Guide** as reference for required technologies
- **Focus on depth over breadth** - it's better to do fewer parts well than all parts superficially
- **Document your assumptions** - if requirements are unclear, state your assumptions
- **Show your thinking** - explain your reasoning, not just the solution
- **Real-world experience** - if you've faced similar challenges, mention them

**Good luck!** This assessment simulates the type of work you'll do as an Advanced Delivery engineer.
