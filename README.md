# 'Deadliness' of COVID-19 (Global and Country-Based)
> DATA3406 - Group 4 (12-Green)

This project is an inspection of the novel coronavirus (COVID-19) pandemic and its perceived deadliness across the world. Analysis will be both from a holistic, global perspective, as well as close examination of certain countries and how they have been impacted by COVID-19.

Our analysis will also consider potential uncertainty present in the data provided.

The source of the data will be from *Our World in Data* (https://ourworldindata.org/coronavirus)

## Table of contents

* [Driving Question](#driving-question)
* [Background](#background)
* [Data Origin](#data-origin)
* [Data Definitions](#data-definitions)
* [Ethics](#ethics)
* [Issues](#issues)
* [Getting started](#getting-started)
* [Contributing](#contributing)
* [Project Owners](#project-owners)
* [License](#license)
* [References](#references)
* [Other Details](#other-details)


Driving Question
---------

The driving question of our analysis is *How Deadly is COVID-19?* We will be examining the 'deadliness' of COVID-19 both from a global perspective, as well as a select few countries and examining their responses to managing the virus.

We will also be accounting for the uncertainty that might be prevalent within the data sources, and we will be making sure to mention these when producing data visualisations.

Background
---------

The novel coronavirus disease 2019 (COVID-19) is an infectious respiratory disease that has impacted the world substantially. It has been classified as a global pandemic by the *World Health Organisation* (WHO), and has sparked countries across the world to develop management and prevention strategies such as lockdowns and extensive social distancing practices.

To date, 

Data Origin 
---------

Our COVID-19 dataSet, *‘owid-covid-data.csv’*, is a snapshot of the data from the *‘Our World in Data’* [github repository](https://github.com/owid/covid-19-data/tree/master/public/data) taken on **15 October 2020**. The data in the repository is open access under the [Creative Commons BY license](https://creativecommons.org/licenses/by/4.0/) and is updated daily. It is made up of a collection of sources, namely the [European Centre for Disease Prevention and Control (ECDC)](https://www.ecdc.europa.eu/en/publications-data/download-todays-data-geographic-distribution-covid-19-cases-worldwide ), official testing reports, United Nations, World Bank, etc. More details are provided in their [codebook](https://github.com/owid/covid-19-data/blob/master/public/data/owid-covid-codebook.csv).

Our dataset has the following features: `iso_code`, `continent`, `location`, `date`, `total_cases`, `new_cases`, `new_cases_smoothed`, `total_deaths`, `new_deaths`, `new_deaths_smoothed`, `total_cases_per_million`, `new_cases_per_million`, `new_cases_smoothed_per_million`, `total_deaths_per_million`, `new_deaths_per_million`, `new_deaths_smoothed_per_million`, `total_tests`, `new_tests`, `new_tests_smoothed`, `total_tests_per_thousand`, `new_tests_per_thousand`, `new_tests_smoothed_per_thousand`, `tests_per_case`, `positive_rate`, `tests_units`, `stringency_index`, `population`, `population_density`, `median_age`, `aged_65_older`, `aged_70_older`, `gdp_per_capita`, `extreme_poverty`, `cardiovasc_death_rate`, `diabetes_prevalence`, `female_smokers`, `male_smokers`, `handwashing_facilities`, `hospital_beds_per_thousand`, `life_expectancy`, `human_development_index`.

Data Definitions
---------

Group Meeting Minutes - Minutes folder
Each group meeting minutes is stored in the Minutes folder with the format, Week#_Meeting_Minutes.pdf. Each document contains the agenda for the week and the following meeting. It also records the action items and division of work among group members for the following week. Additionally, it discusses the key points we learned from each member’s individual analysis.

Process Notebooks
Each group member has their own Jupyter notebook containing the data exploration for their respective part. These process notebooks are updated regularly and stored in the Process Notebooks folder.

> TODO: List of key files and describes key variables needed to understand the product notebook. Like purpose of each folder, where to find process notebooks, product notebook, the data... Purpose for different folder of data (**Preserve immutability of the raw data.**)

Ethics
---------

Issues
---------
- [x] **Format README file**
- [ ] **Create an outline of the product notebook**
- [ ] **Ethical analysis - purpose**
- [ ] **Stakeholder analysis**
- [ ] **Ethical analysis - nature of raw data**
- [ ] **Ethical analysis - managing data and biases**
- [ ] **Ethical analysis - limitations**

Getting Started
---------
To clone the repository: 

1. Create a folder on your local machine where you want to store these files (you can do this normally).
    * in terminal/command-line, you use the command `mkdir filename`
2. Navigate to the folder you have just created in terminal/command-line. 
    * To do this use the command, `cd` to change directories (navigate through folders), and `dir` (for windows) or `ls` (for linux/MacOS) to show a list of available directories accessible from your current directory. 
    * Example sequence of commands: 
        * `cd Desktop` (your now on the desktop) -> `cd foldername` (your now in the folder your created to store the repository) -> `cd data3406_group4` (your now in the repository folder)
        * Note: A common mistake people make is assuming that the folder they had created is the repository, its actually the folder that *stores the local copy of the repository* so make sure you navigate to the repository folder first, otherwise you will get an error message saying that the repository does not exist.
3. Type in the command `$ git clone https://github.sydney.edu.au/awon6941/DATA3406_Group4.git`
4. You should now have a copy of the repository on your local machine. 

Contributing
---------
(assuming you are currently on your local repository directory)
1. `$git pull` - pull the latest changes **(ALWAYS DO THIS FIRST)** 
2. Make your changes to the folder, either by adding a new file, or overwriting an existing file. 
3. `$git add .` - for add all changes or ‘$git add hello.ipynb’ - for a specific file.
4. `$git commit -m “Your commit comments here." `
5. `$git push` - push your commits to the repository.

If you thought you had made a mistake, you can simly reset your commit by using the command,
   * `$git reset --soft HEAD~1` to reset it back by 1 commit 
      * use `--soft` if you simply wanted to correct your commit message, and push the changes.
      * use `--hard` if you want to completely remove the changes. 
   * `$git reset --hard 0abcd1d` resets to a specific commit based on the commit code (e.g. 0abcd1d).

Alternatively, you can simply overwrite the files you changed with the older version, or simply delete the unwanted file/folder from your desktop and use the sequence of commands,
  * `git add .`, `git commit -m "message"` and `git push`. 
   
 For more commands see the [Git cheatsheet](https://github.sydney.edu.au/awon6941/DATA3406_Group4/blob/master/assests/SWTM-2088_Atlassian-Git-Cheatsheet.pdf) by Atlissian.  

Project Owners
---------
Project owners are DATA3406 students from the University of Sydney.

### Contact details

| Full Name       | Preferred Name | SID       | Email                      | Phone     |
|-----------------|----------------|-----------|----------------------------|-----------|
| Samantha Chew   | Samantha       | 480380926 | sche4003@uni.sydney.edu.au | 0426262512|
| Alex Wong       | Alex           | 470066919 | awon6941@uni.sydney.edu.au | +65 96629875|
| Andrew Auwyang  | Andrew         | 480377616 | aauw2900@uni.sydney.edu.au | 0433120386|
| Voon Ken Ren    | Ken            | 480219084 | kvoo2843@uni.sydney.edu.au | 0450752249|
| Lou Irish Gonzales | Lou         | 480378255 | lgon9610@uni.sydney.edu.au | 0426203696|

### Role Rotation

|    Week     |  Tracker |  Manager |  Editor | GitHub Manager |  Tester and Checklist  |
| :---------: | :------: | :------: | :-----: | :------------: | :--------------------: |
|      8      |    Lou   |   Alex   |   Sam   |       Ken      |                Andrew  |
|      9      |  Andrew  |    Lou   |  Alex   |       Sam      |                   Ken  |
|     10      |    Ken   |  Andrew  |   Lou   |      Alex      |                   Sam  |
|     11      |    Sam   |    Ken   |  Andrew |       Lou      |                  Alex  |
|     12      |    Alex  |    Sam   |   Ken   |     Andrew     |                   Lou  |

License
---------

References
---------
> "You have the permission to use, distribute, and reproduce these in any medium, provided the source and authors are credited." How should we provide the source and authors? https://github.com/owid/covid-19-data/tree/master/public/data
> This data has been collected, aggregated, and documented by Cameron Appel, Diana Beltekian, Daniel Gavrilov, Charlie Giattino, Joe Hasell, Bobbie Macdonald, Edouard Mathieu, Esteban Ortiz-Ospina, Hannah Ritchie, Max Roser.

Other Details
---------

### Meeting Times
* Monday 8:30pm 

### Tools
* Github
* Google Drive 
* Jupyter Notebooks/Google Collab

