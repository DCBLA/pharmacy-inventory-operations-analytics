# Methods Summary

## ABC Classification

ABC classification was used to rank medicines by annual usage value. The analysis found that Dapagliflozin and EpiPen accounted for 68.7% of total usage value in the selected portfolio, supporting close monitoring of high-value products.

## Demand Pattern Assessment

Demand patterns were reviewed by product rather than assuming one forecasting approach would suit all medicines.

- Dapagliflozin: high-value chronic-demand item with stable repeat demand.
- Sertraline: stable repeat demand with low unit cost and high volume.
- Amoxicillin: seasonal demand spike around autumn/winter infection periods.
- Fexofenadine: spring/summer demand increase linked to pollen season.

## Forecasting Method Selection

Holt-Winters was recommended for products with recurring seasonal peaks, such as Amoxicillin and Fexofenadine.

Simple Exponential Smoothing was recommended for stable products such as Sertraline, where no strong seasonality or trend was visible.

## Inventory Cost Analysis

Costs were assessed across three dimensions:

- holding cost: capital tied up, storage space, refrigeration, expiry risk
- ordering cost: administration, delivery, processing, order frequency
- stockout cost: service failure, emergency sourcing, patient risk

## Inventory Policy Design

The final design recommends differentiated controls:

- A-class: continuous review with safety stock
- B-class: adjusted continuous review with product-specific constraints
- C-class: periodic review with seasonal uplift where needed

## EOQ Illustration

EOQ was used as an illustrative calculation for Sertraline because it had stable, high-volume demand. The calculation highlighted the ordering-holding trade-off but also showed why operational checks such as shelf space should come before implementing a pure formula output.
