# 🚨 AI Emergency Safety Agent

## Overview
AI Emergency Safety Agent is a mobile AI agent built using the Droidrun framework and executed on Mobilerun Cloud AI.
The agent autonomously performs emergency actions on a mobile device when the user signals danger.

## Problem
In emergency situations, users may panic and fail to quickly:
- Share their location
- Contact emergency services

## Solution
This agent listens for a danger signal and automatically performs critical safety actions without requiring manual interaction.

## Trigger
Incoming SMS containing the text:
"I AM IN DANGER"

## Agent Actions
1. Turn ON device location (GPS)
2. Share live location using Google Maps
3. Dial emergency number (112)
4. Send confirmation message

## Agentic Behavior
The agent follows an observe → decide → act loop:
- Observes incoming SMS
- Decides whether emergency mode should be activated
- Acts autonomously across multiple mobile apps

## Platform Used
- Droidrun Framework
- Mobilerun Cloud AI
- Android Device / Emulator

## Demo
A demo video link is available in the demo folder.

## Hackathon
Built for Droidrun DevSprint 2026.
