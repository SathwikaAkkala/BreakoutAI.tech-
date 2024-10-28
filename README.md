**Project Overview**
This project is designed to process options trading data, retrieve specific values from an API, and calculate important financial metrics like margin_required and premium_earned.

**AI Usage Summary**
Function Skeletons: ChatGPT was used to suggest basic structures for the functions.
Error Handling and Conditionals: AI recommended adding error handling for API responses, helping to manage failed requests effectively.
Premium Calculation: AI assisted in understanding and implementing the calculation logic for premium_earned based on bid/ask values and lot size.
Testing Summary
Testing was performed using sample data to validate both the structure and calculation accuracy of the functions. Further validation with live API data is recommended for production use.
**Explanation of Code Components**
1. get_option_chain_data Function:

In a real implementation, this function would retrieve data from an API. Here, it returns a sample DataFrame for demonstration purposes.
*AI-Assistance Details:
.Function Structure: ChatGPT was used to clarify the overall function structure, including conditional retrieval of bid_price or ask_price based on the side parameter.
.Error Handling: ChatGPT suggested incorporating error handling for cases when the API request fails, ensuring better management of response errors.
2. calculate_margin_and_premium Function:

Calculates premium_earned by multiplying each bid/ask price by a lot_size of 50.

Adds placeholder margin_required values for demonstration. Replace these with actual API response data in real use.
*AI-Assistance Details:
.Logic for Calculations: AI clarified the use of lot_size in the premium calculation, ensuring accuracy in earnings calculations.
.API Integration: ChatGPT provided guidance on how to structure the API call for margin calculation and parse the JSON response.

3. Sample Data for Testing:

The sample data is manually defined to match the structure that would be returned by get_option_chain_data.
