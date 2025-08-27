# Doctor-Who-Timey-Wimey-Series
A project looking at the timeline of Doctor Who and assessing whether changes in Doctor affect viewing figures.

Doctor Who is the world's longest running sci-fi show, having aired first in 1963. The show's longevity is due, in part, to a narrative device whereby the Doctor can regenerate as a different actor whenever the character is killed. It is these regenerations that form the basis of the project.

## Hypothesis
Changes in Doctor will result in a change in viewing figures of 1m or more

## Data

Episode data was pulled from Wikipedia and Rating Graph

https://en.wikipedia.org/wiki/List_of_Doctor_Who_episodes_(2005%E2%80%93present)

https://www.ratingraph.com/tv-shows/doctor-who-ratings-20291/ (2005 - 2022)

https://www.ratingraph.com/tv-shows/doctor-who-ratings-115139/ (2023 +)


The dataset contains all seasons from the 2005 relaunch and the 2023 reboot. For ease I've not called the two new ones 1 and 2, I've continued with 15 and 16
Specials have been included - Christmas specials have been named episode zero of the following season, any that came between seasons (Eve of the Daleks, for example) have been attached to the season prior

|  Column Name   | Description                                  |
|----------------|----------------------------------------------|
|  Season        |  Season of the show                          |
|  Episode       |  The episode of each season                  |
|  Episode ID    |  A unique identifier of season and episode   |
|  Episode Title |  The title of the episode                    |
|  Written by    |  Who wrote the episode                       |
|  Release Date  |  The date it aired on BBC                    |
|  Viewers       |  The number of viewers on BBC (millions)     |
|  Year          |  The year the episode aired                  |
|  IMDB Score    |  Rating given by viewers on IMDB (out of 10) |
|  Companion     |  Who was travelling with The Doctor          |
|  Viewers       |  Who was in charge of the show               |


## Doctors

|  #  | Actor                     |
|-----|---------------------------|
|  9  |  Christopher Ecclestone   |
|  10 |  David Tennant            |
|  11 |  Matt Smith               |
|  12 |  Peter Capaldi            |
|  13 |  Jodie Whittaker          |
|  14 |  David Tennant again      |
|  15 |  Ncuti Gatwa              |


## Analysis
- Time Series Analysis of the twenty seasons with trends and forecast
- Linear regression to determine the validity of the hypothesis
- Both conducted in Python


## License
MIT license applied
