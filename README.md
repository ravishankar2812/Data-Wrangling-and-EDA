# Data-Cleaning-and-EDA
About the Uncleaned Audible Data set 
With the trend toward audiobooks growing, the idea is to understand how the audiobook market has been growing over the years. From authors of audiobooks to release dates, the data represents the important details of audiobooks from 1998 till 2025 (pre-planned releases).
I will be Performing Data wrangling and EDA on uncleaned dataset 

### Column Breakdown
- name: Name of the audiobook
- author: Author of the audiobook
- narrator: Narrator of the audiobook
- time: Length of the audiobook
- releasedate: Release date of the audiobook
- language: Language of the audiobook
- stars: No. of stars the audiobook received
- price: Price of the audiobook in INR
- ratings: No. of reviews received by the audiobook

 ## **Observations**:
   ### **Manual**
  
  ### Dirty Data

*   The audiobook title text contains multiple language. **Consistency**
*   Row no 36 contains the info related to the kind of audiobook with title **Consistency**
-   Row no 159 have mixed english and other language **Consistency**
-   Author coulum have wrttenby: in all the row **Accuracy**
-   Narrator column have written NarratedBY: in all the rows **Accuracy**
-   Date column is having data type string **Validity**
-   Stars column has many missing values **Completeness**
-   Price column has dtata type string **Validity**
-   Language columns have all lower text but English language has E caps **Consistency**
-   Date column have mentioned the date in different format**Validity**
  ### Messy Data


*   The name of the Audiobook is combined with Volume and editition of the audio book **Consistency**
*   The Time column is having hours and minutes, need to handle **Validity** **Consistency**
-   Starts column have stars as well as rating **Validity** **Consistency**



   ### **Coding**

  ### Dirty Data

*   No missing value founds in any of the columns
*   
  ### Messy Data

*   All columns have same data types string **Validity**
