# Portfolio
---
## Data Science

### Unveiling the Secrets of Spotify Songs’ Popularity

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/linhlhpham/Spotify-Song-Popularity/blob/main/DSO-545_Final-Project-Code.ipynb)
[![Report](https://img.shields.io/badge/PDF-Report-red?logo=PDF)](pdf/Spotify-Report.pdf)
[![Presentation](https://img.shields.io/badge/Presentation-salmon?)](pdf/Spotify-Presentation.pdf)

The music industry is a lucrative sector within the entertainment industry, generating billions of dollars annually. **With 114,000 Spotify tracks over a range of 125 different genres**, there is immense revenue potential to utilize business analytics to help music producers adapt to this evolving landscape, understand consumer preferences through track popularity, guide in the song-making process, enhance the overall listening experience for consumers, and ultimately increase customer loyalty and subscription.

<center><img src="images/spotify graph.png"/></center>

#### Interesting findings:
- **Cluster 0** represents the popularity of Pop-films. The songs in this genre tend to be moderately popular when they have lower ‘danceability’ and ‘tempo’ and a more positive or happy emotional tone.
- **Cluster 1** represents the popularity of K-pop. Since ‘valence’ and ‘loudness’ have positive values, it indicates that songs in K-pop should have higher loudness and a generally positive mood.
- **Cluster 2** represents the popularity of Chill. Negative ‘tempo’ suggests a more relaxed or laid-back feel, whereas positive ‘danceability’ indicates a balanced level of rhythm suitable for dancing. 
- **Cluster 3** represents the popularity of Pop. Songs in this genre are relatively popular when the tracks are less explicit, less danceable and convey a less positive mood. Pop songs tend to be louder to attract listeners. 
- **Cluster 4** represents the popularity of Hip-hop. It is pretty expected that Hip-hop songs are likely to be more popular when they have a strong rhythm and cheerful mood, creating a lively feel when combined with high danceability. However, it’s interesting to note that songs in this genre should contain fewer explicit lyrics and fall within a moderate tempo range.

<center><img src="images/spotify clustering.png"/></center>

---
### Homeownership and Delinquency: Decoding the Impact on Credit Card Holders

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/linhlhpham/Homeownership-delinquency/blob/main/DSO-510_Group-C1_Final-Code.ipynb)
[![Report](https://img.shields.io/badge/PDF-Report-red?logo=PDF)](pdf/HOS-Report.pdf)
[![Presentation](https://img.shields.io/badge/Presentation-salmon?)](pdf/HOS-Presentation.pdf)

- Credit cards are the most prevalent form of household debt and continue to become even more widespread. As Americans grapple with high inflation and record debt, many have fallen behind on credit card payments. In fact, 5.08% of credit card balances fell into serious delinquency in the second quarter of 2023, according to data from the Federal Reserve Bank of New York.
- The problem our team aimed to answer was: “Does a credit card holder’s home ownership status impact their delinquent behavior?” Our goal is to help banks understand what factors influence an individual’s delinquency rate. Through this, banks can identify which consumers are most likely to default and refine strategies to target these consumers. 
- With a dataset of **400K** values over 4 quarters, our team first performed a comprehensive EDA and saw a significant trend emerge that individuals with mortgages consistently showed the highest average delinquency rate. In contrast, those renting homes displayed the lowest average delinquency rate. 

<center><img src="images/HOS 1.png"/></center>
<center><img src="images/HOS 3.png"/></center>

We then leveraged Multivariate Regression modeling and with p-value < 0.05, we were able to conclude that both "home_ownership_RENT" and "home_ownership_OWN" exert a discernible influence on the values of "delinquency_2yrs." It is evident that groups with different home ownership statuses manifest distinct patterns in their occurrences of delinquency over the past two years. This nuanced understanding allows for a more comprehensive interpretation of the relationships between home ownership and delinquency, contributing valuable insights to inform further investigations or policy considerations in relevant domains.

<center><img src="images/HOS 2.png"/></center>
---
<center>© 2023 Thanh Phan. Powered by Jekyll and the Minimal Theme.</center>
