# Course Enrollment

Create/view/search/update/drop course enrollments.
# Student Account Management + Home/Landing Page

Student registration, list/search, edit and delete. Home page/landing page ownership is also assigned to Member 1. The original UI files are copied unchanged for reference.
# Course Details Management

Add, view/search, update and delete courses.
# Course Feedback / Reviews

The existing project stores feedback/support in Tickets (subject, message, status, reply). Map feedback comments and review handling here; do not rename endpoints without coordinating the team.
# Homework / Assignments

The existing project models lessons/assignment instructions with the Lesson module. Map this module to the assignment tasks described in the PDF.

## Files in this member folder
These are reference copies of the corresponding files from the complete working IntelliJ project. Keep Java package names (`com.learnhub...`) unchanged when merging changes.

- `entity/Enrollment.java`
- `controller/EnrollmentController.java`
- `repository/EnrollmentRepository.java`
- `service/EnrollmentService.java`
- `dto/EnrollmentDto.java`
- `entity/Customer.java`
- `controller/CustomerController.java`
- `repository/CustomerRepository.java`
- `service/CustomerService.java`
- `dto/CustomerDto.java`

## Home page UI files (original copies; unchanged)
- `home-page-ui/index.html`
- `home-page-ui/app.js`
- `home-page-ui/main.css`
- `entity/Course.java`
- `controller/CourseController.java`
- `repository/CourseRepository.java`
- `service/CourseService.java`
- `dto/CourseDto.java`
- `entity/Ticket.java`
- `controller/TicketController.java`
- `repository/TicketRepository.java`
- `service/TicketService.java`
- `dto/TicketDto.java`
- `entity/Lesson.java`
- `controller/LessonController.java`
- `repository/LessonRepository.java`
- `service/LessonService.java`
- `dto/LessonDto.java`

## Git workflow
Create a branch such as `member-1-student-home`, commit only your work, then push and open a Pull Request. The full app remains integrated in `../..` at `LearnHub-IntelliJ-Project`; these folders are split/reference copies, not six separately runnable Spring Boot apps.
