# testrepo
Ranks <-c(2, 2, 3, 1, 1, 4, 4, 2)
Ranks
Subject <-c("computer programming","math", "statistics", 
                                "machine learning", "domain expertise", 
                                "communication", "presentation skills", 
                               "data visualization")
Subject
Matt <-data.frame(Ranks, Subject)
Matt
barplot(Matt$Ranks, width =1, horiz =FALSE, xlab ="Subject", ylab = "Ranks", names.arg= c("CP",
        "Math", "Stats", "ML", "DE", "Comm", "PS","DV"), main="Matt's Data Science Profile")

