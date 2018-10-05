=====
Accounts
=====
 
Accounts is a reusable custom user model app for Django with the Motorholic project formatting
 
Detailed documentation is in the "ProjectDocumentation" directory.
 
Quick start
-----------
 
1. Add 'reusable_accounts' to your INSTALLED_APPS setting like this::
 
    INSTALLED_APPS = (
        ...
        'reusable_accounts',
    )
 

2. Run `python manage.py migrate` to create the accounts models.
 
3. Add the accounts css::
    <link rel="stylesheet" href="{% static "css/mechanic.css" %}">

4. Add the stripe js file::
    <link rel="stylesheet" href="{% static "js/stripe.jpg" %}">

5. Ensure you have the backends.py which is used for the custom user model
	
6. Use accounts app to manage Stripe monthly subscriptions, ensure you have Stripe loaded.