                                                                                                           │
│     1 # Simple SIEM with Elasticsearch                                                                     │
│     2                                                                                                      │
│     3 This project sets up a simple Security Information and Event Management (SIEM) system using the      │
│       Elastic Stack (Elasticsearch and Kibana). It's a starting point for building a more comprehensive    │
│       SIEM solution.                                                                                       │
│     4                                                                                                      │
│     5 ## Components                                                                                        │
│     6                                                                                                      │
│     7 *   **Elasticsearch**: A distributed, RESTful search and analytics engine that stores and indexes    │
│       the security data.                                                                                   │
│     8 *   **Kibana**: A web-based user interface for visualizing and analyzing the data in Elasticsearch.  │
│     9                                                                                                      │
│    10 ## Getting Started                                                                                   │
│    11                                                                                                      │
│    12 To get started, you will need to have Docker and Docker Compose installed.                           │
│    13                                                                                                      │
│    14 1.  Clone this repository.                                                                           │
│    15 2.  Run `docker compose up -d` to start the Elasticsearch and Kibana containers.                     │
│    16 3.  Access Kibana at `http://localhost:5601` in your web browser.            
