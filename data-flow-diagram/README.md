# Data Flow Diagram Documentation

## Overview
This directory contains the Data Flow Diagram (DFD) for the Airbnb Clone backend system. The DFD illustrates how data moves through the system, showing processes, data stores, external entities, and data flows.

## Contents
- `data-flow.png` - Level 1 Data Flow Diagram
- `data-flow-detailed.md` - Detailed explanation of data flows and processes

## DFD Components

### External Entities:
1. **Guest** - User looking to book accommodations
2. **Host** - User listing and managing properties
3. **Admin** - System administrator
4. **Payment Gateway** - External payment processor (Stripe/PayPal)

### Key Processes:
1. User Authentication & Management
2. Property Management
3. Booking Management
4. Payment Processing
5. Review System
6. Messaging System

### Data Stores:
1. Users Database
2. Properties Database
3. Bookings Database
4. Payments Database
5. Reviews Database
6. Messages Database

## Purpose
The DFD helps:
- Understand data movement through the system
- Identify potential data bottlenecks
- Design database relationships
- Plan API endpoints and data validation
- Ensure data security and integrity