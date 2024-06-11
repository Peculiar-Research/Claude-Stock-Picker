
1. Open the file in Google Colab:
   - Download the ipynb file from github
   - Go to https://colab.research.google.com/
   - Click on "File" > "Open notebook"
   - Select "GitHub" tab
   - Enter the GitHub repository URL where the code is hosted
   - Select the file and click "Open"

2. Create an Anthropic account and get an API key:
   - Go to https://www.anthropic.com/ and sign up for an account
   - Once logged in, buy credits, then go to the "API" section and copy your API key

3. Update the code with your Anthropic API key:
   - In the Colab notebook, locate the 2nd line `ANTHROPIC_API_KEY = "YOUR_API_KEY_HERE"` and replace `"YOUR_API_KEY_HERE"` with the API key you copied in the previous step.

4. Adjust the number of stocks to analyze:
   - In the `def generate_ticker_ideas(industry)` function, locate the line system_prompt and messages to modify the number of tickers returned as needed.
   - For example, to analyze 10 stocks, you can change the number to 10.

5. Run the code:
   - Once you've made the necessary changes, you can run the entire notebook.
   - When prompted, enter the industry you want to analyze, it can be a large or small industry.

The code will then:
- Generate a list of ticker ideas for the specified industry
- Perform a comprehensive analysis on each company, including financial performance, market position, growth prospects, risk assessment, and more
- Provide a ranking of the companies based on their investment potential

The more stocks you analyze, the longer the process will take (approximately 1 minute per stock). Feel free to adjust the number of stocks as needed, but keep in mind that the more data you provide, the more thorough the analysis will be.
