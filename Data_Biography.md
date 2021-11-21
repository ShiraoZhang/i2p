# Data Biography

### Declaration of Authorship

I, Shirao Zhang, confirm that the work presented in this assessment is my own. Where information has been derived from other sources, I confirm that this has been indicated in the work.

Shirao Zhang

Date of signature: 20/11/2021
Assessment due date: 26/11/2021
Student Number: 21053585

_Please write your answer immediately below the level-3 headers and delete the guidance prior to submission._

---

### 1. Who collected the data?

#### As mentioned in [2], buy-to-let career landlords and some management companies collected the data, and Andy Wightman, a Green party member of the Scottish parliament commissioned a report.

---

### 2. Why did they collect it?

#### As mentioned in [2], most obviously, short-term rentals threaten a new kind of gentrification as they shift much-needed housing from the housing sector to the tourist economy. Along the way, there is evidence that it has led to rising rent levels and exacerbating predictable and terrible social divisions. [1] also argued that Airbnb has introduced a new potential income stream entering the housing market, which is systemic but geographically imbalanced.

---

### 3. How was it collected?

#### [4] claimed that the first stage in data collection is to visit the Airbnb website search pages to locate as many listings as possible in London. Each listing has its own page on Airbnb website. As the second part of the data collection for each data set, the programs visit each page to gather detailed information about that listing. Therefore, every listing described in the dataset can be seen on the Airbnb website when a survey is conducted.

---

### 4. What useful information does it contain?

#### It contains the house name, host response time, host response rate, host acceptance rate, whether the host identity is verified, neighbourhood, latitude, longitude, property type, room type, accommodates, the number and situation of bathrooms, the number of bedrooms and beds, price, whether the house has the availability of short term limit, the number of room that has 30 - day limit, 60 - day limit, 90 - day limit, and 365 - day limit, the number of reviews, review scores rating, the review scores of accuracy, cleanliness, check in, communication, location, and value, whether it can book instantly, and how many reviews per month. They can reflect a house’s location, basic information, the credibility of the landlord, customer impressions and service ratings, price, ease of ordering, and attention of the house.

---

### 5. To what extent is the data 'complete'?

#### There are some NaNs and Nulls, so row of these should be dropped. It is worth nothing that many Airbnb listings are never visited by guests: those that are not easy to see do not play an important role in the business. As mentioned in [4], in the absence of internal Airbnb data, the number of reviews can also provide the number of visits to a listing. Otherwise, this metric may be imprecise for any individual list, but in general, it is widely used to estimate the relative number of visits to the list population. For the location, some list pages do have imprecise locations, but for summary purposes, the accuracy is high. From my perspective, at least 90% of the active listings in the city have been captured.

---

### 6. What kinds of analysis would this support?

#### First, the text analysis can be carried out. And the method called Term Frequency – Inverse Document Frequency (tf - idf) can be used. Second, the data can also be classified. We can calculate the count of each property type and each room type. Third, the price should also be changed to float by deleting “$” and “,” in order to analyze conveniently afterwards. Fourth, we can also get the mean, standard deviation, minimum, 25% quantile, median, 75% quantile, and maximum of these variables. Fifth, we can find how many listings cost more than $100 per night for entire apartment for example. Sixth, finding the cheapest and most expensive listings. Seventh, calculating the z - score, the IQR – standardised score, and natural log of the price. Eighth, we can visualise the distribution of the distribution of the series, such as histograms, Kernel Density Estimate plots, and boxplots. It can also combine the price with longitude and latitude, and make scatterplots. The hex bin plots can also be plotted using longitude and latitude. Ninth, the host response rate and host acceptance rate can reflect the service attitude. The review scores of every aspect can analyse the level of listings and the satisfaction of customers. The number of reviews and reviews per month can reflect the attention of listings, and whether it has the availability of short term limit can analyse the ease of ordering.

---

### 7. Which of the uses presented in Q.6 are _ethical_?

#### Kate and Megan [3] claimed that social media platforms and mobile phone data are often mined to analyse data. However, social and mobile data set have their limitations and can lead to certain types of analytical and ethical oversight if not fully understood and interpreted. [5] argued that the reasons for students and researchers to act ethically can be divided into three categories, in addition to the moral argument that humans should always do so. First, ethical behaviour ensures that rights of individuals or communities affected by research are protected. Secondly, by acting ethically, researchers maintain public opinion and public trust, which will allow future scholars to conduct new research, Third, universities can be held responsible for the actions of students or employees and therefore need to protect their institutions, which reinforces the emphasis on ethical behavior. In Question 6, the first analysis to the seventh analysis are ethical. However, for the eighth use, it is not ethical. Since it is about longitude and latitude, as mentioned in [5], geocodes are geographic coordinates that can be abstracted into various spatial levels. Therefore, from my perspective, longitude and latitude are geocodes. And [5] also claimed that research using geocoding has the potential to expose the ethical aspects of geographic research, especially because they are sensitive to privacy. For the ninth use, it is also not very ethical. Obtaining the host response rate and host acceptance rate will reveal the host’s personal information. In the dataset, it collected their ID, name, location, and personal profile, so their privacy is not guaranteed. If they do not make their customers satisfied, they may be subjected to cyberbullying and so on. In addition, obtaining the review scores maybe reveal the personal information of customers. Therefore, analysing the service attitude and the satisfaction of customers are not ethical. However, in my opinion, the using of reflecting the attention of listings and the ease of ordering and ethical.

## Bibliography

[1] D. Wachsmuth and A. Weisler. (2018, June) “Airbnb and the rent gap: Gentrification through the sharing economy”, Environment and Planning A: Economy and Space [Online]. vol. 50, issue 6. pp. 1147–1170. Available: https://journals.sagepub.com/doi/10.1177/0308518X18778038

[2] J. Harris. (2018, February. 12). Profiteers make a killing on Airbnb – and erode communities [Online]. Available: https://www.theguardian.com/commentisfree/2018/feb/12/profiteers-killing-airbnb-erode-communities

[3] K. Crawford and M. Finn. (2014, November) “The limits of crisis data: analytical and ethical challenges of using social and mobile data to understand disasters”. GeoJournal [Online]. vol. 80. pp. 491–502. Available: https://doi.org/10.1007/s10708-014-9597-z

[4] M. Cox and T. Slee. (2016, February. 10). How Airbnb’s data hid the facts in New York City [Online]. Available: http://insideairbnb.com/reports/how-airbnbs-data-hid-the-facts-in-new-york-city.pdf

[5] V. Bemt, J. Doornbos, L. Meijering, M. Plegt, N. Theunissen. (2018, February) “Teaching ethics when working with geocoded data: a novel experiential learning approach”. Journal of Geography in Higher Education [Online]. vol. 42, issue 2. Available: https://www.tandfonline.com/doi/full/10.1080/03098265.2018.1436534

## Appendix 

