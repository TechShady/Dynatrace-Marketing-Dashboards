# Digital Business Analytics Marketing Campaign Dashboards

This dashboard pack provides a detail overview for your marketing campaigns. You can see the responses broken down by campain, <br>
user experience for the campaigns and key KPI data like revenue and conversion for the campaigns. Additional drill downs show campaign <br>
performance and KPIs across configurable GEOs. You can also drill down to campaign user journeys, fauled campaign user journys and <br>
abandonded campaign user journeys.

![Marketing Campaign Overview](image/MCO.png)

[Prerequisites Video](https://www.youtube.com/watch?v=VFRN0fexMbY "Prereq Video")

[Deployment Video Coming Soon]()

[Usage Video Coming Soon]()

# Prerequisites Highlights

1. Create a session property for your campaign (i.e. Web property pack - web\_utm\_campaign query string)
2. Create a session property for revenue (i.e. revenue - CSS selector)
3. Create a session property for a successful conversion (i.e. "Order processed." - CSS selector)
4. Create a metric for the campaign session property (Metric: Useraction Duration split by Campaign)
5. Create a metric for the revenue session property (Metric Revenue no split)
6. Create 4 additional metrics for each GEO location (Metric: Useraction Duration split by Campaign Filter by continent, region, etc)
7. Mark the last user action step as a key user action for the user journey

# Create Metric for Campaigns

![Marketing Campaign Overview](image/MCOCampaigns.png)

# Create Metric for Revenue

![Marketing Campaign Overview](image/MCORevenue.png)

# Create Metric for Campaign by GEO

![Marketing Campaign Overview](image/MCOCampaignsByGEO.png)

