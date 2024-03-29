# *SANJEEVNI*

*Sanjeevni* connects users or patients with required doctors based on specialization. Any outside 
emergency, we can do emergency booking to hospital visits and do the emergency paper work
through app and we can book the ambulance on prior to arrival. Online medicine order with
prescribed doctors’ authentication (with prescription as given by doctor).
Sanjeevni strives to provide the highest quality, most economical health care and services to our
customers and their families by utilizing best practices, highly qualified medical professionals,
and creative programs and services tailored to their specific requirements.

## SETUPING UP AND RUNNING *SANJEEVNI* ON YOUR SYSTEM
You can follow these steps to succesfully setup *Sanjeevni* in your computer:-

1. Download and extract the project into a directory of your choice</li>
  
2. Install all dependencies listed in <i>package.json</i> using <br> 
       `npm instal X`
   where X is the name of a dependency</li>

3. Seed the database using<br>
       `npm seed the database`
       
4. Start up the web application using<br>
       `npm start`
       
## SITE MAP
- Landing Page
  - Links to login and signup pages
- Login Page
  - Allows a user to log in to the site
  - To use the seed data, you may use -- username: TESTUSER password: NOTSAFE 
- Sign Up Page
  - Allows a user to create an account on the site
- Dashboard Page
  - Displays links to all the features a user can use
  - Search doctors by:
    -  Speciality
    -  Name
  - Links to:
    - Pharmacy Databank
    - User Profile
- Doctor Search Result Page
  - Allows a user to go through a list of all relevant doctors available and select one on bases of their search.
- Doctor Details Page
  - Displays all the details, ratings and reviews of the selected doctor
  - Lets the user book an appointment with the doctor
  - Lets the user leave a review for the doctor
- User Profile Page
  - Displays all information about the user
  - Allows the user to logout
- Pharmacy Databank Page
  - Displays 2 search patterns and display all button
  - Search pharmacies by: 
    -  Medicine Name
    -  ZIP CODE
  - Display all pharmacies
- All Pharmacies Page
  - Displays a list of all pharmacies stored in database
  - Allows user to click on a pharmacy to see ots details
-Pharmacy Details Page
  - Displays all details, ratings and reviews of the pharmacy including available medicines
  - Allows user to order medicines form that store
  - Allows user to leave a review for the pharmacy
  
