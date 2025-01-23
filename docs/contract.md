Grading Contract
================
January 23 2025

<!--- How to use this Rmarkdown document
The text above this comment is the YAML header. Change the variables under "params" into what is relevant for you and your situation. In cases where there are choices, you have to choose one of those choices. Make sure you spell your parameter the same was as one of the choices and also have the same capital or small letters.
&#10;The parameters that you have specified in the YAML header will be used in the rest of the code to change out place holders.
&#10;The gray boxes are r code. Since there is a "include = FALSE" command in the header of each code block, the code itself will be ran and used to produce the rest of the document. However, the code itself will not show up when you render/knit the document.
&#10;The first code chunk sets the number of labs and portfolio projects you need, based on what grade you are writing the contract for. You should double check that this number is the same as what is currently stated in the syllabus as being the requirement for that grade. The second code chunk defines some variables we need and the list with the topics for the modules. Double-check that all the modules that are currently available are in that list. If not, feel free to change that. The third code chunk defines a function that takes in some parameters (information you give it) and turns that into a string we use in the contract, for example with the relevant module names and dates.
-->
<!--- The next part here is the text that will actually be displayed in the document. The #, ##, or ### before some text indicates that this is a header. The number of "#"'s correspond to the level of the heading. So, # Heading will be in a bigger font than ## Header.
&#10;The text that consists of "tick"r text"tick" (I can't actually write it with the ticks here, as that would have been interpreted by r as code to run) is in-line r code. It will run the r code and the output will be pasted there in the text when you render/knit the document. Any call to params$[input parameter here] calls the parameter you inputted in the YAML header. So, for example, if you put in A as a grade, the string below will produce a text stating "Terms to Get a Grade of "A"".
The r codes with the parameters should paste the value or text that you need. If it seems wrong, double-check that you put in the right parameter (e.g. didn't misspell something). 
&#10;There is also some code that calls a function called string_details. This is the function we defined (made) earlier to make the strings we need. The parameters (values) we put in the parameter when calling the function determines what we get from it.
&#10;Read over the text for the contract and change or add anything you want to change.
-->

## Terms to Get a Grade of “A”

I, Linn Zapffe, agree to :

1)  Earn “Satisfactory” on 11 self-paced lab assignments on the schedule
    specified below. Getting a grade of “Satisfactory” requires that:
    - I have attempted all steps of the assignment. If unable to  
      complete steps due to unresolved questions, I have asked questions
      in Github FAQs or during the help sessions, or I have Googled the
      issue and shown effort to resolve questions;
    - I have checked that files, repos, or projects appear on my Github
      account and are accessible;
    - I feel like I have spent an adequate amount of time and energy on
      the assignment;
2)  Produce at least 10 “Satisfactory” portfolio pieces on the schedule
    specified below. Getting a grade of “Satisfactory” requires that:
    - I have designed a portfolio project that I think challenges my
      understanding of programming, explores a topic I want to know more
      about, or targets something I feel like I need more practice with;
    - I have checked that files, repos, or projects appear on my Github
      account and are accessible;
    - I feel like I have spent an adequate amount of time and energy on
      the projects;

### Schedule

- [ ] **Module 1, 01/13 - 01/19 : Data Science**
  - [ ] Finish Lab 1 by Sunday: 01/19
- [ ] **Module 2, 01/20 - 01/26 : Data and Visualization**
  - [ ] Finish Lab 2 by Sunday: 01/26
  - [ ] Propose your contract to Mason by Sunday: 01/26
- [ ] **Module 3, 01/27 - 02/02 : Tidyverse**
  - [ ] Finish Lab 3 by Sunday: 02/02
  - [ ] Finish portfolio piece 1 by Sunday: 02/02
- [ ] **Module 4, 02/03 - 02/09 : Data Diving with Tidyverse**
  - [ ] Finish Lab 4 by Sunday: 02/09
- [ ] **Module 5, 02/10 - 02/16 : Effective Data Visualization**
  - [ ] Finish Lab 5 by Sunday: 02/16
  - [ ] Finish portfolio piece 2 by Sunday: 02/16
- [ ] **Module 6, 02/17 - 02/23 : Web scraping**
  - [ ] Finish Lab 6 by Sunday: 02/23
  - [ ] Schedule a check-in with Mason by Sunday: 02/23
- [ ] **Module 7, 02/24 - 03/02 : Functions and Automation**
  - [ ] Finish Lab 7 by Sunday: 03/02
  - [ ] Finish portfolio piece 3 by Sunday: 03/02
- [ ] **Module 8, 03/03 - 03/09 : Data and Ethics**
  - [ ] Finish Lab 8 by Sunday: 03/09
- **Spring break! - 03/10 - 03/16**
- [ ] **Module 9, 03/17 - 03/23 : Modeling the Tidy way!**
  - [ ] Finish Lab 9 by Sunday: 03/23
  - [ ] Finish portfolio piece 4 by Sunday: 03/23
- [ ] **Module 10, 03/24 - 03/30 : Overfitting and Cross-validation**
  - [ ] Finish Lab 10 by Sunday: 03/30
- [ ] **Module 11, 03/31 - 04/06 : Quantifying Uncertainty**
  - [ ] Finish Lab 11 by Sunday: 04/06
  - [ ] Finish portfolio piece 5 by Sunday: 04/06
- [ ] **Module 12, 04/07 - 04/13 : Base R and Simulating Data**
  - [ ] Finish portfolio piece 6 by Sunday: 04/13
- [ ] **Module 13, 04/14 - 04/20 : Large Language Models**
  - [ ] Finish portfolio pieces 7 and 8 by Sunday: 04/20
- [ ] **Module 14, 04/21 - 04/27 : Interactive Web Apps**
  - [ ] Finish portfolio piece 9 and 10 by Sunday: 04/27
- [ ] **Portfolio completion**
  - Due on Sunday: 04/27

## Further guidelines

- According to reasons discussed and agreed upon in advance with the
  professor, there are some situations which might require some of these
  deadlines to be moved. If this is the case, I will reach out to the
  professor and agree on another deadline. The number of assignments
  that have to be completed satisfactory will not change because of
  these reasons.
- If the professor has any concerns about the assignments and whether
  they reach the standards of being completed “satisfactory”, the
  professor will communicate these concerns with me and, if deemed
  appropriate, offer an opportunity to correct them.
- I pertain the right to, at any time, switch out any of the modules and
  labs with another module or lab in the course or change the order of
  them from what is currently specified in the contract. This will not
  affect the number of labs or modules that are to be completed
  according to the contract. Any such changes will be noted in this
  contract for reference, but will not require notifying the professor.
- Any other part of this contract can be changed before the final grade
  is set if agreed upon by both myself and the professor.

<!--- Now, I suggest that you knit the document. You can do this by pushing the "Knit" button with a blue yarn ball above this screen in Rmarkdown. To see the changes, push it to Github and look at the file there. If you feel more advanced, you can also change the output type to a html document in the YAML header. However, note that this will mess up some of the formatting, so I suggest to only do this temporarily while messing with the document and then switching back to the Github document type.
&#10;When looking at your knitted document, you will now see the standard schedule based on the dates and information you put in as parameters in the YAML header. There are a few things I suggest you look over and change as it fits you:
&#10;- There are currently mode modules than there are weeks in the semester. That means that you can't get through all the modules. If you want, you can switch out any of the modules in the contract with another module. The module is determined based on the number inputted as the third parameter in the string_details function. For example, in the following code "string_details(monday_week_one, 11, 12, modules_list)", the module number would be 12. If you are wondering what module module 12 is, you can go to the code block that defines the list "module_list" and count. Module 12 would be the topic that corresponds to the 12th topic in that list.
&#10;- In addition, there are also more labs that what is required to get an "A". You can therefore also change which labs you are doing. This is just written in the standard text (not code) in the contract, so to do that, simple remove the line with the lab you don't want and add it somewhere else, changing out the lab number. For example, if you do not want to do lab 10, delete the line stating "- [ ] Finish Lab 10 by Sunday:
03/30" and add this, switching out the lab number with another lab you want to do and any other parameteres that need to be adjusted, under the relevant module.
&#10;- You can move around when to do labs and any of the other things that have to be done. You can do this simply by copy pasting the text and code associated with it and move it around. For example, if you know that you have a busy week one week, you might want to move any portfolio project deadlines to the following week. Do for example look at when your thesis is due and see whether you want to keep the time around then more open.
&#10;- Look over when spring break is and move any assignments to other weeks (unless you want deadlines during spring break)
&#10;- As you finish assignments or modules, you can mark them with a check. The "[ ]" indicates an empty check box, while "[x]" indicates a checked box.
&#10;When you are done with the edits to the contract, you can knit it again, push it to Github, and look over it to see that everything looks good. -->
<!--- This contract is adapted from Annie Somerville's contract https://github.com/anniehsom -->
