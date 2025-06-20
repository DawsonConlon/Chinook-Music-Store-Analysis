Executive Summary

This report presents a comprehensive SQL/Excel-based analysis of the Chinook digital music store. The insights revealed here offer a detailed understanding of customer behaviour, artist and genre performance, and geographic revenue distribution. Using the Chinook database, I have crafted targeted business intelligence findings designed to inform better decision-making for music product marketing, sales strategies, and expansion planning. The data includes three years of customer activity and 412 invoices included within the analysis. 

 Top Performing Artists.

The analysis identified the five highest-selling artists based on the number of tracks sold:

Iron Maiden – 140 total sales.

U2 – 107 total sales.

Metallica – 91 total sales.

Led Zeppelin - 87 total sales.

Os Paralamas Do Sucesso - 45 total sales.

The average total sales across all artists was 21. Iron Maiden outperformed this average by 119 sales, making Iron Maiden 6.6 times more popular than the average artist, indicating significant popularity and commercial viability. U2 also performed notably well, with their sales being 5 times higher than the average. 

![image](https://github.com/user-attachments/assets/473e648c-7a6c-45e5-8067-d976151d5510)






Top Selling Genres.

Rock was the most purchased genre by a large margin, with 835 total sales, followed by Latin music at 386 total sales. The average sales across all genres was 93, positioning Rock as:

Over 8.9 times more popular than the genre average.

Accounting for 37% of all track sales within the Chinook store.

Latin music, while distant from Rock, still represented a significant portion of sales, indicating a strong international and multicultural interest.

![image](https://github.com/user-attachments/assets/f1629c99-da91-4647-b143-bd7272eb41d6)



Genre Preferences by Country.

A pivot table combined with slicers can be used interactively within the excel file to assess genre preferences by country. This allows stakeholders to:

Understand local musical tastes.

Optimize country-specific marketing campaigns.

Explore underrepresented genres in different markets.

![image](https://github.com/user-attachments/assets/64f46a1c-d13c-408d-a725-cea381c38994)

![image](https://github.com/user-attachments/assets/944f3341-f008-4f9f-982b-d60d6ac2e4f9)



Total Revenue by Country.

Over the observed three-year period, the store generated a total revenue of $2,328.60. The average revenue per country was approximately $97.00.

Key revenue contributors:

USA – $523.06 (22% of total revenue).

Canada – $303.96 (13% of total revenue).

Together, North America accounted for 35% of total revenue. While North America remains crucial for business success, significant contributions from European and South American markets indicate global viability and point to the opportunity for localized expansion.

![image](https://github.com/user-attachments/assets/a30ada23-5fe9-4a23-a666-04bac8898761)


![image](https://github.com/user-attachments/assets/b6a73935-f5ec-4ff8-993f-0d9dfd4734d7)


Average Invoice Value by Country.

From a total of 412 invoices, the global average invoice value was approximately $9.50.

Noteworthy insights:

The USA generated the most invoices (91) but ranked 7th in average invoice value.

European countries led in terms of the highest average invoice amounts, suggesting customers in those regions tend to spend more per transaction.

These findings suggest a potential to increase value per customer in high-volume countries like the USA, and to further nurture high-value customers in Europe.

![image](https://github.com/user-attachments/assets/04a2ba23-10bd-48e5-8cd9-cfd5088413cb)


Methodology.

All analyses were performed using SQL on the SQLite version of the Chinook Database. Tables used included:

Invoice

InvoiceLine

Customer

Track

Album

Artist

Genre

Advanced SQL techniques such as JOINs, aggregation, window functions, and date formatting were applied. Results were exported and, where applicable, visualized for clearer communication.

Business Recommendations.

Prioritize top-selling artists like Iron Maiden and U2 for promotional campaigns.

Focus on Rock and Latin genres for global campaigns.

Invest in the North American market, but consider tailored strategies for Europe and South America, where spending behaviour differs.

Incentivize higher invoice values in high-volume, low-value regions like the USA.

Use genre preference insights per country to inform regional content offerings.


