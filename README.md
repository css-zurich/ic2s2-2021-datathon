# IC2S2 2021 Datathon

Welcome to the [IC2S2 2021](https://ic2s2-2021.ethz.ch/) virtual datathon, we look forward to your participation!

This site provides detailed information about the event and is updated regularly to support you with the most up-to-date information throughout the datathon. If you have any questions please do not hesitate to reach out to the organizers, [Karsten Donnay](mailto:donnay@ipz.uzh.ch) and [Aleksandra Urman](mailto:urman@ifi.uzh.ch)!

- [Schedule](#schedule)
- [Formalities](#formalities)
- [Task](#task)

## Schedule
The IC2S2 2021 datathon will take place **fully virtually** from Thursday July 22, 2021 to Sunday July 25, 2021. Free individual registration until July 8, 2021 is open to all IC2S2 participants.

- Wed., July 21: Team assignment and prerecorded introduction session available
- Thu., July 22: Live kick-off session at 14:00h (GMT+2)
- Fri, July 23: Live check-in session at 14:00h (GMT+2)
- Sat, July 24: Live check-in session at 14:00h (GMT+2)
- Sun, July 25: Submission Deadline at 23:59h (GMT+2) 

## Formalities
Please note the folowing formalities and general information. If anything is unclear or you require additional information, please do not hesitate to reach out to the organizers:

### Communication

- The main communication venue is our Slack space "ic2s2datathon2021"; all participants have been invited directly (if you did not receive an invitation, please let us know!)
- All live sessions take place via Zoom; the link is provided in the _#general_ channel on Slack

### Team Assignment
Teams will be centrally assigned by the organizers based on the participants’ experience, interests and skills. In the assignment process, we will strive to make the teams diverse and at the same time balanced.

- We conducted a brief survey of all registered participants between July 13 and 19 to learn more about your individual backgrounds.
- The teams of 4-5 participants were then matched to ensure that each team reflects different levels of experience and skills while matching stated interestes and ensuring compatibility in terms of time zone.
- If participants did not provide any information, we randomly assigned them to a team.

### Submissions

- Deadline: **Sun, July 25 at 23:59h (GMT+2)**
- We ask you to prepare a **video (max. 15 min)** explaining your questions, methods and findings
- You may also provide additional documentation (e.g., an interactive website, PDF documents etc.)
- **Please do not submit any data or code!**
- All submissions will be **public** and made via this GitHub repository; we will provide submissions folders for each group labeled by your assigned group number
- Winning projects will be announced before the end of [IC2S2 2021](https://ic2s2-2021.ethz.ch/) and featured in an award session in the main conference

### Evaluation

The projects will be avaluated by a three-person jury consisting of:

- [Prof. Dr. Karsten Donnay](https://www.karstendonnay.net) (UZH, Department of Political Science & Digital Society Initiative)
- [Dr. Aleksandra Urman](http://aleksandra-urman.ch/) (UZH, Social Computing Group)
- [Nicolò Pagan](https://people.ee.ethz.ch/~pagann/) (ETH, Social Networks Lab & UZH, Social Computing Group)

We have diverse methodological backgrounds in the area of computational social science and hail from different substantive disciplines. In evaluating the projects we will be looking for projects that combine interesting substantive research questions with creative, sophisticated analyses. Within the scope of the task outlined below, we look forward to seeing which questions you are interested in!


## Task

### Overview
The COVID pandemic has upended daily lives and everyday behaviors, including through drastic counter-measures such as lockdowns or mobility restrictions. There is at the same time unprecedented data coverage that allows nuanced analysis of the relationship between pandemic dynamics, changes in population mobility and the progress in vaccination campaigns and, of course, how the public perceives such measures. In this datathon, teams of 4-5 participants will be tasked to explore these relationships using a variety of highly spatially and temporally resolved datasets on each of these dynamics. The datasets, among others, will include mobility data during the pandemic and social media data. The goal is to use a data-driven lense to investigate these fundamental co-dependencies and reveal important variations within and between countries. Using the data provided, teams are free to focus on a particular aspect or question of their choice while leveraging any methodological approach. 


### Topic & Possible Questions
Teams are free to address any question that can be addressed with the datasets provided and that are related to Covid-19 and population mobility during the pandemic. We have outlined a few possible concrete example questions but those are only meant as an orientation or inspiration and should in no way limit what exactly you want to work on!

- **Association between mobility patterns and case numbers** e.g., is a reduction in the visits to grocery stores associated with decreased covid cases within ~10-14 days?
- **Association between public opinion and mobility changes** e.g., is there a mobility divide? Do we see persistent differences in terms of mobility during covid between countries? What are potential explanations for this?
- **Vaccination and mobility** e.g., how fast does vaccination bring people back to “business as usual”? Does increase in vaccination lead to increase in mobility even when all measures stay in place?

Note that you are **completely free to set the geographical scope** of your project but we do provide a few datasets that are only available for Switzerland, see below.

### Datasets

The datathon draws on a varity of datasets, some of them in the public domain, others that are closed-access for which we specifically secured permission to use in the context of this event. The following two general guidelines apply to the use of datasets in this datathon, please refer to the sections below for further details:

- In addressing the task, you do not have to use all of the datasets we provide but **at least one dataset has to be used**.
- You may use further complementary datasets on any dimension of your choice that are not mentioned below as long as these data are in the **public domain and freely accessible**.

#### Mobility Data

For mobility data we draw on the two leading, comprehensive publicly available mobility datasets provided by Google and Apple. Please access these data directly from the two data providers:

- Google's [Covid-19 mobility dataset](https://www.google.com/covid19/mobility/)
- Apple's [mobility dataset](https://covid19.apple.com/mobility)

In addition, we have also secured access to a detailed closed-access Covid-19 mobility panel on Switzerland ([MOBIS](https://ivtmobis.ethz.ch/mobis/covid19/en/)) through the research team of Prof. Kay Axhausen ([ETH](https://www.ivt.ethz.ch/en/)) that includes not only detailed, longitudinal mobility data collected via an app but also individual characteristics of travelers collected through a matched-survey. The data spans both lockdown and non-lockdown periods in Switzerland during 2020, as well as pre-Covid 2019 data. **We are very grateful to Prof. Axhausen and his team for sharing these data with us for this event!**

Given the closed-access nature of these data, any team wishing to use these data has to sign a data agreement that exclusively grants the right to use these data **only** for the purposes of this datathon. We will provide the details on the specific procedure for granting access to these data in the Slack space of this event.

#### Covid-19 Data

Complementing these data and providing information on the situation regarding COVID-19 in specific countries, you can use data on COVID-19 cases, ICU occupancy, hospitalizations, etc. There are many data sources available for that. We specifically suggest using the following two data sources:

- Data provided by the [European Centre for Disease Prevention and Control](https://www.ecdc.europa.eu/en/covid-19/data)
- Date on vaccinations outside the EU/EEA area available through [Our World in Data](https://ourworldindata.org/covid-vaccinations)

#### Social Media Data

If you are interested to link mobility and Covid-19 data to (broad) measures of public attitudes or opinions, we recommend to leverage existing collections of Covid-19 related social media posts, Twitter in particular. One such comprehensive collection provides a continuous sample of the IDs of Covid-19 related tweets (i.e., sampling a set of Covid-19 hashtags) since early 2020 that can be re-hydrated using the Twitter API:

- Covid-19 TweetID collection by Emily Chen (USC) on [GitHub](https://github.com/echen102/COVID-19-TweetIDs)

For the datathon, we provide on such dataset that was already fully collated and downloaded with a focus on social media communication in Switzerland. The data may only be used in the context of this datathon and information on how to access it, will be provided in the Slack space of this event.