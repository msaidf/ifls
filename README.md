# Crowd-coding of IFLS data

Indonesian Family Life Survey (IFLS) is an on-going longitudinal survey in Indonesia. Its sample is representative of about 83% of the Indonesian population living in 13 of the 27 provinces in the country in 1993. There has been five waves of IFLS, collected in 1993, 1997, 2000, 2007/08, and 2014/15.

The survey contains very rich questions, unparalleled by any other survey collected in Indonesia. This richness comes at the cost of complexity. The data from each wave of survey is comprised of dozens of files, with various layout. In order to prepare the IFLS data for analysis, there are a lot of data table reshaping and merging across files. 

The goal of this open repository is to share the statistical programming code on tidying IFLS data tables, so that unnecessary work repetition by different researchers can be avoided. The side benefit for the researcher who shares their code is that they can get feedback if there is coding error or more efficient way to do the same task.

This repository is language-agnostic, code from any statistical program can be shared here. I personally choose R as my main statistical language, although I am also proficient in coding with Stata. Anybody free to fork and create a pull request to contribute in their chosen language, either for new tasks, or porting code from one language to another. 

## Tidy Data

I am using "tidy data" term such as defined by [Hadley Wickham](http://vita.had.co.nz/papers/tidy-data.pdf). In the case of IFLS data, I think the decently tidy form of it would be such that we combine all individual level data to one table and all household level data to another. For community level data, I think it is best to have one table for each facility.

## License
All the code in this repository is shared under GPL3 term. 
