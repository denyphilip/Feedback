# Feedback
Description:
With help of this module, user can submit their feedback.

- Welcome page with bootrap menu with menu items - Login
- On center of the page there will be a button to submit feedback
- Manage Session for logged in user.
- Submit Feedback:Only Registered user can submit feedback after login, if not logged in then redirect to the Login URL .
- Submit Feedback have following steps.
- Step 1:
1. Are you a current or former employee? 
(Radio button with options Current, Former)
2. Employer's Name
(Text Field)
1. Overall Rating 
(Out of 5 star, user can give star rating, use feedback star UI 
Ref. https://mdbootstrap.com/docs/b4/jquery/plugins/rating/
2. Employment Status
(Drop down with options Full Time, Part Time, Contract, Intern)
3. Job Title 
(Text Field)
4. Review Headline 
(Text Field)
5. Pros
(Text Area, min 15 characters - max 200 characters)
6. Cons
(Text Area, min 15 characters - max 200 characters)
7. Advice Management
(Text Area, min 15 characters - max 200 characters)

1. Submit Proof (On submit store file in upload folder)
(File upload, allowed file type doc and pdf)
2. Agree Terms and Condition 
(checkbox).
Submit Button to submit all the steps.
On submit, Review submitted form fields.
