# <a href='https://github.com/shubacca/API-mini-project/blob/master/API/api_data_wrangling_mini_project.ipynb'> API mini project </a>
The current project analyzes financial stock data of a company, using the requests package. The company of interest is Carl Zeiss Meditec, which manufactures tools for eye examinations, as well as medical lasers for laser eye surgery: https://www.zeiss.com/meditec/int/home.html. The company is listed under the stock ticker AFX_X.

Here are the particular tasks associated with the API project:
- Collect data from the Franfurt Stock Exchange, for the ticker AFX_X, for the whole year 2017 (keep in mind that the date format is YYYY-MM-DD).
- Convert the returned JSON object into a Python dictionary.
- Calculate what the highest and lowest opening prices were for the stock in this period.
- What was the largest change in any one day (based on High and Low price)?
- What was the largest change between any two days (based on Closing Price)?
- What was the average daily trading volume during this year?
- What was the median trading volume during this year. (Note: you may need to implement your own function for calculating the median.)
