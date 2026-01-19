# 🚀 Lambda – Serverless Function Execution Platform

## Overview
This project implements a **serverless function execution platform** inspired by AWS Lambda. It allows users to deploy and execute functions on-demand through HTTP APIs while enforcing execution constraints such as timeouts and resource usage limits.

The platform supports **Python and JavaScript** functions and integrates **multiple virtualization technologies** to evaluate performance, scalability, and efficiency. A web-based dashboard provides real-time visibility into function execution metrics.

---

## Key Features
- On-demand function execution via HTTP requests  
- Support for Python and JavaScript functions  
- Execution constraints (timeouts and resource limits)  
- Docker-based function execution  
- Secondary virtualization support (Firecracker MicroVMs, Nanos Unikernel, or gVisor)  
- Warm-start mechanisms and container pooling  
- Execution metrics collection (response time, errors, resource usage)  
- Web-based monitoring and management dashboard  

---

## System Components
- **Backend API**  
  Handles function deployment, metadata storage, execution routing, logging, and error handling.

- **Execution Engine**  
  Executes functions inside isolated environments using multiple virtualization technologies and enforces execution constraints.

- **Metrics & Monitoring**  
  Collects and aggregates execution metrics to monitor performance and reliability.

- **Frontend Dashboard**  
  Provides interfaces for function deployment, management, and real-time performance monitoring.

---

## Project Milestones

### Week 1 – Core Infrastructure
- Project architecture and system design  
- Backend API setup  
- Docker-based execution engine  
- Basic working prototype  

### Week 2 – Enhanced Execution
- Improved routing, warm-up, and error handling  
- Integration of a second virtualization technology  
- Metrics collection and performance comparison  

### Week 3 – Frontend & Integration
- Frontend application for function management  
- Monitoring dashboard implementation  
- End-to-end integration, testing, and optimization  

---

## Optional Enhancements
- Auto-scaling based on request load  
- Environment variable support for functions  
- Cost analysis across virtualization technologies  
- Support for additional programming languages  
