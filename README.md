# Lab M7.05 - Creating Budgets and Alerts

## What I Did
- Created an SNS topic and confirmed email subscription for budget alerts
- Set up a monthly $50 cost budget with 50%, 80%, and 100% threshold alerts
- Created a service-specific EC2 budget ($30) and a tag-based dev environment budget ($25)
- Configured an automated budget action that applies an IAM deny policy at 100%
- Documented the full budget configuration in a dashboard reference

## Key Findings
- Multi-threshold alerts provide early warning at different spend levels
- Tag-based budgets require cost allocation tags to be activated in Billing
- Automated actions add enforcement beyond simple email notifications
- Budget configurations should be version-controlled with Terraform

## Screenshots
- sns-subscription-confirmed.png
- budget-list-console.png
- budget-alerts-thresholds.png
- budget-action-configuration.png
