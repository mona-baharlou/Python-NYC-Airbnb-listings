**"Exploring NYC Airbnb Listings with Python 🏙️**  

I dug into Airbnb's NYC 2019 dataset using Python to understand pricing trends and how they relate to customer reviews. Here's what I did:  

1. **Loaded the Data** 📂  
   - Imported libraries like Pandas, Matplotlib, and Seaborn.  
   - Read the `AB_NYC_2019.csv` file to explore NYC Airbnb listings.  

2. **Visualized Price Distribution** 💵  
   - Created a histogram of listing prices. Most were under $200, but there were wild outliers (some over $1,000!).  
   - Refined the histogram by binning prices in $40 increments (0-40, 40-80, etc.) to get a clearer picture.  

3. **Explored Price vs. Reviews** 🔍  
   - Plotted a scatter plot of prices against the number of reviews.  
   - Noticed most reviews cluster around cheaper listings (<$200), with pricier spots getting fewer reviews overall.  
   - Zoomed in on listings under $1,100 and shrunk the dot size (`s=5`) to reduce clutter and spot patterns better.  

**Key Takeaways** 🎯  
- Budget-friendly listings dominate the NYC Airbnb market.  
- Higher prices = fewer reviews (maybe folks think twice before splurging?).  
- Adjusting bins and axis limits helps clean up noisy data!"  
---  
