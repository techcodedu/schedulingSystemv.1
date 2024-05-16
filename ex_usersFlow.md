# External Users Flow

## 1. Landing on the Homepage
- User visits the homepage.
- User sees two primary options: "Track Application" and "Book Assessment".

## 2. Selecting Book Assessment
- User clicks the "Book Assessment" button.
- Redirect to the booking assessment page.

## 3. User Registration and Verification
### Individual Registration:
- User fills out a registration form with personal details (name, email, phone number).
- User uploads a picture and a valid ID for verification.

### Group Registration:
- Representative fills out a form with their details (name, email, phone number).
- Representative indicates the number of individuals (packs).
- Representative uploads a picture and a valid ID.

## 4. Scheduling Application
- User selects the desired training or assessment program from a list.
- User chooses preferred dates from available slots.
- User submits the scheduling application.

## 5. Tracking and Notification
### Tracking Application Status:
- User receives a scheduling application number.
- User can enter this number on the website to check the status.

### Approval Notification:
- User receives an email/SMS notification upon initial approval.

### Upload Links:
- User uploads scanned application forms for each individual in the group (if group registration).
- User is notified to pay the processing fee.

## 6. Payment Management
- User views total fees and payment status on their dashboard.
- User completes secure online payment processing.

## 7. Final Approval and Schedule Viewing
- Admin verifies uploaded forms and confirms payment receipt.
- Final approval of the scheduling is granted.
- User can access a calendar link to view detailed schedule information.

## 8. Feedback and Support
- User provides feedback on training and assessment sessions.
- User accesses support for booking and payment issues.

## Booking Assessment Flow Diagram

1. **Homepage**  
   User lands on the homepage.
   - Button: "Book Assessment"

2. **Registration Page**  
   User selects to register as an individual or representative of a group.
   - Form: Personal/Representative details
   - Upload: Picture and valid ID

3. **Scheduling Page**  
   User selects the desired program and dates.
   - Dropdown: Select program
   - Calendar: Choose dates
   - Button: Submit application

4. **Tracking and Notification**
   - User receives application number.
   - Notification: Email/SMS for approval.
   - Upload: Scanned application forms (for group).
   - Notification: Payment processing.

5. **Payment Page**  
   User views and completes payment.
   - View: Total fees and payment status
   - Button: Complete payment

6. **Final Approval and Schedule Viewing**
   - Admin verification.
   - Final approval notification.
   - Link: View detailed schedule.

7. **Feedback and Support**
   - Form: Provide feedback
   - Access: Support for issues.

## Implementation Steps

1. **Create Routes and Templates for Each Step**:
   - Booking assessment page
   - Registration form
   - Scheduling application form
   - Payment page
   - Schedule viewing page
   - Feedback and support page

2. **Implement Registration Logic**:
   - Handle individual and group registration
   - Validate and upload ID

3. **Implement Scheduling Application Logic**:
   - Allow users to select programs and dates
   - Store scheduling application data

4. **Implement Tracking and Notification System**:
   - Generate and track application numbers
   - Send email/SMS notifications

5. **Implement Payment Management**:
   - Display total fees
   - Integrate secure payment gateway

6. **Admin Verification and Final Approval**:
   - Admin interface to verify documents and payments
   - Approve schedules and notify users

7. **Feedback and Support System**:
   - Allow users to provide feedback
   - Provide support for booking and payment issues
