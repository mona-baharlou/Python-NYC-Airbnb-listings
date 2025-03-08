**Exploring NYC Airbnb Listings with Python 🏙️**  

I dug into Airbnb's NYC 2019 dataset using Python to understand pricing trends and how they relate to customer reviews.

Here’s the **skills I demonstrated** in this project:  

---

### **Technical Skills** 💻  
1. **Data Import & Basics**:  
   - Loading datasets into Python using `pandas` (e.g., `pd.read_csv`).  
   - Inspecting data structures (e.g., `nyc` to view the DataFrame).  

2. **Data Visualization**:  
   - Creating **histograms** to analyze price distributions.  
   - Designing **scatter plots** to explore relationships (e.g., price vs. reviews).  
   - Customizing plots with labels (`xlabel`, `ylabel`), axis limits (`xlim`), and styling (e.g., `s=5` for smaller dots).  

3. **Data Cleaning & Optimization**:  
   - Handling outliers by adjusting bins (`bins = ny.arange(0, 1100, 40)`).  
   - Improving plot readability by trimming axes (e.g., `plt.xlim(0, 1100)`).  

---

### **Analytical Skills** 🔍  
1. **Pattern Recognition**:  
   - Spotting trends (e.g., cheaper listings dominate the market).  
   - Identifying outliers (e.g., ultra-expensive listings over $1,000).  

2. **Hypothesis Testing**:  
   - Exploring if higher-priced listings get fewer reviews.  

3. **Critical Thinking**:  
   - Iterating on visuals (adjusting dot sizes) to clarify noisy data.  

---

### **Tools & Libraries** 🛠️  
- **Python**  
- **Pandas**: Data manipulation.  
- **Matplotlib/Seaborn**: Advanced visualization.  
- **NumPy**: Numerical operations (e.g., creating bins).  

---

And here's what I did in this project:
 
1. **Loaded the Data** 📂  
   - Imported libraries like Pandas, Matplotlib, and Seaborn.  
   - Read the `AB_NYC_2019.csv` file to explore NYC Airbnb listings.  

2. **Visualized Price Distribution** 💵  
   - Created a histogram of listing prices. Most were under $200, but there were wild outliers (some over $1,000!).  
   - Refined the histogram by binning prices in $40 increments (0-40, 40-80, etc.) to get a clearer picture.
  
     ![](https://github.com/mona-baharlou/Python-NYC-Airbnb-listings/blob/main/nyc1.PNG)
  
     
     ![](https://github.com/mona-baharlou/Python-NYC-Airbnb-listings/blob/main/nyc2.PNG)



3. **Explored Price vs. Reviews** 🔍  
   - Plotted a scatter plot of prices against the number of reviews.  
   - Noticed most reviews cluster around cheaper listings (<$200), with pricier spots getting fewer reviews overall.  
   - Zoomed in on listings under $1,100 and shrunk the dot size (`s=5`) to reduce clutter and spot patterns better.
  
       ![](https://github.com/mona-baharlou/Python-NYC-Airbnb-listings/blob/main/nyc3.PNG)
    
       ![](https://github.com/mona-baharlou/Python-NYC-Airbnb-listings/blob/main/nyc4.PNG)



**What I Understood** 🎯  
- Budget-friendly listings dominate the NYC Airbnb market.  
- Higher prices = fewer reviews.  
- Adjusting bins and axis limits helps clean up noisy data!"  
---  
