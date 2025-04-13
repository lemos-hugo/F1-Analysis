# Formula 1: Sprint vs. Grand Prix Analysis

This is a project done for the New York Data Science Academy, which focuses on data analysis using Python.

Formula 1 is a worldwide sensation and has seen increasing popularity over the last couple of years following its acquisition by American group Liberty Media Corp. The acquisition brought changes to the brand entertainment-wise in the form of new racing circuits held in the United States, popular artist performances in F1 events and the hit Netflix series 'Drive to Survive'. However, the changes introduced to the F1 brand also included updates to the format of races in order to make the sport more dynamic and entertainment-driven. In 2021, the so-called 'Sprint' races were included as part of the Grand Prix weekend. 

The purpose of this project is to analyze drivers' and teams' performances in Sprint vs. Grand Prix races and draw insightful conclusions about the inclusion of the new format.

## Background

Traditionally, Formula 1 race weekends took the following format: 
  1. Drivers have 3 _Free Practice_ sessions on Friday, in which they can freely drive through the racing circuit in order to test their car and get to know the track.
  2. _Qualifiers_ are held on Saturday. These are time trials in which each driver has a chance to race the circuit and record their fastest lap time. The lap times are used to establish what will be their starting position on the race, which is referred to as the _grid_.
  3. Sundays are typically race days, referred to as _Grand Prix_. Drivers will start at their positions established during the qualifiers and race for the best finishing positions.

With the inclusion of the new _Sprint_ race for certain race weekends, the new format is as follows:
  1. Drivers now have only 1 _Free Practice_ session at the very first day.
  2. Typically on Fridays, now there's a _Sprint Qualifier_ as well as a _Sprint Race_ hours later. These work in the same format as a regular race: the qualifier establishes the starting position of each driver in the Sprint race, with the only difference being that Sprint races are half the length of a regular race.
  3. Regular qualifiers and Grand Prix races are held in the remaining days as per usual.

For additional context, refer to the official F1 documentation: https://www.formula1.com/en/latest/article/the-beginners-guide-to-the-formula-1-weekend.5RFZzGXNhEi9AEuMXwo987

## Motivation

With the provided background information, the rational follow-up is: what does this change for drivers? Does it mean that there's less practices and a shorter race before the main event? What should be the motivator for drivers and their teams to try and win Sprint races?

The scoring system in Formula 1 rewards drivers who were in the top 10 of the Grand Prix (higher the position, higher the points). For Sprint races, the top 8 drivers are rewarded with points in the same fashion. There are two competitions throughout the season: (1) **Drivers Tournament**, in which the driver with the most points win and (2) **Constructor's Tournament**, in which team's with the most points (each team has 2 drivers) win. This means that Sprint races are an opportunity to score additional points, which can make a big difference for drivers and teams at the end of the season. Therefore, there is an interest in performing well in Sprint races, and this feeds into the main questions to be addressed throughout this analysis:

  - How do driver's performances differ from Sprint to Grand Prix? Who are the drivers who perform best at each format?
  - What's the influence of a driver's starting position in the grid for Sprint and Grand Prix? Which format has the biggest difference between starting and ending position? What does this mean for driver's risk appetite in each format?
  - What teams perform better in Sprint in comparison to the Grand Prix? How considerable is that difference? Are these usually winning teams?

## Data Remarks

Since Sprint races were only introduced in 2021 and don't happen every weekend, this means that Sprint and Grand Prix will be compared only for weekends where both events happened over the last 4 seasons. Refer to the original dataset from Kaggle for any doubts: https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020

Link to the presentation slides: https://docs.google.com/presentation/d/1OpV9NLSSkrO_jGWr0I9qcLTlDafr5skOEfzRQgl0UKk/edit?usp=sharing

  
