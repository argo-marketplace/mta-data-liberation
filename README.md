# mta-data-liberation
Liberating imprisoned data (PDF tables) from NYC MTA's 2020-2024 Capital Plan.
![mta 2019-11-23 13_15_00](https://user-images.githubusercontent.com/4397663/69483758-54444700-0df9-11ea-9a7a-263bd2a8495c.gif)


## Why
> MTA's 2020-2024 $51.5 billion capital investment + $3.3 billion for
> MTA Bridges and Tunnels over the next five years is 70% larger than
> the 2015-2019 Program, addressing core system priorities that will
> deliver major benefits to New York's transit infrastructure.
> 
> "The maintenance and continual improvement of the transit system
> relies on the MTA Capital Program, a series of five-year investment
> plans which began in 1982." Over the past 37 years, $128 billion has
> been invested in the system.

Yet, the data behind the allocation of this money is unfortunately locked away in PDF documents rendering it difficult to further interrogation and advanced analysis by researchers and the public at large.

## What
[A csv file](https://github.com/argo-marketplace/mta-data-liberation/blob/master/MTA%20capital%20plan%20(2020-2024)%20-%20MASTER.csv) containing the allocations of ~$49 Billion of capital spending has been created for more advanced analysis and interogation by the public at large.

CSV columns:

1. SNO - An index of projects.
2. PROJECT - An individual project that is part of a larger program
3. CODE - A "project code" categorizing the specific the project (code definitions TBD)
4. 2020 - Program spend in 2020
5. 2021 - Program spend in 2021
6. 2022 - Program spend in 2022
7. 2023 - Program spend in 2023
8. 2024 - Program spend in 2024
9. All Years - Program spend total (2020-2024)
10. PROGRAM CODE - A code specific to a program
11. PROGRAM - A program that defines a specific mandate within the MTA
12. PROGRAM NOTE - Notes specific to the program

[The csv also exists as a Google sheet here](https://docs.google.com/spreadsheets/u/1/d/1Wegrw_k9CvWlxoTmC7TaM0U9Cz40vaT7Xj8XDQ_1xmU/edit?usp=sharing)

## How
A paid license of Adobe Acrobat was used to convert the tables containing project / program listings from the [original PDF document](https://new.mta.info/document/10511) into an Excel spreadsheet. The spreadsheet was then cleaned manually.

One can also use utilities like [pdfgrep](https://pdfgrep.org/) or [Tabula](https://tabula.technology/)

## Please
Cite this repo if you use it any academic / official work.

## Know
Applied Research in Government Operations is a non-profit organization that builds, operates, and maintains pioneering data infrastructure to transform how basic public services are delivered. See more at argolabs.org
Email us argo@argolabs.org
