# RBAC-Implementation
# RBAC Implementation Assignment

## Project Overview
This project demonstrates a basic Role-Based Access Control (RBAC) system using Python. It manages user permissions by assigning users to specific roles (Admin, Editor, Viewer).

## How it Works
1. **Admin:** Full access (Read, Write, Delete, Manage Users).
2. **Editor:** Limited access (Read, Write).
3. **Viewer:** Minimal access (Read only).

## Test Results
When the script is executed, it produces the following output:
- alice (admin) -> can delete: Access Granted
- bob (editor) -> can write: Access Granted
- bob (editor) -> can delete: Access Denied
- charlie (viewer) -> can write: Access Denied
