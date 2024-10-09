This repository works about the merge of two of netflix´ databases. One with the titles coming from netflix originals, named "originals", and other with all the content the platform includes called "titles".

The two different databases were merged using an "innerjoin" method, in order to preserve the most complete data. In retrospective, maybe another different method could be more suitable, since numerous observations were lost coming from the total titles. For example "titles" database had 2930 observations after dropping nulls and duplicated values.

The initial data analysis shows some type incongruences: The "type" column, refered to the format of the show, has only one type of value: Movie. This bias responds to the incorrect merge between both databases, which left only data relative to netflix's original movies.
Secondary, the column "duration" is listed as an object, which concords with the given nomenclature "n min", but further study of the variables returns a couple null values.

Final database has 18 rows for 513 total observations, with no duplicated values, but had 364 null values,which were dropped. 65% of nulls were found in the "Duration" row.

The main languages are English, Hindi and Spanish. English conforms 68% of the main languages, in line with the main target audience (USA and UK) 

Most shows are from 2019 and 2020 (52%), but first comers are from 2014, the year the platform was introduced. During the first aforementioned years, the COVID pandemic skyrocketed the demand and consumption of on-line content, which justifies that netflix released some more shows.

In regards to the content, most popular shows are documentaries (25,7%) and Drama shows (14,2%). Least posted shows are Mockumentaries and Drama/horror (both 1,9%).
Most shows are rated 5.8 by IMDB (58% of total obs), those with a rating over 7 points only conform around the 30% of the database. This can lead to the ratification of netflix as a commercial mass-media distributor, versus other platforms which focus on higher-quality, more expensive content, such as Filmin or Disney+.

For future iterations, exploring the quality of the shows through ratings in the last uploading years could give insights of how the business model of netflix has changed. Knowing what important actors have played the most roles could open a new investigation line as of the aforementioned change in business model. 
