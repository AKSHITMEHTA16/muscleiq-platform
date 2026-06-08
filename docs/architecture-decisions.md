# MuscleIQ System Overview

## Architecture Style
Microservices Architecture

## What is API Gateway?
API Gateway acts as the main entry point for all client requests. 
It receives requests from frontend or mobile applications and routes them to the correct microservice.

## Why Microservices?
Microservices help in:
- independent development
- better scalability
- easier deployment
- service isolation
- better maintainability

Instead of building one huge backend application, the system is divided into smaller services.

## Planned Services

### Auth Service
Handles:
- login
- signup
- JWT authentication
- user security

### User Service
Handles:
- user profile
- personal details
- account information

### Workout Service
Handles:
- workout tracking
- exercise history
- workout plans

### Recovery Service
Handles:
- pain logs
- recovery monitoring
- injury tracking

## Monolith vs Microservices

### Monolith
One large backend application where all modules are tightly connected.

### Microservices
Small independent services communicating with each other through APIs.

## Communication
REST APIs

## Database
PostgreSQL

## Containerization
Docker