{
   "event_id": "7bbd4af6-4075-4902-af56-9fc59ab71362",
   "event_type": "acu.summary.closedaccount",
   "event_body": {
        "updated_date": "2022-08-23",
        "merchant": {
            "id": 123456,
            "name": "Test Account"
        },
        "cards_checked": {
            "customer_vault": {
                "checked": 123,
                "updated": 1
            },
            "subscriptions": {
                "checked": 232,
                "updated": 1
            }
        },
        "vault_count_updated_closed_account": 1,
        "vault_updates": [
            {
                "customer_vault_id": "281474976710722",
                "billing_id": "230304034",
                "cc_number": "434343******0123",
                "cc_exp": "11/25",
                "first_name": "Longterm",
                "last_name": "Client",
                "email": "sample@customer.com",
                "phone": "6025551213"
            }
        ],
        "recurring_count_updated_closed_account": 1,
        "recurring_updates": [
            {
                "subscription_id": "281474976710727",
                "cc_number": "601101******0002",
                "cc_exp": "11/32",
                "first_name": "Bob",
                "last_name": "Smith",
                "email": "bsmith@example.co.uk",
                "phone": "+440111122222"
            }
        ]
    }
}