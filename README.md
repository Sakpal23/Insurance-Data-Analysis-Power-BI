# Insurance-Data-Analysis-Power-BI
A 2-page Power BI report on insurance policies, premiums, coverage and claims. It shows which policy types earn the most, how claims are split by status, and which age groups claim the most.
Dashboard
<img width="1022" height="576" alt="Report-1" src="https://github.com/user-attachments/assets/24345503-7a01-4c4b-b99b-e45569c521c4" />


## Key numbers

| Measure | Value |
|---|---|
| Premium Amount | 5.98M |
| Coverage Amount | 600.55M |
| Claim Amount | 16.91M |
| Active policies | 90.85% (9.09K) |
| Inactive policies | 9.15% (0.92K) |

## What the data shows

- **Travel** brings in the most premium: 2.5M of 5.98M (about 42%). Health is next at 1.2M, then Auto 1.0M, Life 0.7M, Home 0.6M.
- **Rejected** is the largest claim group at 4.4K, ahead of Settled (3.4K) and Pending (2.3K).
- **Adults** have the highest claim amount (8.8M), then Elder (6.4M) and Young Adult (1.7M).
- Most policies are active (90.85%).

## Report pages

1. Dashboard (overview)
   <img width="1022" height="576" alt="Report-1" src="https://github.com/user-attachments/assets/e6124875-3985-4928-a316-ca4b7febcf59" />
2. Policy detail table
   <img width="1022" height="575" alt="Report-2" src="https://github.com/user-attachments/assets/8904b81d-84eb-43dc-9ef8-18bc2190ee99" />


## How it was built

- **Power Query:** set correct data types, added a conditional column, merged queries.
- **DAX:** measures for premium, coverage, claim amount and claim counts.
- **Row-Level Security (RLS):** roles limit which rows each user can see.
- **Visuals:** bar chart, donut chart, ribbon chart, area chart, matrix, table, slicers.


## Data fields

PolicyNumber, CustomerID, ClaimNumber, Age, Gender, CoverageAmount, PremiumAmount, PolicyStartDate, PolicyEndDate, PolicyType, ClaimStatus, Active/Inactive, Age Group.

## Tools

Power BI Desktop, Power Query, DAX.

## Files

```
Insurance-Data-Analysis/
├── Insurance_Data_Analysis.pbix
├── Insurance_Data_Analysis.pptx
├── images/
│   └── dashboard.png
└── README.md
```

## How to open

1. Download `Insurance_Data_Analysis.pbix`.
2. Open it in Power BI Desktop.
3. To test RLS: Modeling > View as > pick a role.

## Author

**Umesh Sakpal**
Power BI Developer and Data Analyst
GitHub: [Sakpal23](https://github.com/Sakpal23)
Email: umeshsakpal14@gmail.com
