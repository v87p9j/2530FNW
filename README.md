java cTHE UNIVERSITY OF HUDDERSFIELD
School of Computing and Engineering
ASSIGNMENT SPECIFICATION
Module Details
Module Code NHE2530FNW
Module Title PCA, Clusters and Grids
Course Title/s BEng (Hons) Electronic Engineering and Computer Systems
Assessment Weighting, Type and Contact Details
Title Python for Parallel computing project 
Weighting 26% 
Mode of working for 
assessment task
Individual
Note: if the assessment task is to be completed on an individual 
basis there should be no collusion or collaboration whilst working on 
and subsequently submitting this assignment. 
Module Leader Dr S AMAMRA SidAli.Amamra@hud.ac.uk
Module Tutor/s Dr A FARZAMNIA
Submission Submission and Feedback Details
Hand-out date 16/09/2024
How to submit your 
work. 
Brightspace/Turnitin
Submission date/s 17/11/2024 by 12:00 noon – if you have any technical issues 
submitting your work, please contact the Module Leader as 
soon as possible.
Expected amount of 
independent time you 
should allocate to 
complete this 
assessment
30 hours
Submission type and 
format
Lab report (1500 words, doc/pdf).
2
Submission Submission and Feedback Details
Date by which your 
grade and feedback 
will be returned
16/12/2024 
Note: This is a maximum of three working weeks after the 
submission deadline. 
Additional Guidance 
Information
Details
Your responsibility It is your responsibility to read and understand the University 
regulations regarding conduct in assessment. 
Please pay special attention to the assessment regulations 
(section 10) on Academic Misconduct.
In brief: ensure that you;
1. DO NOT use the work of another student - this includes 
students from previous years and other institutions, as well 
as current students on the module.
2. DO NOT make your work available or leave insecure, for 
other students to view or use. 
3. Any examples provided by the module tutor should be 
appropriately referenced, as should examples from external 
sources. 
Further guidance can be found in the SCEN Academic Skills 
Resource and UoH Academic Integrity Resource module in 
Brightspace. 
Guidance on using AI: Level 1 – Not Permitted
The use of AI tools is not permitted in any part of this 
assessment.
School Guidance and 
Support 
If you experience difficulties with this assessment or with time
management, please speak to the module tutor/s, your 
Personal Academic Tutor, or the Student Progress Mentors. 
Student Progress Mentor – useful links.
3
Additional Guidance 
Information
Details
• Brightspace Module - SCE Student Progress Mentors 
(hud.ac.uk).
• Email - sce.progress.mentors@hud.ac.uk
Booking an appointment - http://hud.ac/rgl
Requesting a Late 
Submission 
It is expected that you complete your assessments by the 
published deadlines. However, it is recognised that there can 
be unexpected circumstances which may affect you being able 
to do so. In such circumstances, you may submit a request for 
an extension. 
Extension applications must be submitted before the published 
assessment deadline has passed. 
To apply for an extension, you should access the Extension 
System on MyHud.
Extenuating 
Circumstances (ECs)
An EC claim is appropriate in exceptional circumstances, when 
an extension is not sufficient due to the nature of the request.
You can access details on the procedure for claiming ECs, on 
the Registry website; Consideration of Personal Circumstances 
- University of Huddersfield, where you can also access the
EC Claim Form.
You will need to submit independent, verifiable evidence for 
your claim to be considered.
Once your EC claim has been reviewed you will get an EC 
outcome email from Registry. 
An approved EC will extend the submission date to the next 
assessment period (e.g July resit period).
Late Submission 
(No ECs approved)
Late submission, up to 5 working days, of the assessment 
submission deadline, will result in your grade being capped to 
a maximum of a pass mark. 
Submission after this period, without an approved extension, 
will result in a 0% grade for this assessment component.
4
Additional Guidance 
Information
Details
Tutor Referral 
available
YES
Resources • Please note: you can access free Office365 software 
and you have 500 Gb of free storage space available on 
Microsoft’s OneDrive – Guidance on downloading Office 
365.
• Python
 
5
Assignment Title 
Computer Cluster and Cloud Project
1. Assignment Aims
The aim of this assignment is to investigate parallel computing / processing using 
Python and it is based on practical laboratory work that consist of three distinct 
components:
• Test and validation of a serial Python Program to find roots of a Quadratic 
Equation.
• Parallel a serial program in the above point using Multiprocessing package 
on Python.
• Parallel a serial program in the above point using Joblib package on Python.
• Compare Multiprocessing and Joblib performance on Python to parallel 
serial programs.
2. Learning Outcomes: 
Knowledge and Understanding Outcomes
2. Examine and compare the parallel computing packages on Python, and assess their 
performance, and theoretical speed up of parallel processing applications.
Ability Outcomes
3. Deploy a parallel processing program, using Python, using environment software.
4. Evaluate different Python packages for parallel processing using appropriate 
package tools, in order to justify their applicability/non-applicability in running 
specific engineering or scientific application.
3. Assessment Brief
This is an individual assignment, assessed by individual laboratory report.
The following serial code (Fig.1) is to find the Roots of a Quadratic Equation. The 
mathematical representation of a Quadratic Equation is ax²+bx+c = 0. A Quadratic 
Equation can have two roots,代 写2530FNW、Python
代做程序编程语言 and they depend entirely upon the discriminant. 
• If discriminant > 0, then Two Distinct Real Roots exist for this equation
• If discriminant = 0, Two Equal and Real Roots exist.
6
• And if discriminant < 0, Two Distinct Complex Roots exist
The serial program 
Figure.1
Assignment objectives:
• Discuss parallel computing on Python with available different libraries?
• Please specify the difference between process and thread.
• Find out the number of your processors on your computer using the multiprocessing 
package.
• Use multiprocessing package to parallel the code in Figure-1 and record the running 
time. Hint: You may need to check out the pool.apply function.
• Use joblib package to parallel the code in Figure-1 and record the running time.
• Produce a laboratory report detailing 
a. Research on the use of Python for parallel processing.
b. Development of a code using multiprocessing package.
c. Development of a code using joblib package.
d. Performance analysis for the developed programs.
e. Benchmarking – comparison of the developed programs.
4. Marking Scheme
The assignment work will be assessed through laboratory report.
The laboratory report should have a well-defined structure similar to the following:
Organisation and content (70%)
Date, Title 
Software Used
7
1. Brief Objectives
This should state clearly what the objectives of the laboratory are. 
2. Diagrams
 Diagram or system sketches.
3. Notes on the procedure used, 
4. Programs design and test Results
a. Results obtained from these.
b. Performance comparison.
Discussion (20%)
 The discussion section may need to be completed outside the timetabled session 
as this section shows if you understand the meaning and limitation of your results. 
The contents should cover the following points where appropriate.
a) What can be learned from the results?
b) Do the simulation results agree with the theory or expected results? 
c) What are the performances between the two procedures (Packages)?
d) Could the program design be done more accurately or in a better way?
e) Is there any further work which could be done?
Conclusion (10%)
 Comments on the results obtained. A paragraph should be adequate for most 
sessions.
8
5. Grading Rubric
Grading Rubric for NHE2404 DSP Applications Assignment
This assignment grading rubric has been developed to show how the assignment will be graded, you should therefore use it to enable you to maximise your 
assignment grade in all areas. Post grading: the rubric can be used as feedback to show the aspects/areas that would be expected in any future related 
assignment, to gain a higher grade.
Awarded Grade
0 2 4 6 8 10
Lab Report: Organisation and content - weighting 70%
The title, date and 
equipment (10%)
No 
evidence 
provided
Some information on lab activities 
missing
Inconsistent record of lab 
activities
Most of the lab 
activities recorded 
and structured
All lab records 
Structured fully as given 
in the Assignment sheet
Diagrams (10%)
Layout with no obvious structure. reasonably presented
Structured with 
annotations and 
practical layout
Easy to follow 
throughout and neatly 
presented
Objectives
(10%) Few objectives stated Some relevant objectives 
stated 
Most objectives stated 
with clear purpose of 
lab activities
All objectives stated and 
demonstrating excellent 
understanding
Procedure
(10%)
Brief procedure in Python program 
design outlined with no or minimal 
accompanying information
Procedure in Python 
program design stated 
with some accompanying 
information
Procedure in Python 
program design stated 
with detailed 
information and 
reasoning 
Procedure in Python 
program design stated 
with extensive 
information and 
reasoning behind the 
steps required to 
complete it 
9
Program design using 
Multiprocessing 
(10%)
Brief information on Program design
Some information on 
program design stated 
with some accompanying 
information
Most the information 
on program design
presented with 
detailed information 
the validation
Detailed information on 
program design with 
extensive information on 
test and validation
Program design using 
joblib (10%) 
Brief information on Program design
Some information on 
program design stated 
with some accompanying 
information
Most the information 
on program design 
presented with 
detailed information 
the validation
Detailed information on 
program design with 
extensive information on 
test and validation
Results/ relevant 
images
(10%)
Inadequately presented - untidy reasonably presented Structured with 
annotations and 
practical layout
Easy to follow 
throughout and neatly 
presented
Awarded Grade
0 4 8 12 16 20
Lab Report: Discussion 20%
Discussion
(20%) No 
evidence 
provided
Brief discussion on 
outcomes of the lab 
work
Some discussion on 
outcomes of the lab 
work, with brief 
reflection on the 
experimental results
Discussion on 
outcomes of the lab 
work, with reflection on 
sources of errors in 
experimental results
Discussion on 
outcomes of the lab 
work, with 
suggestions for 
more accurate or 
better approach
Critical discussion 
supported by 
evidence and 
analysis of the 
achieved outcomes
Awarded Grade
0 2 4 6 8 10
Lab Report: Conclusion 10%
10
Conclusion
(10%) No 
evidence 
provided
Limited/inadequate conclusions – not accounting 
for achievements and or not relating to original 
Aims and Objective (AOs)
Basic conclusions 
given – related to 
original AOs
Extensive detailed 
conclusions
Extensive detailed 
conclusions with 
reference to 
possible Future 
Work

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
