READ ME
=========

The exit interview service asses users (organizational staff members) in conducting and monitoring exit interviews with staff that have resigned from the organizations. Users will have their own accounts and will use a web-based survey form to ask the interview questions and enter data gathered from respondents over the telephone. Because users may not be able to reach the interview respondents on the first call attempt, they will be able to log contacts in the system, view surveys they have completed and review results of surveys. 

Resources that are part of the system include: 

- Users - a list of users of the system
- Respodents - a list of recently resigned staff who respond to survesy
- Contacts -a list contacts made by users to respondents
- Surveys - a list of surveys completed by users with respondents
- Results - a list of responses provided by survey respondents

id attribute values:
-
- *users* - Applied to a div tag. A list of users
- *UID* - Applied to a FORM tag. A form for creating a user
- *respondents* -   Applied to a div tag. A a list of respondents
- *RID* - Applied to a FORM tag. A form for creating a respondent
- *contacts* -  Applied to a div tag. A list of contacts
- *contactID* - Applied to a FORM tag. A form used to add contacts
- *surveys* -  Applied to a div tag. A list of surveys
- *surveyID* - Applied to a FORM tag. A form used to display survey questions and enter responses
- *results* - Applied to a div tag. A list of survey results
- *resultID* - Applied to a FORM tag. A form used to display a survey result for a respondent.

class attribute values:
-
- *user* - Applied to a LI tag. Represents a single user
- *respondent* - Applied to a LI tag. Represents a single respondent
- *survey* - Applied to a LI tag. A survey of a single respondent
- *result* - Applied to a LI tag. A result of a single survey 
- *all* - Applied to a UL tag. A list of users, respondents, contacts, surveys or results
- *userUpdate* - Applied to a FORM tag. An update to user. Should contain these elements:
    - INPUT [text]=Uname
    - INPUT [text]=UID
    - INPUT [text]=email
    - INPUT [text]=jobtitle
- *respondentUpdate* - Applied to a FORM tag. An update to respondent should include these elements:
    - INPUT [text]=Rname
    - INPUT [text]=RID
    - INPUT [text]=Rphone
    - INPUT [text]=supervisor
- *surveyUpdate* - Applied to a FORM tag. An update to survey form.
- *contactdatetime* - Applied to a SPAN tag. Contains the date-time a contact was made.
- *interviewdatetime* - Applied to a SPAN tag. The date-time an interview was completed (survey form submitted).
- *question* - Applied to an LI tag. A single question on survey.
- *qResponse* - Applied to a FORM tag. A response to question on survey.           
- *userSearch* - Applied to a FORM tag. A link template to search all users.
- *respondentSearch* - Applied to a FORM tag. A link template to search all respondents.              - *surveySearch* - Applied to a FORM tag. A link template to search all surveys completed.
- *resultsSearch* - Applied to a FORM tag. A link template to search all survey results.                                                                                                      - 
name attribute values:
-
- *Uname* - Applied to an INPUT [text] element. The full name of a user.
- *UID* - Applied to an INPUT [text] element. The employee ID of a user.
- *password* - Applied to INPUT [password] element. The user password.
- *email* - Applied to an INPUT [email] element. The email address of a user.
- *jobtitle* - Applied to an INPUT [text] element. The Job Title of a user.
- *Rname* - Applied to an INPUT [text] element. The full name of a respondent.
- *RID* - Applied to an INPUT [text] element. The employee ID of a respondent. 
- *RPhone* - Applied to an INPUT [tel] element. The phone # of a respondent.
- *hiredatetime* - Applied to an INPUT [datetime] element. The date respondent was hired
- *termdatetime* - Applied to an INPUT [datetime] element. The date a respondent resigned.
- *Supervisor* - Applied to an INPUT [text] element. The Supervisor of a respondent.
- *SID* - Applied to an INPUT [text] element.The employee ID of a respondent's supervisor.
- *Q{num}Response* - Applied to INPUT [text] elements. This would capture responses to each question on survey form.

rel attribute values:
-
- *index* - Applied to A tag. A reference to starting URI for application
- *user* -  Applied to A tag. A reference to a user representation
- *respondent* -  Applied to A tag. A reference to a respondent representatio
- *contact* - Applied to A tag. A reference to a contact representation
- *survey* - Applied to A tag. A reference to a survey representation
- *result* -Applied to A tag. A reference to a result representation


  
    