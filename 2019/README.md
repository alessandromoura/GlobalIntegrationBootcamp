To make this solution to work you need to do the following steps:
1. Publish the BolinhaService in a Service Plan in Azure
2. Publish the HoccaBarService in a Service Plan in Azure
3. Deploy the Logic Apps created
4. Create a Service Bus namespace (premium tier)
5. In Service Bus, create one topic and three subscriptions filtering by the field Meal
6. In Service Bus, go to events and point to the Logic App created for the HoccaBar

If you have questions about setting this up, let me know and I'll help you to do it.

Please be aware of the cost of Service Bus (premium tier), and how much it will cost it to maintain this environment live. If it's just for testing, remove the namespace after you are done with the test or you will end up with a very high bill.
