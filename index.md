---
# Do not edit the text between these lines!
layout: default
---



<!-- This is a comment. Below, you'll see code for inserting an image. To make this image appear, update <custom-path>. To add an image, save it inside the imgs folder of this repository. -->
<img src="<custom-path>/static/imgs/logo.png" alt="Image of Comp110 rainbow logo. "  width="500"/>



# Introduction 
The idea we wanted to implement in this course was to use more real-world examples to help students better understand how coding can be useful. The reason for this idea was that most students who take this course come from different majors other than Computer Science, because this course may fulfill a requirement for their degree. Using real-world examples will allow them to understand why this course may be useful in the future.
With this idea in mind, we examined 4 variables: comp_major, interested_connections, valuable, and social_issues.
In Dr. Lytle's class, there are 534 students in total. Only 31 students have Computer Science as their major or minor. This indicates that 94.19% of the class comes from different majors, and that taking this class is either a requirement for their major or their gen-eds.

## Graph #1
The first graph looks at the count of students who rated their interest in the connections between computer science and other fields, with 1 being strongly disagree and 7 being strongly agree. Most of the students rated this a 4 or 5. The least amount of responses was 1. This data gives us some unclear results. Even though it looks like a majority of the students are interested in how coding is used in different scenarios, there were still many people who rated it from 1 to 4. We wanted to further explore this data by implementing a function that filtered the values greater than the mean and counted them. The result was 135 students who rated it from 5 to 7. That is only about 25% of the class.
<img src="C:\Users\こここ\OneDrive - University of North Carolina at Chapel Hill\COMP110\comp110-26s-workspace\personal-site.github.io\static\imgs\Screenshot 2026-04-26 170850.png"  width="500"


## Graph #2
We then looked at a scatterplot with the variables interested_connections and social_issues. There is a clear positive relation between the variables, since as the level of interest in connections increases, we see an increase in the interest in agreement of social issues being relevant to computer scientists and software engineers. The size of the dots represents the number of counts, with the bigger dots suggesting that more students felt that way. This graph clearly shows that most of the bigger dots are in the top right corner, where students ranked both interested_connections and social_issues high. It suggests that students who are more interested in the connections between fields also believe that social issues are relevant to computer scientists. I think this scatterplot gave us a clearer picture that most students know that coding is relevant to the modern world today.
<img src="C:\Users\こここ\OneDrive - University of North Carolina at Chapel Hill\COMP110\comp110-26s-workspace\personal-site.github.io\static\imgs\Screenshot 2026-04-26 170900.png"  width="500"


## Graph #3
Then we looked at one of the most important variables, valuable, in which a student rates how valuable the skills the course teaches them will be in the future. In this graph, most students rated this a 7, the highest agreement level. Besides that, most students rated this from 4 to 7. This clearly shows that students think the skills will be valuable in this course. However, they may not exactly know how or why these skills may come in handy. Having real-world examples in this scenario will allow them to grasp a better understanding of the course and material in general.
<img src="C:\Users\こここ\OneDrive - University of North Carolina at Chapel Hill\COMP110\comp110-26s-workspace\personal-site.github.io\static\imgs\Screenshot 2026-04-26 170907.png" width="500"


## Conclusion
Overall, I don't think there is a clear result of whether students would or would not like real-world examples. Although students think this coding is heavily important in real-life, there is not enough time to fully implement this idea. To further explore this topic, we would further look at other variables, including pace and difficulty, to see whether students are feeling overwhelmed. If students are not feeling overwhelmed, then introducing small examples should be fine.

## Potential downsides
Although this may be useful to many students, there are many downsides to this idea. Introducing real-world examples during class may take time away from potential questions students may have or teaching material. At the end of the day, students are being graded on their ability to understand the course, and real-world examples may take some time away from students. However, it may also help students understand the material better. Teachers may post examples of scenarios outside of class for students who may be curious; however, I'm going to guess that the majority of the students will never look at the material due to their busy schedules. The teacher may also assign it as homework, like with this assignment. However, even with this assignment, students may get confused with the material. Teachers also need to be able to find data that is appropriate for an introductory-level class.

## Implementation
We think the best way to implement this is to add optional assignments as extra credit for students to view, instead of adding them to the original classwork. This will allow students to gain an understanding of why a specific piece of coding can be useful. It doesn't even have to be real-world data, but can be made-up data, which is simpler and close enough to allow students to understand how it would work in a real-life setting. A trade-off to this idea is more work for someone to grade the work.