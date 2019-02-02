# Overview and Data
Exploratory data analysis was performed to gain insights into whether customers prefer certain features of anime more than others.

## Tools Used

The analysis was done using R version 3.5.1 in a R markdown file. The output is a pdf after knitting. The libraries used were gridExtra, ggplot2, ggrepel, tidyverse, knitr, and kableExtra.

## The Process

Originally, the data was scraped off the web using Python. The object was saved but the python list objects within the dataframe were converted to strings. When loading the data into R, the string lists were cleaned into a usable R format. After, summary statistics were performed and graphs were created to explore the data and gain insights. A report was made as the output of the R markdown file which can be found in the repo.

## Replicate the analysis

To replicate my results, one could simply knit the R markdown file to pdf. The data is included in the repository. Ensure that all tools and libraries such as R markdown/knitting and the libraries mentioned in the "Tools Used" section are installed and running on your personal device.

## Author(s)

* **Dexter Luu**
111
Table 1. The head of the data scraped from myanimelist.net. The voice actors column was truncated to
four entries for formatting but the data had up to 10 entries per anime.
X Title Rank Score studio media.type
0 Death Note 1 8.66 Madhouse TV
1 Shingeki no Kyojin 2 8.48 Wit Studio TV
2 Sword Art Online 3 7.60 A-1 Pictures TV
3 Fullmetal Alchemist: Brotherhood 4 9.24 Bones TV
4 One Punch Man 5 8.71 Madhouse TV
5 Tokyo Ghoul 6 7.99 Studio Pierrot TV
X genres
0 c("Mystery", "Police", "Psychological", "Supernatural", "Thriller", "Shounen")
1 c("Action", "Military", "Mystery", "Super Power", "Drama", "Fantasy", "Shounen")
2 c("Action", "Adventure", "Fantasy", "Game", "Romance")
3 c("Action", "Adventure", "Comedy", "Drama", "Fantasy", "Magic", "Military", "Shounen")
4 c("Action", "Sci-Fi", "Comedy", "Parody", "Super Power", "Supernatural", "Seinen")
5 c("Action", "Mystery", "Horror", "Psychological", "Supernatural", "Drama", "Seinen")
X voice.actors
0 c("Yamaguchi, Kappei", "Miyano, Mamoru", "Nakamura, Shidou", "Hidaka, Noriko")
1 c("Ishikawa, Yui", "Kaji, Yuki", "Inoue, Marina", "Kamiya, Hiroshi")
2 c("Matsuoka, Yoshitsugu", "Tomatsu, Haruka", "Taketatsu, Ayana", "Itou, Kanae")
3 c("Park, Romi", "Kugimiya, Rie", "Miki, Shinichiro", "Fujiwara, Keiji")
4 c("Furukawa, Makoto", "Ishikawa, Kaito", "Nakamura, Yuuichi", "Yuuki, Aoi")
5 c("Kobori, Yurie", "Amamiya, Sora", "Kugimiya, Rie", "Miyano, Mamoru"
```
