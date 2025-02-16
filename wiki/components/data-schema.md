# Common Data Schema

### Kokonut Farms Common Data Schema

| **Name**                | **Type**      | **Content**                                                                                                                 |
| ----------------------- | ------------- | --------------------------------------------------------------------------------------------------------------------------- |
| Project Dates           | Date          | Start & End Dates                                                                                                           |
| Forecasted Budget       | Number        | Estimated Development Budget                                                                                                |
| Land Size               | Number        | Size of Land for Agricultural Activities                                                                                    |
| Project Location        | Coordinates   | Geographic coordinates or UTM (Universal Transverse Mercator)                                                               |
| Planting Capacity       | Number        | Based on the crop selection, this field would allow specifying how many plants fit in the project.                          |
| Source of Funding       | Text          | Funding Source for Project Development.                                                                                     |
| Revenue Streams         | Multiselect   | Streams of revenue based on agricultural activities and Crop Selection.                                                     |
| Governance Mechanism    | Single Select | Type of governance that will govern the Development, Operations, and Beneficiaries of the project.                          |
| Token Allocation        | Richtext      | Allocation of Governance Tokens or Loot Tokens for stakeholders if using Blockchain-based Governance Mechanism.             |
| Public Goods Allocation | Number        | Percentage of Revenue to be Allocated for Public Goods Activities.                                                          |
| Project Summary         | Richtext      | Executive Summary of the project, which includes a blurb about the location, Size, Crop Selection, and Harvest Forecast.    |
| Local Problem           | Richtext      | The local problem the project is aiming to address by leveraging the Community Development features of the Framework.       |
| Proposed Solution       | Richtext      | The proposed solution and how exactly the development of the project is going to help ease & eradicate the pain points.     |
| Target Market           | Multiselect   | Selection of target audience based on the crop selection, desired financial returns, quality of harvest, and project goals. |

