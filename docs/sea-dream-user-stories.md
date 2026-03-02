# Sea Dream Beach Guest House — User Stories

## Epic 1: Home Page Experience

### US-01: View Hero Section
**As a** visitor  
**I want to** see an attractive hero banner  
**So that** I can quickly understand the guest house offering  

**Acceptance Criteria**
- Hero image loads correctly  
- Property name is visible  
- “View Rooms” button is clickable  
- Navigation bar is visible at top  

---

### US-02: Search Room Availability
**As a** visitor  
**I want to** select check-in and check-out dates  
**So that** I can check room availability  

**Acceptance Criteria**
- User can pick check-in date  
- User can pick check-out date  
- Guest count dropdown works  
- Search button triggers availability check  
- Validation prevents invalid date range  

---

### US-03: View About Preview
**As a** visitor  
**I want to** read a short description of the guest house  
**So that** I can decide if it suits my stay  

**Acceptance Criteria**
- About text is visible  
- Rating is displayed  
- “More About” button navigates to About page  

---

### US-04: Browse Featured Room
**As a** visitor  
**I want to** see room categories on the home page  
**So that** I can quickly explore options  

**Acceptance Criteria**
- Room cards display image, name, and price  
- Each card has “Booking Now” button  
- Cards are responsive on mobile  
- Clicking navigates to room details/booking  

---

### US-05: View Facilities
**As a** visitor  
**I want to** see available facilities  
**So that** I know what amenities are provided  

**Acceptance Criteria**
- Facilities icons are visible  
- Each facility has label  
- Section is responsive  

---

### US-06: Read Testimonials
**As a** visitor  
**I want to** see guest reviews  
**So that** I can trust the property  

**Acceptance Criteria**
- Testimonial text is readable  
- Guest name and image shown  
- Slider/controls work properly  

---

## Epic 2: Rooms Page

### US-07: View Room Listings
**As a** visitor  
**I want to** browse all available rooms  
**So that** I can compare options  

**Acceptance Criteria**
- Each room shows:
  - image
  - description
  - amenities
  - price per night
- Layout matches design  
- Page loads within acceptable time  

---

### US-08: View Room Amenities
**As a** visitor  
**I want to** see room features  
**So that** I know what is included  

**Acceptance Criteria**
- Amenities icons display correctly  
- Text labels are readable  
- Missing amenities are not shown  

---

### US-09: Start Booking From Room Card
**As a** visitor  
**I want to** click “Booking Now”  
**So that** I can reserve a room  

**Acceptance Criteria**
- Button is visible on each room  
- Clicking opens booking flow  
- Selected room type is passed forward  

---

## Epic 3: About Page

### US-10: Read Full Property Information
**As a** visitor  
**I want** detailed information about the guest house  
**So that** I can build trust before booking  

**Acceptance Criteria**
- Property description visible  
- Image gallery loads  
- Room count displayed  
- Content is readable on mobile  

---

### US-11: View Core Values
**As a** visitor  
**I want** to see key selling points  
**So that** I understand why to choose this hotel  

**Acceptance Criteria**
- Value cards display correctly  
- Icons visible  
- Section responsive  

---

## Epic 4: Contact Page

### US-12: View Contact Information
**As a** visitor  
**I want** to see phone, email, and location  
**So that** I can contact the hotel easily  

**Acceptance Criteria**
- Address is visible  
- Phone number clickable on mobile  
- Email clickable  
- Social icons work  

---

### US-13: Send Message via Contact Form
**As a** visitor  
**I want** to send an inquiry  
**So that** I can ask questions before booking  

**Acceptance Criteria**
- Required fields validated  
- Email format validated  
- Form submits successfully  
- Success message displayed  
- Errors shown for invalid input  

---

### US-14: View Location on Map
**As a** visitor  
**I want** to see the property location on map  
**So that** I can understand where it is  

**Acceptance Criteria**
- Map loads correctly  
- Marker shows property location  
- Map responsive on mobile  

---

## Epic 5: Navigation & Footer

### US-15: Navigate Between Pages
**As a** visitor  
**I want** to use the top navigation  
**So that** I can move around the site easily  

**Acceptance Criteria**
- Menu links work (Home, About, Rooms, Facilities, Contact)  
- Active page is highlighted  
- Mobile menu works (hamburger if implemented)  

---

### US-16: Use Footer Links
**As a** visitor  
**I want** quick access from footer  
**So that** I can navigate or contact easily  

**Acceptance Criteria**
- Footer links work  
- Social icons clickable  
- Copyright visible  

---

## Epic 6: Online Payment Integration

### US-17: Choose Payment Method
**As a** customer  
**I want** to select a payment method during booking  
**So that** I can pay conveniently  

**Acceptance Criteria**
- Payment options are displayed (e.g., Card)  
- User can select one method  
- Selected method is highlighted  
- User cannot proceed without selecting a method  

---

### US-18: Pay for Booking Online
**As a** customer  
**I want** to pay securely online  
**So that** my room reservation is confirmed  

**Acceptance Criteria**
- Payment form loads securely (HTTPS)  
- Card details fields are validated  
- Payment gateway processes transaction  
- User sees loading state during payment  
- Booking is created only after successful payment  
- Failure message shown if payment fails  

---

### US-19: Receive Booking Confirmation
**As a** customer  
**I want** confirmation after successful payment  
**So that** I know my booking is completed  

**Acceptance Criteria**
- Success message displayed  
- Booking reference number generated  
- Confirmation email sent  
- Booking details shown on screen  

---

## Epic 7: Room Availability Calendar

### US-20: View Room Availability
**As a** visitor  
**I want** to see available dates for rooms  
**So that** I can plan my stay  

**Acceptance Criteria**
- Calendar displays correctly  
- Available dates are selectable  
- Booked dates are disabled  
- Calendar is responsive  

---

### US-21: Prevent Double Booking
**As a** system  
**I want** to block already booked dates  
**So that** two users cannot book the same room  

**Acceptance Criteria**
- System checks existing bookings  
- Overlapping dates are prevented  
- User sees message if dates unavailable  
- Database updates after booking  

---

### US-22: Filter Rooms by Date
**As a** visitor  
**I want** to search rooms by check-in/check-out  
**So that** I only see available rooms  

**Acceptance Criteria**
- Date picker works  
- Results update after search  
- Only available rooms displayed  
- Message shown if no rooms available  

---

## Epic 8: Admin Panel for Room Management

### US-23: Admin Login
**As an** admin  
**I want** to log into the admin panel  
**So that** I can manage the system  

**Acceptance Criteria**
- Admin can enter email/password  
- Credentials validated  
- Invalid login shows error  
- Successful login redirects to dashboard  
- Session is secured  

---

### US-24: Add New Room
**As an** admin  
**I want** to add new room details  
**So that** rooms appear on the website  

**Acceptance Criteria**
- Admin can enter:
  - room name
  - description
  - price
  - amenities
  - images
- Required fields validated  
- Room saved to database  
- New room appears on Rooms page  

---

### US-25: Edit Room Details
**As an** admin  
**I want** to update room information  
**So that** the website stays accurate  

**Acceptance Criteria**
- Admin can open edit form  
- Existing data is pre-filled  
- Changes save correctly  
- Updated info reflects on frontend  

---

### US-26: Delete Room
**As an** admin  
**I want** to remove a room  
**So that** unavailable rooms are not shown  

**Acceptance Criteria**
- Delete action requires confirmation  
- Room removed from database  
- Room no longer visible to users  
- Related bookings handled safely  

---

### US-27: View Bookings
**As an** admin  
**I want** to see all reservations  
**So that** I can manage guests  

**Acceptance Criteria**
- Booking list displays  
- Shows guest name, dates, room, payment status  
- List is sortable/filterable  

---

### US-28: Update Booking Status
**As an** admin  
**I want** to change booking status  
**So that** I can manage reservations  

**Acceptance Criteria**
- Admin can mark booking as:
  - confirmed
  - cancelled
  - completed
- Status updates in database  
- User is notified if required  

---

## Epic 9: User Authentication

### US-29: User Registration
**As a** new visitor  
**I want** to create an account  
**So that** I can book rooms and manage my reservations  

**Acceptance Criteria**
- Registration form includes:
  - Full name
  - Email
  - Phone number
  - Password
  - Confirm password
- All required fields validated  
- Email format validated  
- Password strength enforced (minimum length)  
- Password and confirm password must match  
- Duplicate email is prevented  
- Successful registration shows confirmation message  
- User record saved in database  

---

### US-30: Email Already Exists Validation
**As a** user  
**I want** to be warned if my email is already registered  
**So that** I can log in instead  

**Acceptance Criteria**
- System checks email uniqueness  
- Error message shown for existing email  
- User cannot complete registration with duplicate email  

---

### US-31: User Login
**As a** registered user  
**I want** to log into my account  
**So that** I can make bookings faster  

**Acceptance Criteria**
- Login form accepts email and password  
- Credentials validated against database  
- Invalid login shows error message  
- Successful login redirects to user dashboard/home  
- Session is created securely  
- Password is masked  

---

### US-32: Remember Login Session
**As a** logged-in user  
**I want** to stay logged in during my visit  
**So that** I don’t have to log in repeatedly  

**Acceptance Criteria**
- Session persists during browsing  
- User remains logged in until logout or timeout  
- Secure session handling implemented  

---

### US-33: User Logout
**As a** logged-in user  
**I want** to log out securely  
**So that** my account stays protected  

**Acceptance Criteria**
- Logout button is visible when logged in  
- Clicking logout destroys session  
- User redirected to home page  
- Protected pages require login again  

---

### US-34: View My Profile
**As a** logged-in user  
**I want** to see my account details  
**So that** I can verify my information  

**Acceptance Criteria**
- Profile page shows name, email, phone  
- Data loads from database  
- Page requires login  

---

### US-35: View My Bookings
**As a** logged-in user  
**I want** to see my booking history  
**So that** I can track my reservations  

**Acceptance Criteria**
- Booking list displays user’s reservations  
- Shows:
  - room type
  - dates
  - payment status
- Only the logged-in user’s bookings are shown  
