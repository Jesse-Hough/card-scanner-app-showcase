# Collection Management Platform with Image-Based Identification

A full-stack web application for managing and tracking collectible items across multiple domains, with support for search, valuation, authentication, and image-based identification.

The system is designed to support collectors by providing a centralized way to organize collections, track value over time, and share wishlists, while integrating AI-driven workflows for item identification.

## Overview

This application enables users to build and manage collections of physical items such as trading cards and other collectibles. It supports both manual search and image-based scanning to identify items and retrieve structured data.

Users can create accounts, manage personal collections, and share wishlists with others. The platform also provides valuation insights at both the item and collection level.

## Core Functionality

- Authenticated user accounts and session management
- Collection management across multiple categories of collectibles
- Item identification via search and image-based scanning
- Real-time display of item-level and collection-level value
- Wishlist creation with shareable links
- External linking to item listings and pricing references

## Features

- Search across large aggregated datasets of collectible items
- Image-based scanning using OCR to extract identifying information
- Matching pipeline to resolve scanned data to known items
- Collection tracking tied to authenticated user accounts
- Automatic valuation display for individual items and total collections
- Wishlist system with shareable views and external reference links
- Responsive interface designed for both desktop and mobile usage

## Architecture

Frontend
- React-based application with component-driven design
- Client-side state management and API integration

Backend and Data
- Supabase for data storage, authentication, and backend services
- Structured querying for efficient lookup and retrieval

AI Integration
- OCR and image recognition pipeline for extracting item identifiers
- Query normalization and matching against stored datasets

Deployment
- Frontend hosted on Vercel
- Backend services managed through Supabase

## Demo

Video walkthrough (desktop and mobile, including authentication and scanning workflow):
[INSERT VIDEO LINK]

Live application:
[INSERT LIVE LINK]

## Screenshots

Desktop

Home Page
<img width="2547" height="1254" alt="image" src="https://github.com/user-attachments/assets/3f09a516-ee05-4019-b1b6-8e94e62c79d7" />

Login Page
<img width="2556" height="1260" alt="image" src="https://github.com/user-attachments/assets/a4417429-ac73-4e3a-9937-690786a93e00" />

Dashboard
<img width="2547" height="1267" alt="image" src="https://github.com/user-attachments/assets/2ccd1d6a-ab17-432e-958d-7bf06decfccf" />

Dashboard Edit Enabled
<img width="2549" height="1264" alt="image" src="https://github.com/user-attachments/assets/00a5c463-1695-4fa7-92da-5fc32a7f631c" />

Add Collectible Page
<img width="2557" height="1246" alt="image" src="https://github.com/user-attachments/assets/68f1fe79-7867-4161-90dd-56f5a884dc92" />

Search Collectible Page
<img width="2554" height="1261" alt="image" src="https://github.com/user-attachments/assets/356d33fb-1b7d-44f6-81ed-63f005c34a4c" />

Edit Collectible Page
<img width="2554" height="1263" alt="image" src="https://github.com/user-attachments/assets/6ad89925-344a-4554-aca5-c655bc986c6d" />



Mobile scanning
![Mobile](./screenshots/mobile.png)

## Design Considerations

- Built to support authenticated, user-specific data and collections
- Designed for mobile-first workflows when scanning physical items
- Focused on minimizing friction between identification, tracking, and valuation
- Structured to support multiple collectible domains beyond trading cards
- Separation of concerns between UI, authentication, data access, and recognition pipeline

## Notes

This repository is a public-facing overview of the project. Core implementation details, backend logic, and data structures are not included.

## Contact

For questions or discussion, feel free to reach out.
