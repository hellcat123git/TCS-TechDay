# Database Schema

## Overview
Defines the core data entities and their relationships.

## Tables / Collections

### Users
- `id` (UUID, Primary Key)
- `email` (String, Unique)
- `created_at` (Timestamp)

### [Entity Name]
- `id` (UUID, Primary Key)
- `user_id` (UUID, Foreign Key)

## Related Context
- Backs the architecture defined in: [[System Architecture]]
- Used by endpoints in: [[API Endpoints]]
