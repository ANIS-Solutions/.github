 
<p align="center">
Building intelligent, privacy-first solutions that help families create a safer digital environment for children.
</p>

<p align="center">
  <a href="https://anis.solutions">Website</a>
  ·
  <a href="https://github.com/ANIS-Solutions">Organization</a>
  ·
  <a href="https://github.com/ANIS-Solutions/documentation">Documentation</a>
</p>

<br/>

## Overview

ANIS is an AI-powered parental control ecosystem that combines cloud intelligence, on-device AI, and real-time monitoring to help parents understand, protect, and support their children.

<br/>

## Technology Stack

<p align="center">
<img src="https://skillicons.dev/icons?i=flutter,nextjs,nodejs,express,mongodb,redis,kotlin,tensorflow,pytorch,docker,nginx" />
</p>

<br/>

## Architecture

```mermaid
flowchart LR

    Parent["Parent App<br/>Flutter"]
    Dashboard["Web Frontend<br/>Next.js"]

    Backend["Backend API<br/>Express.js"]
    Mongo["MongoDB"]
    Redis["Redis"]

    AIHosted["AI Hosted Services"]
    AIOnDevice["AI On-Device"]

    Child["Child App<br/>Kotlin"]

    Parent --> Backend
    Dashboard --> Backend

    Backend --> Mongo
    Backend --> Redis

    Backend --> AIHosted

    Child --> Backend
    Child --> AIOnDevice

    AIHosted --> Backend
````

## Mission

ANIS aims to create ethical, transparent, and intelligent digital parenting tools that empower families while respecting privacy and trust.

<br/>

<p align="center">
  <a href="https://anis.solutions">Website</a> •
  <a href="https://github.com/ANIS-Solutions">GitHub</a>
</p>

<p align="center">
ANIS Solutions
</p>
 
