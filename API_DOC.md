1. XXXXXClient List and Create
    * List and Create API for XXXXXClientMaster Model
    * URL : /operation/clientmaster-list
    * HTTP method : GET
    * input :  NA
    * output :

```

```

    * HTTP method : POST
    * input :
```

```
    * output :
```

```
    * business logic :

---
---
2. XXXXXClient Update and Delete
    * Update and Delete API for XXXXClientMaster Model
    * URL : /operation/clientmaster-list-update/1
    * HTTP method : PUT
    * input :
```


```
    * output :
```

```

    * business logic  :
---

# template ends here


---
1. Client - List and Create
    * List and Create API for ClientMaster Model
    * URL : /operation/clientmaster-list
    * HTTP method : GET
    * input :  NA
    * output :
```
   {
        "count": 1,
        "next": null,
        "previous": null,
        "results": 
       [
            {
                "id": 1,
                "client_id": "Client 1",
                "name": "Rajeev",
                "address": "Address 1",
                "phonenumber": null,
                "alt_phonenumber": null,
                "mobilenumber": null,
                "email": null,
                "dob": "2015-09-01",
                "gender": "male",
                "guardian": "Ramesh",
                "guardian_type": "father",
                "category": "individual",
                "place": 1,
                "pan": null,
                "pan_date": null,
                "gst_no": null,
                "location": "Cherpulassery",
                "represented_by": "Rajeev",
                "alt_mobilenumber": null,
                "gst_date": null,
                "alt_email": null,
                "sec_address": null,
                "sec_phonenumber": null,
                "alt_sec_phonenumber": null,
                "sec_mobilenumber": null,
                "alt_sec_mobilenumber": null,
                "sec_email": null,
                "alt_sec_email": null,
                "sec_place": 1,
                "parent_clientid": null
            }
       ]
   }
```

    *HTTP method : POST
    * input :
```
    {
    "client_id": "Client 1",
    "category": "individual",
    "name": "Shihab",
    "location": "Cheruthuruthy",
    "represented_by": "Shihab",
    "dob": "1990-09-01",
    "gender": "male",
    "guardian": "XXXXX",
    "guardian_type": "father",
    "address": "Address 1",
    "phonenumber": null,
    "alt_phonenumber": null,
    "mobilenumber": null,
    "alt_mobilenumber": null,
    "email": null,
    "alt_email": null,
    "sec_address": null,
    "sec_phonenumber": null,
    "alt_sec_phonenumber": null,
    "sec_mobilenumber": null,
    "alt_sec_mobilenumber": null,
    "sec_email": null,
    "alt_sec_email": null,
    "pan": null,
    "pan_date": null,
    "gst_no": null,
    "gst_date": null,
    "place": 1,
    "sec_place": 1,
    "parent_clientid": null,
	"user_id" : 1
}
```
    * output :
```
    {
        "id": 7,
        "client_id": "RAJ/CLNT/2018-2019-001002",
        "category": "individual",
        "name": "Shihab",
        "location": "Cheruthuruthy",
        "represented_by": "Shihab",
        "dob": "1990-09-01",
        "gender": "male",
        "guardian": "XXXXX",
        "guardian_type": "father",
        "address": "Address 1",
        "phonenumber": null,
        "alt_phonenumber": null,
        "mobilenumber": null,
        "alt_mobilenumber": null,
        "email": null,
        "alt_email": null,
        "sec_address": null,
        "sec_phonenumber": null,
        "alt_sec_phonenumber": null,
        "sec_mobilenumber": null,
        "alt_sec_mobilenumber": null,
        "sec_email": null,
        "alt_sec_email": null,
        "pan": null,
        "pan_date": null,
        "gst_no": null,
        "gst_date": null,
        "place": 1,
        "sec_place": 1,
        "parent_clientid": null
}
```
    * business logic :

---

---
2. Client - Update and Delete
    * Update and Delete API for ClientMaster Model
    * URL : /operation/clientmaster-list-update/1
    * HTTP method : PUT
    * input :
```
    {
    "client_id": "Client 1",
    "category": "individual",
    "name": "Rajeev",
    "location": "Cherpulassery",
    "represented_by": "Rajeev",
    "dob": "2015-09-01",
    "gender": "male",
    "guardian": "Ramesh",
    "guardian_type": "father",
    "address": "Address 1",
    "phonenumber": null,
    "alt_phonenumber": null,
    "mobilenumber": null,
    "alt_mobilenumber": null,
    "email": null,
    "alt_email": null,
    "sec_address": null,
    "sec_phonenumber": null,
    "alt_sec_phonenumber": null,
    "sec_mobilenumber": null,
    "alt_sec_mobilenumber": null,
    "sec_email": null,
    "alt_sec_email": null,
    "pan": null,
    "pan_date": null,
    "gst_no": null,
    "gst_date": null,
    "place": 1,
    "sec_place": 1,
    "parent_clientid": null,
   "user_id" :1
}
```
* output :
```
     {
        "id": 1,
        "client_id": "Client 1",
        "category": "individual",
        "name": "Rajeev",
        "location": "Cherpulassery",
        "represented_by": "Rajeev",
        "dob": "2015-09-01",
        "gender": "male",
        "guardian": "Ramesh",
        "guardian_type": "father",
        "address": "Address 1",
        "phonenumber": null,
        "alt_phonenumber": null,
        "mobilenumber": null,
        "alt_mobilenumber": null,
        "email": null,
        "alt_email": null,
        "sec_address": null,
        "sec_phonenumber": null,
        "alt_sec_phonenumber": null,
        "sec_mobilenumber": null,
        "alt_sec_mobilenumber": null,
        "sec_email": null,
        "alt_sec_email": null,
        "pan": null,
        "pan_date": null,
        "gst_no": null,
        "gst_date": null,
        "place": 1,
        "sec_place": 1,
        "parent_clientid": null
    }
```

    * business logic  :
---

---
1. ClientBranch - List and Create
    * List and Create API for ClientBranch Model
    * URL : /operation/clientbranch-list
    * HTTP method : GET
    * input :  NA
    * output :

```
{
    "count": 1,
    "next": null,
    "previous": null,
    "results":
     
     [
            {
                "name": "Second Brancch",
                "client": 1,
                "address": "Address 2",
                "phonenumber": "",
                "mobilenumber": "",
                "email": "",
                "pan": "",
                "pan_date": null,
                "gst_no": "",
                "gst_date": null,
                "id": 2,
                "location": "location 1",
                "place": 1
            }
    ]
}

```

    * HTTP method : POST
    * input :
```
    {
        "name": "First Branch New",
        "client": 1,
        "address": "Address 1",
        "phonenumber": "",
        "mobilenumber": "",
        "email": "",
        "pan": "",
        "pan_date": null,
        "gst_no": "",
        "gst_date": null,
        "location": "location 1",
        "place": 1,
        "user_id": 1
}
```
    * output :
```
    {
        "name": "First Branch New",
        "client": 1,
        "address": "Address 1",
        "phonenumber": "",
        "mobilenumber": "",
        "email": "",
        "pan": "",
        "pan_date": null,
        "gst_no": "",
        "gst_date": null,
        "id": 4,
        "location": "location 1",
        "place": 1
    }
```
    * business logic :

---
---
2. ClientBranch - Update and Delete
    * Update and Delete API for ClientBranch Model
    * URL : /operation/clientbranch-list-update/1
    * HTTP method : PUT
    * input :
```
    {
        "name": "First Brancch New for update",
        "client": 1,
        "address": "Address 1 New",
        "phonenumber": "",
        "mobilenumber": "",
        "email": "",
        "pan": "",
        "pan_date": null,
        "gst_no": "",
        "gst_date": null,
        "user_id": 1,
        "location": "location 1",
        "place": 1
    }

```
    * output :
```
    {
        "name": "First Brancch New for update",
        "client": 1,
        "address": "Address 1 New",
        "phonenumber": "",
        "mobilenumber": "",
        "email": "",
        "pan": "",
        "pan_date": null,
        "gst_no": "",
        "gst_date": null,
        "id": 1,
        "location": "location 1",
        "place": 1
    }
```

    * business logic  :
---

---
1. EmpMaster - List and Create
    * List and Create API for EpMaster Model
    * URL : /operation/empmaster-list
    * HTTP method : GET
    * input :  NA
    * output :

```
    {
        "count": 1,
        "next": null,
        "previous": null,
        "results": [
            {
                "emp_id": "EMP ID2",
                "name": "EMP Name2",
                "address": "",
                "emptype": "advocate",
                "place": 1,
                "pan": null,
                "pan_date": null,
                "qualification": "Quali 2",
                "resume": "http://localhost:8000/uploads/uploads/emp_resume/EMP%20Name2/Case_Regn.pdf",
                "doj": null,
                "status": "active",
                "id": 2,
                "hourly_rate": "75.00"
            }
        ]
    }
```
    * HTTP method : POST
    * input :
```
    {
        "emp_id": "EMP ID1 New",
        "name": "EMP Name1 new lates",
        "address": "",
        "emptype": "advocate",
        "place": 1,
        "pan": null,
        "pan_date": null,
        "qualification": "Quali 1",
        "resume": "http://localhost:8000/uploads/uploads/emp_resume/EMP%20Name1/Client_Regn_tJjNDsu.pdf",
        "doj": null,
        "status": "active",
        "hourly_rate": "350.00",
        "user_id": 1
    }
```
    * output :
```
    {
        "emp_id": "EMP ID1 New",
        "name": "EMP Name1 new lates",
        "address": "",
        "emptype": "advocate",
        "place": 1,
        "pan": null,
        "pan_date": null,
        "qualification": "Quali 1",
        "resume": "http://localhost:8000/uploads/uploads/emp_resume/EMP%20Name1/Client_Regn_tJjNDsu.pdf",
        "doj": null,
        "status": "active",
        "id": 1,
        "hourly_rate": "50.00"
    }
```
    * business logic :
---
---
2. EmpMaster - Update and Delete
    * Update and Delete API for EmpMaster Model
    * URL : /operation/empmaster-list-update/1
    * HTTP method : PUT
    * input :
```
    {
        "emp_id": "EMP ID1 New",
        "name": "EMP Name1 new lates",
        "address": "",
        "emptype": "advocate",
        "place": 1,
        "pan": null,
        "pan_date": null,
        "qualification": "Quali 1",
        "resume": "http://localhost:8000/uploads/uploads/emp_resume/EMP%20Name1/Client_Regn_tJjNDsu.pdf",
        "doj": null,
        "status": "active",
        "hourly_rate": "350.00",
        "user_id": 1
    }

```
    * output :
```
    {
        "emp_id": "EMP ID1 New",
        "name": "EMP Name1 new lates",
        "address": "",
        "emptype": "advocate",
        "place": 1,
        "pan": null,
        "pan_date": null,
        "qualification": "Quali 1",
        "resume": "http://localhost:8000/uploads/uploads/emp_resume/EMP%20Name1/Client_Regn_tJjNDsu.pdf",
        "doj": null,
        "status": "active",
        "id": 1,
        "hourly_rate": "50.00"
    }
```

    * business logic  :
---

---
1. AssociateMaster - List and Create
    * List and Create API for AssociateMaster Model
    * URL : /operation/associatemaster-list
    * HTTP method : GET
    * input :  NA
    * output :

```
    {
        "count": 1,
        "next": null,
        "previous": null,
        "results": 
        [
            {
                "associateid": "Associate ID2",
                "name": "Associate Name 2",
                "address": "",
                "place": 1,
                "pan": null,
                "pan_date": null,
                "qualification": "Quali 2",
                "doj": null,
                "id": 2
            }
        ]
    }
```

    * HTTP method : POST
    * input :
```
    {
        "associateid": "100",
        "name": "Associate Name 100",
        "address": "",
        "place": 1,
        "pan": null,
        "pan_date": null,
        "qualification": "Quali 4",
        "doj": null,
        "user_id": 1
    }
```
    * output :
```
    {
        "associateid": "100",
        "name": "Associate Name 100",
        "address": "",
        "place": 1,
        "pan": null,
        "pan_date": null,
        "qualification": "Quali 4",
        "doj": null,
        "id": 10
    }
```
    * business logic :

---
---
2. Associate - Master Update and Delete
    * Update and Delete API for AssociateMaster Model
    * URL : /operation/associatemaster-list-update/1
    * HTTP method : PUT
    * input :
```
    {
        "associateid": "Associate ID New",
        "name": "Associate Name New Latest",
        "address": "",
        "place": 1,
        "pan": null,
        "pan_date": null,
        "qualification": "Quali 1",
        "doj": null,
        "user_id": 1
    }

```
    * output :
```
    {
        "associateid": "Associate ID New",
        "name": "Associate Name New Latest",
        "address": "",
        "place": 1,
        "pan": null,
        "pan_date": null,
        "qualification": "Quali 1",
        "doj": null,
        "id": 1
    }
```

    * business logic  :
---

---
1. BillMaster List and Create 
    * List and Create API for BillMaster Model (Nested to BillDetails)
    * URL : /operation/bill-list
    * HTTP method : GET
    * input :  NA
    * output :

```
{
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "id": 1,
            "bill_details": [
                {
                    "item_id": 1,
                    "item_fee_amt": 10.0,
                    "item_exp_amt": 10.0,
                    "remarks": "slkdjf new",
                    "id": 4
                },
                {
                    "item_id": 2,
                    "item_fee_amt": 20.0,
                    "item_exp_amt": 20.0,
                    "remarks": "slkdjf new",
                    "id": 5
                }
            ],
            "bill_id": "CRE/BM/2018-2019-001000",
            "entered_date": "2018-04-12T03:58:02.392899Z",
            "bill_date": null,
            "bill_type": "cash",
            "ref_no1": "dsds rajeev new",
            "ref_no2": "rajeev new",
            "created_from": "dfdf",
            "ac_voucher_no": "444efe",
            "ref_date1": "2018-03-19T09:19:41.459528Z",
            "ref_date2": "2018-03-19T09:19:41.459528Z",
            "service_type": "case",
            "expense_amt": "11.00",
            "fee_amt": "12.00",
            "gross_amt": "13.00",
            "disc_percentage": "1.00",
            "disc_amt": "10.50",
            "gst_code": "dfdf",
            "tds_percentage": "10.00",
            "tds_amt": "10.00",
            "cgst_percentage": "10.00",
            "cgst_amt": "10.00",
            "sgst_percentage": "10.00",
            "sgst_amt": "10.00",
            "net_amt": "10.00",
            "remarks": "dfdfd",
            "client": 1,
            "adv_id": 1,
            "case": null,
            "notice": null,
            "opinion": null,
            "documentation": null,
            "prepared_by": 1,
            "entered_by": 1,
            "authorised_by": 1
        }
    ]
}
```

    * HTTP method : POST
    * input :
```
{
     "bill_details": [
        {
            "item_id": 1,
            "item_fee_amt": 10.0,
            "item_exp_amt": 10.0,
            "remarks": "slkdjf"
    
        },
        {
            "item_id": 2,
            "item_fee_amt": 20.0,
            "item_exp_amt": 20.0,
            "remarks": "slkdjf"
        }
    ],
    "bill_id": "1",
    "date": "2018-03-20T09:19:41.459528Z",
    "bill_type": "cash",
    "ref_no1": "dsds rajeev",
    "ref_no2": "sdsd rajeev",
    "created_from": "dfdf",
    "ac_voucher_no": "444efe",
    "ref_date1": "2018-03-19T09:19:41.459528Z",
    "ref_date2": "2018-03-19T09:19:41.459528Z",
    "service_type": "case",
    "expense_amt": "11.00",
    "fee_amt": "12.00",
    "gross_amt": "13.00",
    "disc_percentage": "1.00",
    "disc_amt": "10.50",
    "gst_code": "dfdf",
    "tds_percentage": "10.00",
    "tds_amt": "10.00",
    "cgst_percentage": "10.00",
    "cgst_amt": "10.00",
    "sgst_percentage": "10.00",
    "sgst_amt": "10.00",
    "net_amt": "10.00",
    "remarks": "dfdfd",
    "prepared_by": 1,
    "entered_by": 1,
    "authorised_by": 1,
    "client": 1,
    "adv_id": 1,
    "case": null,
    "notice": null,
    "opinion": null,
    "documentation": null,
    "user_id" : 1 
}
```
    * output :
```
{
    "bill_details": [],
    "bill_id": "CRE/BM/2018-2019-001000",
    "bill_type": "cash",
    "ref_no1": "dsds rajeev",
    "ref_no2": "sdsd rajeev",
    "created_from": "dfdf",
    "ac_voucher_no": "444efe",
    "ref_date1": "2018-03-19T09:19:41.459528Z",
    "ref_date2": "2018-03-19T09:19:41.459528Z",
    "service_type": "case",
    "expense_amt": "11.00",
    "fee_amt": "12.00",
    "gross_amt": "13.00",
    "disc_percentage": "1.00",
    "disc_amt": "10.50",
    "gst_code": "dfdf",
    "tds_percentage": "10.00",
    "tds_amt": "10.00",
    "cgst_percentage": "10.00",
    "cgst_amt": "10.00",
    "sgst_percentage": "10.00",
    "sgst_amt": "10.00",
    "net_amt": "10.00",
    "remarks": "dfdfd",
    "client": 1,
    "adv_id": 1,
    "case": null,
    "notice": null,
    "opinion": null,
    "documentation": null,
    "prepared_by": 1,
    "entered_by": 1,
    "authorised_by": 1
}
```
    * business logic :

---

---
2. BillMaster Update and Delete
    * Update and Delete API for BillMaster Model (Nested to BillDetails)
    * URL : /operation/bill-update/1
    * HTTP method : PUT
    * input :
```
{
     "bill_details": [
        {
            "item_id": 1,
            "item_fee_amt": 10.0,
            "item_exp_amt": 10.0,
            "remarks": "slkdjf new"
       
        },
        { 
            "item_id": 2,
            "item_fee_amt": 20.0,
            "item_exp_amt": 20.0,
            "remarks": "slkdjf new"
 
        }
    ],
    "bill_id": "CRE/BM/2018-2019-001000",
    "entered_date": "2018-04-12T03:58:02.392899Z",
    "bill_date": null,
    "bill_type": "cash",
    "ref_no1": "dsds rajeev new",
    "ref_no2": "rajeev new",
    "created_from": "dfdf",
    "ac_voucher_no": "444efe",
    "ref_date1": "2018-03-19T09:19:41.459528Z",
    "ref_date2": "2018-03-19T09:19:41.459528Z",
    "service_type": "case",
    "expense_amt": "11.00",
    "fee_amt": "12.00",
    "gross_amt": "13.00",
    "disc_percentage": "1.00",
    "disc_amt": "10.50",
    "gst_code": "dfdf",
    "tds_percentage": "10.00",
    "tds_amt": "10.00",
    "cgst_percentage": "10.00",
    "cgst_amt": "10.00",
    "sgst_percentage": "10.00",
    "sgst_amt": "10.00",
    "net_amt": "10.00",
    "remarks": "dfdfd",
    "client": 1,
    "adv_id": 1,
    "case": null,
    "notice": null,
    "opinion": null,
    "documentation": null,
    "prepared_by": 1,
    "entered_by": 1,
    "authorised_by": 1,
    "user_id" : 1
}

```
    * output :
```
{
    "id": 1,
    "bill_details": [
        {
            "item_id": 1,
            "item_fee_amt": 10.0,
            "item_exp_amt": 10.0,
            "remarks": "slkdjf new",
            "id": 4
        },
        {
            "item_id": 2,
            "item_fee_amt": 20.0,
            "item_exp_amt": 20.0,
            "remarks": "slkdjf new",
            "id": 5
        }
    ],
    "bill_id": "CRE/BM/2018-2019-001000",
    "entered_date": "2018-04-12T03:58:02.392899Z",
    "bill_date": null,
    "bill_type": "cash",
    "ref_no1": "dsds rajeev new",
    "ref_no2": "rajeev new",
    "created_from": "dfdf",
    "ac_voucher_no": "444efe",
    "ref_date1": "2018-03-19T09:19:41.459528Z",
    "ref_date2": "2018-03-19T09:19:41.459528Z",
    "service_type": "case",
    "expense_amt": "11.00",
    "fee_amt": "12.00",
    "gross_amt": "13.00",
    "disc_percentage": "1.00",
    "disc_amt": "10.50",
    "gst_code": "dfdf",
    "tds_percentage": "10.00",
    "tds_amt": "10.00",
    "cgst_percentage": "10.00",
    "cgst_amt": "10.00",
    "sgst_percentage": "10.00",
    "sgst_amt": "10.00",
    "net_amt": "10.00",
    "remarks": "dfdfd",
    "client": 1,
    "adv_id": 1,
    "case": null,
    "notice": null,
    "opinion": null,
    "documentation": null,
    "prepared_by": 1,
    "entered_by": 1,
    "authorised_by": 1
}

    * business logic  :
---



---
1. CaseMaster - List and Create
    * List and Create API for CaseMaster Model (Nested to CaseAdvocateList and CaseAssociateList)
    * URL : /operation/case-list
    * HTTP method : GET
    * input :  NA
    * output :

```
    {
        "count": 1,
        "next": null,
        "previous": null,
        "results": [
            {
                "id": 3,
                "advocate_details": [
                    {
                        "advocate": 3,
                        "id": 3
                    },
                    {
                        "advocate": 2,
                        "id": 4
                    }
                ],
                "associate_details": [
                    {
                        "associate": 1,
                        "id": 3
                    },
                    {
                        "associate": 2,
                        "id": 4
                    }
                ],
                "case_id": "RAJ/CM/2017-2018-001001",
                "entered_date": "2018-03-27",
                "case_no1": "1",
                "case_no2": "2",
                "case_subject_remarks": "rem",
                "case_remarks": "crem",
                "other_remarks": "orem",
                "parent_ia": null,
                "who": "Rajeev",
                "whom": "Rajesh",
                "other_professional": "Ramesh",
                "opposite_adv": "Keshav",
                "case_engaged_date": "2018-03-19",
                "case_filed_date": "2018-03-19",
                "case_first_appearance_date": "2018-03-19",
                "case_reminder_date": "2018-03-19",
                "case_reminder_details": "Case Reminder",
                "some_reference_no": "Ref 1",
                "court_type": 1,
                "client": 1,
                "case_subject": 1,
                "case_type": 1,
                "parent_case": null,
                "referral_case": null,
                "status": 1
            }
        ]
    }

```

    * HTTP method : POST
    * input :
```
    {
        "case_no1": "101",
        "case_no2": "201",
        "case_subject_remarks": "rem",
        "case_remarks": "crem",
        "other_remarks": "orem",
        "parent_case": null,
        "referral_case": null,
        "parent_ia": null,
        "who": "Rajeev AM",
        "whom": "Rajesh M",
        "other_professional": "Ramesh",
        "opposite_adv": "Keshav",
        "case_engaged_date": "2018-03-19",
        "case_filed_date": "2018-03-19",
        "case_first_appearance_date": "2018-03-19",
        "case_reminder_date": "2018-03-19",
        "case_reminder_details": "Case Reminder ",
        "some_reference_no": "Ref 1",
        "court_type": 1,
        "client": 1,
        "case_subject": 1,
        "case_type": 1,
        "status": 1,
        "user_id":1,
        "advocate_details": [
           {
             "advocate": 3
           },
           {
             "advocate": 2
           }
         ],
        "associate_details": [
             {
             "associate": 2
           }
         ]
    }

```
    * output :
```
    {
        "advocate_details": [],
        "associate_details": [],
        "case_id": "RAJ/CM/2018-2019-001002",
        "case_no1": "101",
        "case_no2": "201",
        "case_subject_remarks": "rem",
        "case_remarks": "crem",
        "other_remarks": "orem",
        "parent_ia": null,
        "who": "Rajeev AM",
        "whom": "Rajesh M",
        "other_professional": "Ramesh",
        "opposite_adv": "Keshav",
        "case_engaged_date": "2018-03-19",
        "case_filed_date": "2018-03-19",
        "case_first_appearance_date": "2018-03-19",
        "case_reminder_date": "2018-03-19",
        "case_reminder_details": "Case Reminder",
        "some_reference_no": "Ref 1",
        "court_type": 1,
        "client": 1,
        "case_subject": 1,
        "case_type": 1,
        "parent_case": null,
        "referral_case": null,
        "status": 1
    }
```
    * business logic :

---
---
2. CaseMaster - Update and Delete
    * Update and Delete API for CaseMaster Model (Nested to CaseAdvocateList and CaseAssociateList)
    * URL : /operation/case-update/4
    * HTTP method : PUT
    * input :
```
    {
        "advocate_details": [
            {
                "advocate": 3
            },
            {
                "advocate": 2
            }
        ],
        "associate_details": [
            {
                "associate": 2
            }
        ],
        "case_id": "RAJ/CM/2018-2019-001002",
        "entered_date": "2018-04-10",
        "case_no1": "101",
        "case_no2": "201",
        "case_subject_remarks": "rem",
        "case_remarks": "crem",
        "other_remarks": "orem",
        "parent_ia": null,
        "who": "Rajeev AM",
        "whom": "Rajesh M",
        "other_professional": "Ramesh",
        "opposite_adv": "Keshav",
        "case_engaged_date": "2018-03-19",
        "case_filed_date": "2018-03-19",
        "case_first_appearance_date": "2018-03-19",
        "case_reminder_date": "2018-03-19",
        "case_reminder_details": "Case Reminder",
        "some_reference_no": "Ref 1",
        "court_type": 1,
        "client": 1,
        "case_subject": 1,
        "case_type": 1,
        "parent_case": null,
        "referral_case": null,
        "status": 1,
        "user_id": 1
    }

```
    * output :
```
    {
        "id": 4,
        "advocate_details": [],
        "associate_details": [],
        "case_id": "RAJ/CM/2018-2019-001002",
        "entered_date": "2018-04-10",
        "case_no1": "101",
        "case_no2": "201",
        "case_subject_remarks": "rem",
        "case_remarks": "crem",
        "other_remarks": "orem",
        "parent_ia": null,
        "who": "Rajeev AM",
        "whom": "Rajesh M",
        "other_professional": "Ramesh",
        "opposite_adv": "Keshav",
        "case_engaged_date": "2018-03-19",
        "case_filed_date": "2018-03-19",
        "case_first_appearance_date": "2018-03-19",
        "case_reminder_date": "2018-03-19",
        "case_reminder_details": "Case Reminder",
        "some_reference_no": "Ref 1",
        "court_type": 1,
        "client": 1,
        "case_subject": 1,
        "case_type": 1,
        "parent_case": null,
        "referral_case": null,
        "status": 1
    }

```

    * business logic  :
---


 
---
1. NoticeMaster List and Create
    * List and Create API for NotieMaster Model (Nested to NoticeAdvocateList and NoticeAssociateList)
    * URL : /operation/notice-list
    * HTTP method : GET
    * input :  NA
    * output :

```
    {
        "count": 1,
        "next": null,
        "previous": null,
        "results": [
            {
                "id": 2,
                "advocate_details": [
                    {
                        "advocate": 1,
                        "id": 3
                    }
                ],
                "associate_details": [
                    {
                        "associate": 1,
                        "id": 1
                    },
                    {
                        "associate": 1,
                        "id": 2
                    }
                ],
                "notice_id": "CRE/NM/2018-2019-001000",
                "entered_date": "2018-04-12",
                "notice_remarks": "crem",
                "notice_engaged_date": "2018-03-19",
                "notice_reminder_date": "2018-03-19",
                "notice_reminder_details": "Notice Reminder",
                "other_professional": "Ramesh",
                "who": "Rajeev New",
                "whom": "Rajesh New",
                "client": 1,
                "notice_subject": 1
            }
        ]
    }
```
    * HTTP method : POST
    * input :
```
    {
        "notice_remarks": "crem",
        "other_remarks": "orem",
        "who": "Rajeev",
        "whom": "Rajesh",
        "other_professional": "Ramesh",
        "notice_engaged_date": "2018-03-19",
        "notice_reminder_date": "2018-03-19",
        "notice_reminder_details": "Notice Reminder ",
        "client": 1,
        "notice_subject": 1,
        "user_id":1,
        "notice_id" : 1,
        "advocate_details": [
           {
             "advocate": 1
           } 
         ],
        "associate_details": [
           {
             "associate": 1
           } 
         ]
    }
```
    * output :
```
    {
        "advocate_details": [],
        "associate_details": [],
        "notice_id": "CRE/NM/2018-2019-001000",
        "notice_remarks": "crem",
        "notice_engaged_date": "2018-03-19",
        "notice_reminder_date": "2018-03-19",
        "notice_reminder_details": "Notice Reminder",
        "other_professional": "Ramesh",
        "who": "Rajeev",
        "whom": "Rajesh",
        "client": 1,
        "notice_subject": 1
    }
```
    * business logic :

---
---
2. NoticeMaster Update and Delete
    * Update and Delete API for NoticeMaster Model (Nested NoticeAdvocateList and NoticeAssociateList)
    * URL : /operation/notice-update/2
    * HTTP method : PUT
    * input :
```
{
    "id": 2,
    "advocate_details": [
        {
            "advocate": 1,
            "id": 2
        }
    ],
    "associate_details": [
        {
            "associate": 1,
            "id": 1
        }
    ],
    "notice_id": "CRE/NM/2018-2019-001000",
    "entered_date": "2018-04-12",
    "notice_remarks": "crem",
    "notice_engaged_date": "2018-03-19",
    "notice_reminder_date": "2018-03-19",
    "notice_reminder_details": "Notice Reminder",
    "other_professional": "Ramesh",
    "who": "Rajeev",
    "whom": "Rajesh",
    "client": 1,
    "notice_subject": 1
}

```
    * output :
```
    {
        "id": 2,
        "advocate_details": [],
        "associate_details": [],
        "notice_id": "CRE/NM/2018-2019-001000",
        "entered_date": "2018-04-12",
        "notice_remarks": "crem",
        "notice_engaged_date": "2018-03-19",
        "notice_reminder_date": "2018-03-19",
        "notice_reminder_details": "Notice Reminder",
        "other_professional": "Ramesh",
        "who": "Rajeev New",
        "whom": "Rajesh New",
        "client": 1,
        "notice_subject": 1
    }
```

    * business logic  :
---

  
---
1. OpinionMaster List and Create
    * List and Create API for OpinionMaster Model (Nested to OpinionAdvocateList and OpionionAssociateList)
    * URL : /operation/opinion-list
    * HTTP method : GET
    * input :  NA
    * output :

```
    {
        "count": 1,
        "next": null,
        "previous": null,
        "results": [
            {
                "id": 1,
                "advocate_details": [
                    {
                        "advocate": 1,
                        "id": 2
                    }
                ],
                "associate_details": [
                    {
                        "associate": 1,
                        "id": 2
                    }
                ],
                "opinionid": "CRE/OM/2018-2019-001000",
                "entered_date": "2018-04-12",
                "matter_name": "Matter Name - Opinion New",
                "other_professional": "Ramesh New",
                "opinion_remarks": "orem new",
                "engaged_date": "2018-03-19",
                "reminder_date": "2018-03-19",
                "reminder_details": "Notice Reminder",
                "client_reference_no": null,
                "clientid": 1,
                "opinion_subjectid": 1
            }
        ]
    }
```

    * HTTP method : POST
    * input :
```
    {
        "opinion_remarks": "orem",
        "matter_name": "Matter Name - Opinion",
        "other_professional": "Ramesh",
        "engaged_date": "2018-03-19",
        "reminder_date": "2018-03-19",
        "reminder_details": "Notice Reminder ",
        "clientid": 1,
        "opinion_subjectid": 1,
        "user_id":1,
        "opinionid" : 1,
        "advocate_details": [
           {
             "advocate": 1
           } 
         ],
        "associate_details": [
           {
             "associate": 1
           } 
         ]
    }

```
    * output :
```
    {
        "advocate_details": [],
        "associate_details": [],
        "opinionid": "CRE/OM/2018-2019-001000",
        "matter_name": "Matter Name - Opinion",
        "other_professional": "Ramesh",
        "opinion_remarks": "orem",
        "engaged_date": "2018-03-19",
        "reminder_date": "2018-03-19",
        "reminder_details": "Notice Reminder",
        "clientid": 1,
        "opinion_subjectid": 1
    }
 

```
    * business logic :

---
---
2.  OpinionMaster Update and Delete
    * Update and Delete API for OpinionMaster Model (Nested to OpinionAdvocateList and OpinionAssocaiteList) 
    * URL : /operation/opinion-update/1
    * HTTP method : PUT
    * input :
```
{
  
    "advocate_details": [
        {
            "advocate": 1
   
        }
    ],
    "associate_details": [
        {
            "associate": 1
 
        }
    ],
    "opinionid": "CRE/OM/2018-2019-001000",
    "entered_date": "2018-04-12",
    "matter_name": "Matter Name - Opinion New",
    "other_professional": "Ramesh New",
    "opinion_remarks": "orem new",
    "engaged_date": "2018-03-19",
    "reminder_date": "2018-03-19",
    "reminder_details": "Notice Reminder",
    "client_reference_no": null,
    "clientid": 1,
    "opinion_subjectid": 1,
    "user_id" :1
}

```
    * output :
```
    {
        "id": 1,
        "advocate_details": [],
        "associate_details": [],
        "opinionid": "CRE/OM/2018-2019-001000",
        "entered_date": "2018-04-12",
        "matter_name": "Matter Name - Opinion New",
        "other_professional": "Ramesh New",
        "opinion_remarks": "orem new",
        "engaged_date": "2018-03-19",
        "reminder_date": "2018-03-19",
        "reminder_details": "Notice Reminder",
        "client_reference_no": null,
        "clientid": 1,
        "opinion_subjectid": 1
    }
```

    * business logic  :
---

 
1. DocumentationMaster List and Create
    * List and Create API for DocumentationMaster Modelv(nested to DoumentationAdvocateDetails and DoumentationAssociateDetails)
    * URL : /operation/documentation-list
    * HTTP method : GET
    * input :  NA
    * output :

```
    {
        "count": 1,
        "next": null,
        "previous": null,
        "results": [
            {
                "id": 1,
                "advocate_details": [
                    {
                        "advocate": 1,
                        "id": 2
                    }
                ],
                "associate_details": [
                    {
                        "associate": 1,
                        "id": 2
                    }
                ],
                "documentation_id": "CRE/DM/2018-2019-001000",
                "entered_date": "2018-04-12",
                "doctype": "single",
                "identification_name": "Identification Name....new",
                "other_professional": "Ramesh new",
                "client_reference_no": null,
                "doc_remarks": "docrem",
                "engaged_date": "2018-03-19",
                "reminder_date": "2018-03-19",
                "reminder_details": "Documentation Reminder new",
                "clientid": 1,
                "subjectid": 1
            }
        ]
    }
```

    * HTTP method : POST
    * input :
```
    {
        "doc_remarks": "docrem",
        "other_professional": "Ramesh",
        "engaged_date": "2018-03-19",
        "reminder_date": "2018-03-19",
        "reminder_details": "Documentation Reminder ",
         "identification_name": "Identification Name.... ",
         "doctype": "single",
        "clientid": 1,
        "subjectid": 1,
        "user_id":1,
        "documentation_id" : 1,
        "advocate_details": [
           {
             "advocate": 1
           } 
         ],
        "associate_details": [
           {
             "associate": 1
           } 
         ]
    }
```
    * output :
```
    {
        "advocate_details": [],
        "associate_details": [],
        "documentation_id": "CRE/DM/2018-2019-001000",
        "doctype": "single",
        "identification_name": "Identification Name....",
        "other_professional": "Ramesh",
        "doc_remarks": "docrem",
        "engaged_date": "2018-03-19",
        "reminder_date": "2018-03-19",
        "reminder_details": "Documentation Reminder",
        "clientid": 1,
        "subjectid": 1
    }
```
    * business logic :

---
---
2. DocumentationMaster Update and Delete
    * Update and Delete API for DocumentationMaster Model (Nested to DocumentationAdvocateList and DocumentationAssociateList)
    * URL : /operation/documentation-update/1
    * HTTP method : PUT
    * input :
```
{
    "user_id": 1,
    "advocate_details": [
        {
            "advocate": 1
 
        }
    ],
    "associate_details": [
        {
            "associate": 1
  
        }
    ],
    "documentation_id": "CRE/DM/2018-2019-001000",
    "entered_date": "2018-04-12",
    "doctype": "single",
    "identification_name": "Identification Name....new",
    "other_professional": "Ramesh new",
    "client_reference_no": null,
    "doc_remarks": "docrem",
    "engaged_date": "2018-03-19",
    "reminder_date": "2018-03-19",
    "reminder_details": "Documentation Reminder new",
    "clientid": 1,
    "subjectid": 1
}

```
    * output :
```
    {
        "id": 1,
        "advocate_details": [],
        "associate_details": [],
        "documentation_id": "CRE/DM/2018-2019-001000",
        "entered_date": "2018-04-12",
        "doctype": "single",
        "identification_name": "Identification Name....new",
        "other_professional": "Ramesh new",
        "client_reference_no": null,
        "doc_remarks": "docrem",
        "engaged_date": "2018-03-19",
        "reminder_date": "2018-03-19",
        "reminder_details": "Documentation Reminder new",
        "clientid": 1,
        "subjectid": 1
    }
```

    * business logic  :
---

  
---
1. OthersMaster List and Create
    * List and Create API for OthersMaster Model (nested to OtherAdvoateList and OtherAssociateList)
    * URL : /operation/other-list
    * HTTP method : GET
    * input :  NA
    * output :

```
    {
        "count": 1,
        "next": null,
        "previous": null,
        "results": [
            {
                "id": 1,
                "advocate_details": [
                    {
                        "advocate": 1,
                        "id": 2
                    }
                ],
                "associate_details": [
                    {
                        "associate": 1,
                        "id": 2
                    }
                ],
                "code": "CRE/OTHM/2018-2019-001000",
                "name": "oth rem new",
                "entered_date": "2018-04-12",
                "engaged_date": "2018-03-19",
                "clientid": 1
            }
        ]
    }
```

    * HTTP method : POST
    * input :
```
    {
        "name": "docrem",
        "engaged_date": "2018-03-19",
        "clientid": 1,
        "user_id":1,
        "code" : 1,
        "advocate_details": [
           {
             "advocate": 1
           } 
         ],
        "associate_details": [
           {
             "associate": 1
           } 
         ]
    }
```
    * output :
```
    {
        "advocate_details": [],
        "associate_details": [],
        "code": "CRE/OTHM/2018-2019-001000",
        "name": "docrem",
        "engaged_date": "2018-03-19",
        "clientid": 1
    }
```
    * business logic :

---
---
2. OthersMaster Update and Delete
    * Update and Delete API for OthersMaster Model (Nested to OthersAdvocateList and OthersAssociateList)
    * URL : /operation/others-update/1
    * HTTP method : PUT
    * input :
```
{
  
    "advocate_details": [
        {
            "advocate": 1 
        }
    ],
    "associate_details": [
        {
            "associate": 1 
        }
    ],
    "code": "CRE/OTHM/2018-2019-001000",
    "name": "oth rem new",
    "entered_date": "2018-04-12",
    "engaged_date": "2018-03-19",
    "clientid": 1,
    "user_id" : 1
}

```
    * output :
```
    {
        "id": 1,
        "advocate_details": [],
        "associate_details": [],
        "code": "CRE/OTHM/2018-2019-001000",
        "name": "oth rem new",
        "entered_date": "2018-04-12",
        "engaged_date": "2018-03-19",
        "clientid": 1
    }
```

    * business logic  :
---

