# Bajaj Finserv Health Hiring Solution

Spring Boot application that automatically solves the Bajaj Finserv Health hiring challenge.

## Problem Statement

Build a Spring Boot app that:
- On startup, sends a POST request to generate a webhook
- Based on the response, solves a SQL problem and stores the result
- Sends the solution (final SQL query) to the returned webhook URL using JWT token

## Features

- Automatic execution on startup
- REST API integration using RestTemplate and WebClient
- JWT token handling
- SQL problem solving based on registration number

## Tech Stack

- Java 11
- Spring Boot 2.7.0
- Maven
- RestTemplate & WebClient
- JJWT for JWT handling

## Setup & Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/bajaj-finserv-hiring-solution.git
   cd bajaj-finserv-hiring-solution