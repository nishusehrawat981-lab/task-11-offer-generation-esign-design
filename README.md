# Task 11 — Offer Generation & E-Sign Design

## Objective

Build a decision-ready offer funnel that tracks candidates from
interview through offer generation, e-signature and hiring.

## Tools Used

- Python
- Google Colab
- Pandas
- Matplotlib

## Dataset

The project uses:

`Task_11_Offer_Generation_E_Sign_Data.csv`

The dataset is based on the earlier synthetic application funnel
and contains an additional synthetic offer/e-sign layer.

## Funnel

Interviewed
→ Offer Generated
→ Offer Sent
→ E-Sign Sent
→ Signed / Declined / Pending
→ Hired

## Key Metrics

- Applications
- Interviewed candidates
- Offers generated
- Interview-to-offer rate
- E-sign sent
- Signed offers
- Pending offers
- Declined offers
- E-sign completion rate
- Offer-to-hire rate

## Key Results

- Applications: 1,000
- Interviewed: 270
- Offers: 85
- Interview-to-offer rate: 31.5%
- Signed offers: 59
- Pending offers: 12
- Declined offers: 14
- E-sign completion rate: 69.4%
- Hired: 59
- Offer-to-hire rate: 69.4%

## Dashboard Views

1. Offer funnel KPI cards
2. Interview → Offer → E-Sign → Hire funnel
3. Source performance
4. Decline-reason analysis
5. Pending-offer monitoring
6. Role and company filters
7. Candidate-level traceability
8. Data-quality checks

## Data Quality

The project checks:

- Unique application IDs
- Unique offer IDs
- Missing offer IDs
- Valid e-sign statuses
- Chronological timestamps
- Logical funnel ordering

## Important Note

The application funnel is synthetic demonstration data.

The offer and e-sign fields are synthetic extensions created
for demonstrating the required Task 11 analytics workflow.

They must not be presented as real production e-sign activity.

## How to Run

1. Open the Google Colab notebook.
2. Upload the Task 11 CSV.
3. Run the cells from top to bottom.
4. Review the funnel, KPIs and e-sign analysis.
5. Export the analysis CSV files.
