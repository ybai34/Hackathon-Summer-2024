# University of Rochester Biomedical Data Science Hackathon Summer 2024
Welcome to the landing page for the hackathon. The competition is now over and final scores are now posted. 

 Please make sure each individual competing on your team is fully registered. To receive a prize, you must supply your University of Rochester e-mail address. All teams scoring better than random will receive a participation prize. 1st and 2nd place winning teams in each division will get a cash prize (see below).
 **All team members must submit their own registration form to receive prizes.** To finish your team registration or to register for an existing team, use this [google form](https://forms.gle/xVYZeegK4hSVtm3F8). 


# Logistics

0.   Each team must have a github handle associated with it in order to participate.  Make sure you edit your registration or email the organizers to provide this, if you haven't yet. Your team will not be scored if you do not provide a handle.
1.   You may add team members up
to noon EDT on 8/13 by editing your response to the google form or emailing the organizers.
2.  Teams of entirely undergraduates will be in the undergraduate
division, else they will be in the open division.
3.  Predictions on test data set are submitted by pushing to
    github.  A repository with the name `Hackathon-Summer-2024`,
    owned by the team captain, will
    be queried for a file named [prediction/prediction.csv](prediction/prediction.csv). Your predictions should be formatted in the exact same way and in the same order as the sample prediction file. Just replace the example TRUE/FALSE predictions with your own.  **If the team captain forks this
    repository and writes predictions there everything should work
    (as long as the predictions are formatted correctly).** 
2.  Predictions will be scored at least once daily, starting 8/13, with
    scores posted by 3 PM.  At
    the organizers' option, predictions may be scored more frequently
    than this.
2.  General questions/problems can be directed to [issues](https://github.com/Rochester-Biomedical-DS/Hackathon-Summer-2024/issues) page.  We encourage other hackathon participants to respond to issues.
3.  The scoreboard will be located
    [here](Leaderboard.Hackathon.2024.md).
   
    We  cannot provide support
    beyond the diagnostic output included on the scoreboard if an error is
    encountered in scoring your predictions.
5.  Interim scoring may employ forms of randomization (e.g. bootstrapping) from the test data set.  The final scores will use all the data and not be randomized.
4.  Competition runs through 2:59 PM EDT 17-August-2024.  The predictions each team has committed to their repository at that time will be used to determine their final score. Captains must submit their own predictions. Any use of predictions from other teams is disqualifying. Winning teams must submit their code to organizers to claim their prize.

# Challenge overview
- Single-cell multiome (RNA + ATAC) sequencing is a recently developed technology platform that simultaneously profiles gene expression and chromatin accessibility from the same cell. Single-cell multiome can transform your understanding of biology, for example, estimating the association between enhancer and gene expression using single-cell multiome data. However, such multiome data have an overabundance of zeros due to dropout events where the mRNA or chromatin accessibility is undetected in a cell. Thus, typical correlation methods (like Pearson correlation and Spearman's rank correlation) showed a low power in estimating the associations between regulatory elements and gene expression. For an overview of zero inflation in single-cell data, see Jiang et al. (2022, [PMID: 35063006](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-022-02601-5)). Accurate detection of associations between regulatory elements and gene expression remains a significant challenge, and no single method outperforms all others.

- The goal of this hackathon is to develop your model to identify associations between chromatin accessibility and gene expression using single-cell multiome data. Chromatin accessibility (ATAC in this hackathon) represents a functional canalization of the epigenome by defining a repertoire of putative regulatory regions (peaks in this hackathon) across the genome, further shaping gene expression programs (RNA in this hackathon). For an overview of the relationship between Chromatin accessibility and gene regulation, see Klemm et al. (2019, [PMID: 30675018](https://www.nature.com/articles/s41576-018-0089-8)).

**Find a complete description of the dataset [here](Data.Description.md) and the data [here](/data).**

# Prizes
   
1.  First place in each division: $300 + $75 x (team size)
2.  Second place in each division: 0 + $50 x (team size)
  
# Winners!
   
**Congratulations to the winning teams:**
   
 * 1st place Undergraduate division- The Browns
 * 2nd place Undergraduate division- Capybara
 
 * 1st place Open division - CookieMonster and DMMH tied
 * 2nd place Open division- BASE

If your team's final MCC was >0, you will receive a prize! 
* All individuals who participated in the following teams will receive a prize for your score: The Browns, Capybara, CookieMonster, DMMH, BASE, Zong Time, MJCG Lab, Tiramisu, emole, AttnIsAllYouNeed, Phoenix, iKun, Rookie Data Scientist, data science gurlies, 60hahsm, ?, Lucy, why axis, Biomedical Data Science Team 2, Gathucy, Elden Lord, and Pickleballers.

In order to claim your prize, you will need to fill out a [post-competition survey](https://forms.gle/ptXhkD3hUhaFkYhKA) and [prize information form](https://forms.gle/sZYUe9SCCFUQzso7A).


# Feedback and post-event information
Thank you for participating in this competition! We hope that you enjoyed the event. Please give us feedback so that we can improve future events. All teams that submit predictions may receive a participation certificate. Please e-mail alarracu at bio.rochester.edu for your certificate.

**Fill out the post-competition [survey](https://forms.gle/ptXhkD3hUhaFkYhKA).** 
* You must be registered for the event in order to claim a prize.  
* If your team submitted predictions and you would like to receive a certificate of participation, please e-mail alarracu@bio.rochester.edu. 
* Some of the winning teams will present their approach to the hackathon in an upcoming meeting of the GIDS working group in life and biomedical data science. You are all invited. Details about the meeting will come via e-mail once it is scheduled.

