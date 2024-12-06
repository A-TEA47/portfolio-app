Instructions
Overview
This project involves creating a personal portfolio page using the skills you've acquired throughout the course. The portfolio will serve as a showcase of your work, implemented as a single-page application with the following sections:

Header: Includes external links to your social media accounts and internal links to page sections.
Landing Section: Features an avatar, a brief bio, and a welcome message.
Projects Section: Displays featured projects using card components in a grid layout.
Contact Me Section: Contains a form for visitors to get in touch with you.
You'll also explore and implement popular open-source libraries to create a polished and professional portfolio.

Libraries
Chakra UI
Chakra UI comes pre-configured in this project. Components needed for implementation are pre-imported from the @chakra-ui/react package. For additional components and props, refer to the official documentation.

Formik and Yup
Formik is used for form handling, specifically the useFormik hook, while Yup is used for form validation. The Contact Me form's UI will be built using Chakra UI components.

Getting Started
Run the app using npm start to view the initial structure.
Install required dependencies with npm install in the terminal to ensure all libraries are ready for use.
The starter app includes a header, three sections with placeholder content, and a footer. The Contact Me section has a basic form layout.

Implementation Steps
Step 1: Header
Add external social media links using the socials array provided. Utilize the HStack component for horizontal stacking and the FontAwesomeIcon component for icons.
Add internal navigation links for the Projects and Contact Me sections. Use smooth scrolling for navigation, implementing the pre-defined handleClick function.
Step 2: Landing Section
Populate the landing section with an avatar, a greeting, and a brief role description. Use the variables (greeting, bio1, bio2) provided for the content and https://i.pravatar.cc/150?img=7 for the avatar image.
Step 3: Projects Section
Complete the Card component to display project details using Chakra UI components like HStack, VStack, Image, Heading, and Text. Add a right-arrow icon for navigation using FontAwesomeIcon.
Step 4: Contact Me Section
Configure useFormik for form handling with initialValues, onSubmit, and validationSchema.
Set up form validation rules using Yup:
Name: Required.
Email: Required and must be valid.
Comment: Required with a minimum of 25 characters.
Display validation errors using Chakra UI’s FormErrorMessage.
Implement submission logic with the provided useSubmit hook, including success/error alerts and form reset.
Step 5: Bonus (Header Animation)
Add a show/hide animation for the header based on scroll direction. Use useEffect and useRef hooks to listen to scroll events and adjust the transform property of the header's Box element.
Screenshots
Refer to the /screenshots directory for visual references:

Initial App Layout
Header with Links
Landing Section UI
Projects Section Cards
Contact Me Form with Validation
Header Animation

