Credit Card Sale

{
    "event_id": "9b312dfd-3174-4748-9447-d63c8744305a",
    "event_type": "transaction.sale.success",
    "event_body": {
        "merchant": {
            "id": "1234",
            "name": "Test Account"
        },
        "features": {
            "is_test_mode": true
        },
        "transaction_id": "1234560000",
        "transaction_type": "cc",
        "condition": "pendingsettlement",
        "processor_id": "ccprocessora",
        "ponumber": "123456789",
        "order_description": "this is a description",
        "order_id": "12345678",
        "customerid": "",
        "customertaxid": "",
        "website": "https://example.com",
        "shipping": "",
        "currency": "USD",
        "tax": "0.08",
        "surcharge": "",
        "cash_discount": "",
        "tip": "",
        "requested_amount": "54.04",
        "shipping_carrier": "",
        "tracking_number": "",
        "shipping_date": "",
        "partial_payment_id": "",
        "partial_payment_balance": "",
        "platform_id": "",
        "authorization_code": "123456",
        "social_security_number": "",
        "drivers_license_number": "",
        "drivers_license_state": "",
        "drivers_license_dob": "",
        "billing_address": {
            "first_name": "Jessica",
            "last_name": "Jones",
            "address_1": "123 Fake St.",
            "address_2": "123123",
            "company": "Alias Investigations",
            "city": "New York City",
            "state": "NY",
            "postal_code": "12345",
            "country": "US",
            "email": "someone@example.com",
            "phone": "555-555-5555",
            "cell_phone": "",
            "fax": "444-555-6666"
        },
        "shipping_address": {
            "first_name": "Jessica",
            "last_name": "Jones",
            "address_1": "123 Fake St.",
            "address_2": "123123",
            "company": "Alias Investigations",
            "city": "New York City",
            "state": "NY",
            "postal_code": "12345",
            "country": "US",
            "email": "someone@example.com",
            "phone": "",
            "fax": ""
        },
        "card": {
            "cc_number": "411111******1111",
            "cc_exp": "1022",
            "cavv": "",
            "cavv_result": "",
            "xid": "",
            "eci": "",
            "avs_response": "N",
            "csc_response": "",
            "cardholder_auth": "",
            "cc_start_date": "",
            "cc_issue_number": "",
            "card_balance": "",
            "card_available_balance": "",
            "entry_mode": "",
            "cc_bin": "",
            "cc_type": ""
        },
        "action": {
            "amount": "54.04",
            "action_type": "sale",
            "date": "20200406175755",
            "success": "1",
            "ip_address": "1.2.3.4",
            "source": "virtual_terminal",
            "api_method": "virtual_terminal",
            "username": "exampleuser",
            "response_text": "SUCCESS",
            "response_code": "100",
            "processor_response_text": "",
            "processor_response_code": "",
            "device_license_number": "",
            "device_nickname": ""
        }
    }
}
            
Event Body Reference
card.entry_mode
Code	Description
0	Unknown
1	Invalid
2	NFC MSD
3	Swiped
4	Keyed
5	EMV ICC
6	NFC EMV
7	Keyed - Fallback
8	Swiped - Fallback
Electronic Check Sale

{
    "event_id": "c1ee29d9-dd29-45d0-903a-c78da43bca32",
    "event_type": "transaction.sale.success",
    "event_body": {
        "merchant": {
            "id": "12345",
            "name": "Test Account"
        },
        "features": {
            "is_test_mode": true
        },
        "transaction_id": "1234560000",
        "transaction_type": "ck",
        "condition": "pendingsettlement",
        "processor_id": "ckprocessora",
        "ponumber": "",
        "order_description": "",
        "order_id": "",
        "customerid": "",
        "customertaxid": "",
        "website": "",
        "shipping": "",
        "currency": "USD",
        "tax": "1.00",
        "surcharge": "",
        "cash_discount": "",
        "tip": "",
        "requested_amount": "60.49",
        "shipping_carrier": "",
        "tracking_number": "",
        "shipping_date": "",
        "partial_payment_id": "",
        "partial_payment_balance": "",
        "platform_id": "",
        "authorization_code": "123456",
        "social_security_number": "",
        "drivers_license_number": "",
        "drivers_license_state": "",
        "drivers_license_dob": "****-**-**",
        "billing_address": {
            "first_name": "Jessica",
            "last_name": "Jones",
            "address_1": "123 Fake St.",
            "address_2": "",
            "company": "Alias Investigations",
            "city": "New York City",
            "state": "NY",
            "postal_code": "12345",
            "country": "US",
            "email": "someone@example.com",
            "phone": "5555555555",
            "cell_phone": "",
            "fax": ""
        },
        "shipping_address": {
            "first_name": "Jessica",
            "last_name": "Jones",
            "address_1": "123 Fake St.",
            "address_2": "",
            "company": "Alias Investigations",
            "city": "New York City",
            "state": "NY",
            "postal_code": "12345",
            "country": "US",
            "email": "someone@example.com",
            "phone": "",
            "fax": ""
        },
        "check": {
            "check_account": "*****1234",
            "check_aba": "100000000",
            "check_name": "Jessica Jones",
            "account_holder_type": "personal",
            "account_type": "checking",
            "sec_code": "WEB"
        },
        "action": {
            "amount": "60.49",
            "action_type": "sale",
            "date": "20200406180124",
            "success": "1",
            "ip_address": "1.2.3.4",
            "source": "virtual_terminal",
            "api_method": "virtual_terminal",
            "username": "exampleuser",
            "response_text": "SUCCESS",
            "response_code": "100",
            "processor_response_text": "",
            "processor_response_code": "",
            "device_license_number": "",
            "device_nickname": ""
        }
    }
}
            
Cash Sale

{
    "event_id": "e88bfc27-2d42-46a1-8427-65b4a7f11f16",
    "event_type": "transaction.sale.success",
    "event_body": {
        "merchant": {
            "id": "123456",
            "name": "Test Account"
        },
        "features": {
            "is_test_mode": true
        },
        "transaction_id": "1234560000",
        "transaction_type": "cs",
        "condition": "complete",
        "processor_id": "csprocessora",
        "ponumber": "",
        "order_description": "",
        "order_id": "",
        "customerid": "",
        "customertaxid": "",
        "website": "",
        "shipping": "",
        "currency": "USD",
        "tax": "1.00",
        "surcharge": "",
        "cash_discount": "",
        "tip": "",
        "requested_amount": "60.49",
        "shipping_carrier": "",
        "tracking_number": "",
        "shipping_date": "",
        "partial_payment_id": "",
        "partial_payment_balance": "",
        "platform_id": "1",
        "authorization_code": "",
        "social_security_number": "",
        "drivers_license_number": "",
        "drivers_license_state": "",
        "drivers_license_dob": "",
        "billing_address": {
            "first_name": "Jessica",
            "last_name": "Jones",
            "address_1": "123 Fake St.",
            "address_2": "",
            "company": "Alias Investigations",
            "city": "New York City",
            "state": "NY",
            "postal_code": "12345",
            "country": "US",
            "email": "someone@example.com",
            "phone": "+15555555555",
            "cell_phone": "",
            "fax": ""
        },
        "shipping_address": {
            "first_name": "Jessica",
            "last_name": "Jones",
            "address_1": "123 Fake St.",
            "address_2": "",
            "company": "Alias Investigations",
            "city": "New York City",
            "state": "NY",
            "postal_code": "12345",
            "country": "US",
            "email": "someone@example.com",
            "phone": "",
            "fax": ""
        },
        "action": {
            "amount": "60.49",
            "action_type": "sale",
            "date": "20200406180150",
            "success": "1",
            "ip_address": "1.2.3.4",
            "source": "virtual_terminal",
            "api_method": "virtual_terminal",
            "username": "exampleuser",
            "response_text": "APPROVED",
            "response_code": "100",
            "processor_response_text": "Approved",
            "processor_response_code": "1",
            "device_license_number": "",
            "device_nickname": ""
        }
    }
}