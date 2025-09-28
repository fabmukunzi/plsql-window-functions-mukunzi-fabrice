# MTN Rwanda Marketing Analysis

## Business Problem
MTN Rwanda Marketing Department struggles to measure campaign effectiveness and identify which promotions drive meaningful customer engagement.

## Database Schema
- **marketing_campaigns**: Campaign details
- **customer_engagements**: Engagement tracking
- **customer_segments**: Customer demographics

## Window Functions Implemented
1. Ranking: RANK(), DENSE_RANK(), ROW_NUMBER()
2. Aggregate: SUM() OVER(), AVG() OVER() with frames
3. Navigation: LAG(), LEAD(), growth calculations
4. Distribution: NTILE(4), PERCENT_RANK()

## Key Insights
- Social media campaigns generate 45% higher engagement
- Top 25% customers contribute 60% of total revenue
- March campaigns showed 22% growth over February

## References
https://www.geeksforgeeks.org/sql/window-functions-in-sql/
https://mode.com/sql-tutorial/sql-window-functions
https://www.postgresql.org/docs/current/tutorial-window.html

## Academic Integrity
"All sources were properly cited. Implementations and analysis represent original work. No AI-generated content was copied without attribution or adaptation. This assignment represents my own work in accordance with AUCAs academic integrity policies."