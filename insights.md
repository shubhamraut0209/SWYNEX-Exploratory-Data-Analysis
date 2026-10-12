# EDA Insights

**Metric definition:** Gross sales = quantity × unit price. Estimated net sales = gross sales × (1 − discount percentage / 100). This assumes each row represents one transaction line and excludes shipping, tax, returns, and other adjustments unless already reflected in the dataset.

1. **Category contribution:** Electronics is the highest net-sales category at $377,574.65, representing 27.0% of total estimated net sales. Consider checking stock availability and product-level margins in this category.
2. **Payment preference:** Cash on Delivery is the most frequently used payment method, accounting for 17.3% of transactions (2,041 transactions). This suggests it is important to keep this payment flow reliable.
3. **Order fulfilment mix:** Delivered is the most common recorded order status (6,472 transactions; 54.8%). Status is a snapshot in this dataset, so this distribution should not be interpreted as a delivery success rate without knowing how statuses were captured.
4. **Geographic concentration:** United Arab Emirates contributes the most estimated net sales at $210,840.68 (15.1% of net sales). This market may merit a deeper look at category mix and fulfilment performance.
5. **Product-level performance:** Power Bank ranks first by estimated net sales at $54,482.82 (3.9% of net sales). Compare its units and discount levels before making pricing or inventory decisions.
6. **Rating coverage limitation:** Customer ratings are missing for 5,968 transactions (50.5%). The mean rating among the 5,846 rated transactions is 3.90/5; improve rating collection before using ratings as a complete customer-satisfaction measure.
7. **Location data limitation:** Shipping city is missing for 491 transactions (4.2%). City rankings therefore describe only records with a populated city; country-level analysis can still use all records.
8. **Discount impact:** Recorded discounts total an estimated $102,514.78, which is 6.8% of gross sales. Evaluate whether discounted products or categories also show stronger units or customer ratings before changing discount policy.
