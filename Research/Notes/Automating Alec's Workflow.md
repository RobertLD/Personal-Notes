


## Things Alex Does at Work

- Expense Reports
- Emails

## Orders exported
- Rapala is the order consumption site.  There are others
- More or less the process of an expense report is converting a csv to an HTML form
- Manual entry is very error prone can we confirm that?
- Perhaps comparing the cart directly to the

### Workflow changes
1. Create email template for items that no longer exist, paste in the items that no longer exist
2. Likely create email templates for all of the common scenarios that emails must be sent for

### Automation
 1. Read CSV #1 and output a collection of item Guid and quantity. 
	 1. This step appears to be error prone. The website likes to say invalid item when uploading
	 2. We need a way to remove items that have been deprecated. This can likely be done automatically via API
2. CSV #1 can be imported directly into the website and the deprecated items can be returned to the user
3. 



## Monthly Reports