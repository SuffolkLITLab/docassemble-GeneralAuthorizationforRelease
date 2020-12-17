# docassemble-GeneralAuthorizationforRelease
A docassemble extension.

This is an online version of a general release of information, which allows organizations to release information about a specific person to someone of their choice, whether it be their attorney or an entity representing them.

# Author
Joelle Ataya, jataya@su.suffolk.edu

<b>Who?</b><br>
    For our final class project in Coding the Law at Suffolk University Law School, we were tasked with solving a real-world issue using programs and coding languages we learned throughout the semester. The Suffolk LITLab is an experiential program combining legal services and legal tech. A big project the LITLab is working on is the Document Assembly Line Project, where court forms and *pro se* materials are automated and made more user-friendly. During the COVID-19 pandemic, everything got harder, especially obtaining legal services. With things falling apart, the Assembly Line Project was created to solve this problem of high legal demand. Collaborating with the Suffolk LITLab, my partners Kayla Gallagher, Mike Carroll and I worked on automating three release of information forms: a general release, an attorney release, and a Boston Housing release form. The users and stakeholders involved are in two groups. One group includes the Document Assembly Line project and its participants, including David Colarusso and Quinten Steenhuis. The second includes the client whose information is being released, the agency that is releasing the information, and the attorney or organization who is obtaining that information.
 
 Aside from our forms, the Assembly Line Project is producing court and *pro se* forms in multiple languages to further this program’s reach and accessibility. Because these automated forms can and should be used by the general public, my teammates and I had to ensure we had a diverse selection of user persona for testing. We had originally planned to automate an attorney release form in Spanish but after receiving feedback, refining our plan and considering the fact that none of us are fluent in Spanish, we did not have enough time to invest ourselves in translating a form. With help from our partners at the LITLab, we decided on creating an additional general release form.


<b>What?</b><br>
  COVID-19 restricted more things than not and made simple in-person tasks hard to accomplish. Even though filling out the form used to be a straightforward process normally executed during in-person meetings, COVID-19 created a problem no one saw coming. The Document Assembly Line Project is aimed at fixing this problem by allowing a user to fill out an authorization for release of information form on their laptop or phone. People can also access certain release forms online. However, these release forms are not as easy to find as one would think, for example a one-page BHA release is embedded in a 30+ page document. We were able to contact the BHA and asked them about requirements for their release form to see if we should simplify or explain it more. Our project aims to make filing a court or *pro se* form easier and more accessible to the general public. with the BHA release form, we were able to do some online research and call them to ask them some questions and gather as much information as we can to perfect our forms. With the attorney release form, there is one form Massachusetts uses, so we automated that one. Research was very important, especially for me since I was the point person, for the general agency release form. Because my team and I had to create this form from scratch, we conducted extensive research and compared numerous of different release forms to see what was required or not. Google was our friend, but so were our lead partners at the LITLab, who gave us great examples that added to our research.

My teammates and I worked on three release of information forms. Although we each worked on one specific form, we were a constant part of each others work and were able to use many of the similar source codes for all three forms.

The three release forms can be found below:<br>
  1.<a href="https://github.com/SuffolkLITLab/docassemble-AttorneyAuthorizationforRelease">Attorney Authoization for Release</a><br>
  2.<a href="https://github.com/SuffolkLITLab/docassemble-BHAReleaseAuthorization">Boston Housing Authority Release</a><br>
  3.<a href="https://github.com/SuffolkLITLab/docassemble-GeneralAuthorizationforRelease">General Release</a><br>


<b>When? Where?</b><br>
    The beauty of our work with the Assembly Line Project is that it now allows people to file court and *pro se* forms from virtually anywhere at any time. Whereas one used to need to send their client a release form, or schedule a meeting just about that form, it can be emailed within the simple click of a button. Our interviews create a process for the client to permit their attorney or an entity to obtain a copy of their personal records. In addition, the BHA form requires an individual to also release their criminal record information. If, for some reason. an attorney wanted all his clients to sign a release form, they could easily send this interview to their clients. By a simple email. The release form can reach hundreds of people from all different demographics at the same time.

<b>How?</b><br>
    As an alternative and as mentioned above, one can sign a release form during an in-person meeting, through email, or just refuse to sign one altogether. As a substitute to these alternatives, the automated form creates a user-friendly solution that creates an easier and more user-friendly interview. Although release forms are usually filled out in person, COVID made face-to-face interactions a rarity. Using data automation, we were able to generate easy interviews that produces a document the client can use to release their personal information.
   
   Testing these release form interviews is the most valuable way to receive important feedback. Aside from testing our own models over and over again, Mike, Kayla and I constantly tested each other’s models to identify any ambiguity and help simplify some of the questions. For each type of release form, we each conducted real-world testing to get live feedback on issues/ambiguities neither one of us spotted.
   
   The issues we faced are mostly ones that can be fixed if we were able to speak to a subject matter expert and had more time to do research accordingly and work with them. The three main issues I stumbled across that have not been solved are minor, yet noteworthy. First, my partners and I were discussing implementing a cover page on each of our forms. Since they are all release of information forms, a cover page would give a general idea as to what a release of information form is and the basics to it. This would overlap with all three (or more if more become automated in the future) release forms that Kayla, Mike and I have to keep them in unison. This issue is one of the minor ones. An important issue we did not know how to fix was the initial question of whether the client is starting a new case or reopening an old one. This automatically assigns them as plaintiff and defendant, which is irrelevant in our case. Since our forms are not court forms, adding this is just confusing on the user. When my teammates and I tried to fix that, our form would break so we decided to leave it alone for someone with a higher level of expertise can take a look at. The last issue I came across is identifying what is required and what is not. For an attorney or the BHA release, it is known what is and isn't required. Because the general release form was constructed by me and there is no one to ask, we leave it up to the client and agency to determine on a case by case basis what is required. If there is a way to allow a party to determine beforehand what is required in their specific instant, what would be very helpful. However, I did not know where to even start with that and did not have enough time to research it, so that issue is left open for the next person to resolve.
   
   Our interviews of our testers required them to submit a brief statement providing feedback on their experience using our interviews and forms, their feedback is stated below:

   <b>*User One</b><br> is a 35-year-old male who is filing out and signing their form on their mobile device, and emailing it to themselves to download. In addition, User One’s form requires a witness.* He found the form easy to use, but disliked the format on his phone. He had remarks about the visuals of the form, and also disliked giving the witness his phone and preferred to email it to him. I believe sending the form to a witness defeats the purpose of them being a witness, since a witness is supposed to be present then and sign the same thing at the same time as the client.
   
  <b> *User Two</b><br> is a 60-year-old woman who is filling out the form on her computer and printing it to mail to her attorney.* She was confused by the question asking her if anyone else had filed with her. This question is rather confusing since only one person per form can release their information. Maybe that is something that should be added somewhere to the form, removing that question and adding a disclaimer that the release form is only valid for one person at a time.
   
   <b>*User Three</b><br> is a 21-year-old female filling out a form on her computer with a witness present, and emailing it to herself to send a copy to her attorney.* She was not sure whether the option to add more than one witness was necessary. She was also confused about being asked if she was the plaintiff or defendant. This is an issue my partners and I also came across and refined to remove the word “court” from the interview since none of the release forms are court forms.

<b>The Feedback</b><br>
    The feedback we got from everyone who tested our forms out was extremely beneficial to us. With every demo of the product, something was tweaked, added or clarified. First off, the three of us tested each other’s forms out multiple times, making sure they were clear and somewhat coherent to each other since they are all release of information forms. We constantly deleted and edited code to make the interview clearer. To make sure our forms were as accessible to as many people as possible, we ensured our testers were from a diverse background. Our first major user feedback session was the one we as teammates had with one another. Our second major feedback group were our Users, who tested the interview for us and gave us feedback in regard to what they are using their form for and how their experience went. A third and very important feedback session we had was the demo we had with David Colarusso and Quinten Steenhuis. They were able to inform us what they think is necessary to include and not based on their experience with our form and previously. They helped us clarify some ambiguous terms to make it easier for the average layperson to answer. As a final attempt to receive user feedback, we even asked a classmate to go through our interview and tell us what she thinks, if she believes anything is unclear or something can be simplified.

<b>The Future</b><br>
    Our plan was to program a short interview that would produce a signed release form, and we did that times three. By automating these forms, we most definitely expanded reach by more than 100 and decreased amount of time by more than 50%. Whereas one used to block out hours of time for someone to come in to meet and sign these release forms, our automated document allows the attorney/entity and client to do the same in a fraction of the time. The interview is also very simplified, so it alleviates any confusion one might have if they were to fill this form out on their own if they access it online. In a fraction of the time using a fraction of the effort, automating these release forms creates a greater reach and impact on the user. It is also more efficient and less time consuming on behalf of the attorney or organization working with the client, since the form can be explained, completed and emailed all within the comfort of the users own home at their own time and pace.
   
   All our forms generate a viable output that is intuitive and a great solution to the status quo. Considering how confusing it was to find the BHA release form and how the general release did not exist, users would most definitely agree that our document automation is a great improvement over how it the process is now. In addition, because of COVID-19, legal help has generally been harder to obtain. Through the Document Assembly Line Project and using our release forms specifically, a client can easily access and execute a release form. Our forms are clear and concise, with explanations and examples given to users when we assumed a prompt might need clarification. Our automation simplifies something that has many parts and complies it into the same place to produce a clear and simple release form.
There are many concerns my team and our testers came up with that have been addressed, and only few that have not. Thinking abstractly, my team and I were considering people who did not have access to a cellphone, laptop or to WIFI. Our solution to this idea was for the client to go to a public library or one of the many public places that offers free internet access. Another obstacle we considered was if someone has a disability that diminishes their ability to clearly read the form and found several programs that dictate the words on the screen in the case one’s vision is impaired. We also considered the obstacle of having a language barrier. That issue can be addressed as this project progresses and more forms are generated in different languages. We had planned to create an attorney release form in Spanish, but time was not on our side to add that to our workload. However, automating such a form in Spanish is one steps towards breaking down the language barrier issue.
    
   Our forms work! It is ready for real world use but could be better by fixing a few minor issues. Most have to do with overall aesthetic and specifications based on who is using the form and what they require. A few hours work on our forms is more than enough to render it ready for real-world use. Discussions with subject matter experts would help us get to the ready stage we want to be at. We were able to call up the Boston Housing Authority and ask them a few questions about specifications for their release form.
   
   The future is bright for this project. After sending letters to our partners, we have received assurance that they are ready and willing to implement further progressions to our forms. With future volunteers, the Assembly Line Project is going to work on continuing to develop our forms and keep up with them. Our project has grown so much from my <b> <a href="https://github.com/SuffolkLITLab/docassemble-GeneralAuthorizationforRelease/blob/main/Intro%20Pitch.pptx">introduction pitch</a></b><br> to what it is now. With a constant strive to make the form as clean, precise and easy as can be, there is so much growth between what I thought I was capable of doing and what I actually did. Hopefully, the future volunteers who continue this automation take steps to fix the few leftover issues and send this out into the real world.
    
<b>Final Thoughts</b><br>
    There are a  people I could not have survived this class without, and at the top of that list are my two teammates, Kayla Gallagher and Mike Carroll. These two were always there for help, feedback and testing. I also want to thank my classmates in Coding the Law, Professor David Colarusso, Quinten Steenhuis and the entire docassemble team. It is always great working with people who want to teach you and help you at the same time.





 <b><a href="www.youtube.com/watch?v=HVaM_goHiAY">TL;DR so here's our video instead</a><br></b><br>
# </ CodingTheLawFinal>


