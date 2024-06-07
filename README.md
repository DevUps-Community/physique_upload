# Image Upload Physique Checking Mini Project

## Objective
Allow users to upload images for physique checking and progress tracking.

## Features to Implement
1. **User Registration and Login:**
   - Create user accounts with registration and authentication.
2. **Image Upload:**
   - Enable users to upload images of their physique.
3. **Physique Comparison:**
   - Allow users to compare images over time to track progress.

## Description
This project aims to allow users to upload images for physique checking and progress tracking.

**Aspects to Consider:**

- **Schema Design:**
  - Plan how to store user-uploaded images, including metadata like upload date and user association.
  - Consider storage solutions like Supabase Storage for handling image files.

- **React App Design:**
  - Design components for image upload, viewing uploaded images, and comparing images over time.
  - Ensure efficient image loading and display.

- **Best Practices:**
  - Ensure image security and privacy.
  - Implement features for easy comparison and progress tracking.
  - Focus on performance optimisation for image handling and storage.

## Technical Requirements
- **Backend:** Node.js with Express
- **Database:** Supabase
- **Frontend:** React
- **File Storage:** Supabase Storage or similar

## Steps to Build
1. **Set up the project:**
   - Initialise a new Node.js project.
   - Set up Supabase and connect it to the project.
2. **Authentication:**
   - Implement user registration and login with Supabase Auth.
3. **Image Upload API:**
   - Create endpoints to upload and fetch images.
4. **Frontend:**
   - Build React components for registration, login, and image upload.
   - Implement image comparison functionality.
