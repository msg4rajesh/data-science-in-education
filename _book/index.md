--- 
title: "Data Science in Education Using R"
author: "Ryan A. Estrellado, Emily A. Bovee, Jesse Mostipak, Joshua M. Rosenberg, and Isabella C. Velásquez"
site: bookdown::bookdown_site
output:
    bookdown::gitbook:
        number_sections: true
documentclass: book
bibliography: [book.bib, packages.bib]
biblio-style: "apalike"
link-citations: yes
github-repo: "data-edu/data-science-in-education"
description: "Bookdown for 'Data Science in Education Using R' by Emily A. Bovee, Ryan A. Estrellado, Jesse Mostipak, Joshua M. Rosenberg, and Isabella C. Velásquez to be published by Routledge in 2020"
favicon: "favicon.ico"
url: "datascienceineducation.com/"
---



# Welcome {-}

Welcome to Data Science in Education Using R! Inspired by {bookdown}, this book is open source. Its contents are reproducible and publicly accessible for people worldwide. The online version of the book is hosted at [datascienceineducation.com](https://datascienceineducation.com/).

![](dsieur-cover-routledge.jpg){width=100%}

## Prologue {-}

There’s this story going around the internet about an eagle egg that hatches in a chicken farm. The eagle egg hatches near the chicken eggs. The local hens are so busy doing their thing that they don’t notice the baby eagle egg is not their own. The eagle chick is born into the world and, having no knowledge of its own eagleness, joins its new family on a nervous and exciting first day of life. Over the next few years the baby eagle lives as chickens live. It eats chicken feed, learns to fly in short choppy hops a few feet at a time, and masters the rapid head jabs of the chicken strut. 

One day, while strutting around the chicken farm, the young eagle sees something soaring through the sky. The flying creature has long wings, which it stretches wide before tucking them back in and angling itself downward for a dive towards the earth. The sight of this other-worldly bird stirs something in the young eagle. 

Over the next few weeks the eagle finds it can’t shake the vision of the soaring eagle from its mind. It tests the conversational waters during feeding time. It wonders out loud, “What if we tried to fly more than two feet off the ground?” The other chickens stare back. The young eagle, uncertain if these stares are ambivalence or the default chicken eye position, begins to ponder the only way forward. It must learn to fly high while living with the chicken family it loves.

This is a book about learning to program in R while working in education. It’s for folks who feel at home in the education community but are looking out into the world and wondering how to use data better. It’s about being a great educator and wondering if it’s too late to learn to code. It’s about being an educator who’s learning to code and wondering if there are others you can learn with. 

We were on Twitter a lot in November of 2017. We talked about things like debugging R code, interpreting model coefficients, and working on spreadsheets with three header rows. We kept coming back to these topics over and over again. It was like having an obscure hobby with online friends because it’s hard to find local knitters who only knit Friends characters, or vinyl collectors who only collect Swedish disco albums. When you work as a data science consultant in education or as an educator learning data science, it’s hard to find that professional community that just gets you. Going to education conferences is great, but the eyes glaze over when you start talking about regression models. The data science conferences are super, but the group at the cocktail table gets smaller when you vent about the state of aggregate test score data. 

We started talking about data science in education online because we wanted to be around folks who do data science in education. We wrote this book for you, so you can learn data science with datasets you can find in education work. We don’t claim to be experts at education or data science, but we’re pretty good at talking about what it’s like to do both in a time where doing both is just starting to take off. 

So, give your chicken family a big hug, open up your laptop, and let’s start learning together. Turns out, there are a lot more hatchlings wanting to be eagles and chickens at the same time.

![(\#fig:unnamed-chunk-3)The Tweet That Started It All](./man/figures/Figure 0.1.png){width=100%}

## Acknowledgments {-}

This work was supported by many individuals from the [DataEdu Slack channel](https://dataedu.slack.com/) (https://dataedu.slack.com/). Thank you to everyone who contributed code, suggested changes, asked questions, filed issues, and even designed a logo for us: Daniel Anderson, Abi Aryan, Jason Becker, William Bork, Jon Duan, Erin Grand, Ellis Hughes, Ludmila Janda, Jake Kaupp, Nathan Kenner, Zuhaib Mahmood, Federico Marini,  Virgil Pierce and the rest of the class at University of Northern Colorado, Wayne Smith, David Ranzolin, Kris Stevens, Bret Staudt Willet, and Gustavo Velásquez.

Thank you to the data scientists in education that took time to share their stories with us: Isabella Fante, LaCole Foots, Tobie Irvine, Arpi Karapetyan, John LaPlante, and Andrew Morozov.

Thank you to the [R 4 Data Science](https://app.slack.com/client/T6UC1DKJQ/C6VCZPGPR) community who graciously hosted a bookclub for this book, and the participants who gave incredible advice and feedback to make this book better: Morgan Grovenburg, Alyssa Ibarra, Daniel Jin, Mark LaVenia, Rob Lucas, Catherine Miller, Yukie Toyama, Ryan Woodbury, and Edgar Zamora.

Thank you to the editor of this book at Routledge, Hannah Shakespeare. We appreciated Hannah’s incisive, constructive feedback, interest, and support for the book and our unique approach to writing it---one which involved writing the book "in the open" (through GitHub) and sharing it on a freely available website.

## Dedications {-}

Emily:

> To my husband, Dan, who supports me every day and has believed in this book from day one. To my family and to Gus, who accompanied me on the journey.

Ryan:

> To my wife, Lucy, and my sons, Dylan and Adam, for enduring so much typing during dinner. And to Dan Winters, for enduring so many plots over coffee.

Jesse:

> To Leo, Miles, Abby, and Jinx.

Josh: 

> To Katie and Jonah and to Teri, Joel, Aaron, and Jess, who took an interest in it from its beginning through its completion. 

Isabella:

> To my loving family, in particular my older brother Gustavo E., who never tells me to go read the manual.

## Citation {-}

If you would like to cite this book, please use the citation below:

> Estrellado, R. A., Freer, E. A., Motsipak, J., Rosenberg, J. M., & Velásquez, I. C. (2020). *Data science in education using R*. London, England: Routledge. *Nb.* All authors contributed equally. 

## Purchasing the book {-}

Purchase the book via:

- [Routledge](https://www.routledge.com/Data-Science-in-Education-Using-R/Estrellado-Freer-Mostipak-Rosenberg-Velasquez/p/book/9780367422257)
- [Amazon](https://www.amazon.com/Data-Science-Education-Using-R/dp/0367422255/ref=sr_1_2?dchild=1&keywords=data+science+in+education+using+r&qid=1593880609&sr=8-2)
- Your local or independent bookseller

## Reviews {-}

"The authors have provided the definitive guide to the topic. The combination of theory and hands-on practical tutorials make this an invaluable resource for the growing fields of learning analytics and educational data science". - Mark Warschauer, Professor of Education and Informatics at the University of California, Irvine

"This book is a clear, compelling guide for real-world practitioners who are ready to use modern tools of data science in the education domain. The effective data analysis content would benefit almost anyone getting started with data today, but these authors' thoughtful, focused handling of the specific issues involved in working with education data sets it apart from most introductory data science books". - Julia Silge, Software Engineer at RStudio

"There are many resources for learning how to analyze education data. But what has long been missing is an inclusive and pedagogically refined resource on how to leverage modern data science principles, workflows, and tools. Data Science in Education using R fills this massive gap and more. It will be the go to resource for the next generation of data driven education professionals. And is a beautiful exposition of how to responsibly work with data from the real, messy, world". - Dustin Tingley, Deputy Vice Provost for Advances in Learning at Harvard University

"Data Science in Education Using R provides a wide menu of resources for individuals in education who wish to both learn R and think more deeply about their relationship to data. The book provides both practical guidance through worked examples and discussions of relevant theory and past research. That the book is written by authors who have varied research and practice positions lends itself to its broad-ranging appeal". - Teomara (Teya) Rutherford, Assistant Professor of Learning Sciences, University of Delaware

"Doing data science in education is an interdisciplinary endeavor. If you are a teacher, an administrator, or an educational researcher who's looking for a theory-informed, practice-oriented, and equity-minded introduction to educational data science, no need to look further than this book. It will help you unleash your data science "superpower," turbocharge your practice, and make real-world changes in your organization". - Bodong Chen, Associate Professor and Co-Director of Learning Informatics Lab at the University of Minnesota
