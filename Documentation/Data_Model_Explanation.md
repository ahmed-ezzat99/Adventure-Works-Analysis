## Data Model Explanation

- The model follows a star schema design.
- Sales table acts as the fact table.
- Dimension tables provide filtering by date, product, territory, and customer.
- Single-direction relationships were used to avoid ambiguity.
- Date table was marked as a Date Table to support time intelligence.
