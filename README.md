# Collection Management Platform with Image-Based Identification

A full-stack web application for managing and tracking collectible items across multiple domains, with support for search, valuation, authentication, and image-based identification.

The system is designed to provide a centralized platform for collectors to organize collections, track value over time, and share wishlists, while integrating AI-driven workflows for item identification.

## Overview

This application enables users to build and manage collections of physical items such as trading cards and other collectibles. It supports both manual search and image-based scanning to identify items and retrieve structured data.

Users can create accounts, manage personal collections, and share wishlists with others. The platform provides valuation insights at both the item and collection level.

## Core Functionality

- Authenticated user accounts and session management  
- Collection management across multiple categories of collectibles  
- Item identification via search and image-based scanning  
- Real-time display of item-level and collection-level value  
- Wishlist creation with shareable links  
- External linking to item listings and pricing references  

## Features

- View other users' collections or keep them private  
- Messaging between users for buying or trading collectibles  
- Group-based communities centered around specific collectible categories  
- Storefront capability for listing items for sale  
- Search across large aggregated datasets of collectible items  
- Image-based scanning using OCR to extract identifying information  
- Matching pipeline to resolve scanned data to known items  
- Collection tracking tied to authenticated user accounts  
- Automatic valuation display for individual items and total collections  
- Wishlist system with shareable views and external reference links  
- Responsive interface designed for both desktop and mobile usage  

## Architecture

### Frontend
- React application with component-driven architecture  
- Client-side state management and API integration  

### Backend and Data
- Supabase for data storage, authentication, and backend services  
- Structured querying for efficient lookup and retrieval  

### AI Integration
- OCR and image recognition pipeline for extracting item identifiers  
- Query normalization and matching against stored datasets  

### Deployment
- Frontend hosted on Vercel  
- Backend services managed through Supabase  

## Demo

Video walkthrough (desktop and mobile, including authentication and scanning workflow):  
[INSERT VIDEO LINK]

Live application:  
[INSERT LIVE LINK]

## Screenshots

### Desktop

| Home | Login | Dashboard |
|------|------|----------|
| <img src="https://github.com/user-attachments/assets/3f09a516-ee05-4019-b1b6-8e94e62c79d7" width="300"/> | <img src="https://github.com/user-attachments/assets/a4417429-ac73-4e3a-9937-690786a93e00" width="300"/> | <img src="https://github.com/user-attachments/assets/2ccd1d6a-ab17-432e-958d-7bf06decfccf" width="300"/> |

| Dashboard Edit | Add Collectible | Search |
|---------------|----------------|--------|
| <img src="https://github.com/user-attachments/assets/00a5c463-1695-4fa7-92da-5fc32a7f631c" width="300"/> | <img src="https://github.com/user-attachments/assets/68f1fe79-7867-4161-90dd-56f5a884dc92" width="300"/> | <img src="https://github.com/user-attachments/assets/356d33fb-1b7d-44f6-81ed-63f005c34a4c" width="300"/> |

| Edit Collectible | Edit Collections | Profile |
|------------------|------------------|---------|
| <img src="https://github.com/user-attachments/assets/6ad89925-344a-4554-aca5-c655bc986c6d" width="300"/> | <img src="https://github.com/user-attachments/assets/f5c5b160-573d-4ce3-87d6-04a2e8313de9" width="300"/> | <img src="https://github.com/user-attachments/assets/b1705fdb-56e4-4163-894a-e0a0e7e847a3" width="300"/> |

### Mobile Scanning

| Dashboard | AI Scan | Results |
|----------|--------|--------|
| <img src="https://github.com/user-attachments/assets/464f92df-800d-41cb-aeba-09ffa4ef0be0" width="220"/> | <img src="https://github.com/user-attachments/assets/c3d30b2c-ce86-42be-97e2-1c3b30e7ad73" width="220"/> | <img src="https://github.com/user-attachments/assets/1d34feb2-b374-4a56-a22a-7b3be62b84f4" width="220"/> |

## Design Considerations

- Built to support authenticated, user-specific collections and data  
- Designed for mobile-first workflows when scanning physical items  
- Focused on minimizing friction between identification, tracking, and valuation  
- Structured to support multiple collectible domains beyond trading cards  
- Separation of concerns between UI, authentication, data access, and recognition pipeline  

## Notes

This repository is a public-facing overview of the project. Core implementation details, backend logic, and data structures are not included.

## Contact

For questions or discussion, feel free to reach out.
