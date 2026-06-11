# Notification System Design

## Objective

Design a notification system that allows users to receive, view, and manage notifications.

## Features

* Create notifications
* View all notifications
* Mark notifications as read
* Delete notifications

## Architecture

Frontend → Backend API → Database

## Components

### Frontend

* User interface for viewing notifications
* Create notification form

### Backend

* REST APIs for notification management
* Business logic handling

### Database

* Stores users and notifications

## API Endpoints

### Create Notification

POST /notifications

### Get All Notifications

GET /notifications

### Mark Notification as Read

PUT /notifications/:id/read

### Delete Notification

DELETE /notifications/:id

## Database Schema

### Notification

* id
* title
* message
* status
* createdAt

## Future Improvements

* Real-time notifications
* Email notifications
* Push notifications
