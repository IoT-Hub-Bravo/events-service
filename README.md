# IoT Hub Events Service

Service for creating and managing user-visible events triggered by rule evaluation.

## Purpose

The events Service owns the lifecycle of user-visible events produced by rule matches.

## Responsibilities

- consume rule match events
- create events
- manage event lifecycle and status
- support event acknowledgement
- provide event history APIs
- expose event data for user interfaces

## Owned data

- events
- event status
- event history
- acknowledgement metadata

## Integrations

### Inbound
- rule match events
- frontend and internal clients

### Outbound
- events audit

## Technology

- Django
- PostgreSQL
- Docker
