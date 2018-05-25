# Account Manager
---
1. Group List and Create
    * List and Create API for Group Model
    * URL : /account/group-create/
    * input : NA
    * HTTP method : GET
    * output
        ```
        {
            "count": 1,
            "next": null,
            "previous": null,
            "results": [
                {
                    "name": "maingroup",
                    "groups": "asset",
                    "code": "ABC123",
                    "print_order_number": 1,
                    "ref_no": "sdfsdf",
                    "history": 4,
                    "id": 1
                }
        }
       }
       ```

    * business logic
---
2. Group Update and Delete
    * Description
    * url
    *   ``` 

        sldkfjsldkf
        ```

    * HTTP method
    * output
    * business login



# Operations

---
1. CaseRemarks Create
    * List and Create API for Group Model
    * URL: /operation/caseremarks-list/
    * input:  
            {
    "name": "caseremarks name 2",
    "code": "case remarks code",
    "entered_date": "2018-02-03",
    "remarks": "caseremarks remarks ",
    "case": 1,
    "user_id":1
        }
    * HTTP method : POST
    * OUTPUT : 
                {
    "name": "caseremarks name 2",
    "code": "case remarks code",
    "entered_date": "2018-02-03",
    "remarks": "caseremarks remarks",
    "id": 1,
    "case": 1
    }

2. CaseRemarks Update
    * Update Created API
    * URL: /operation/caseremarks-list-update/1
    * Input:
            {
        "name": "caseremarks name 2 updated",
        "code": "case remarks code",
        "entered_date": "2018-02-03",
        "remarks": "caseremarks remarks",
        "id": 1,
        "case": 1,
        "user_id":1
    }
    * HTTP Method: PUT
    * OUTPUT: 

    {
        "name": "caseremarks name 2 updated",
        "code": "case remarks code",
        "entered_date": "2018-02-03",
        "remarks": "caseremarks remarks",
        "id": 1,
        "case": 1,
        "user_id":1
    }

3. CaseSubject 
    * List API for Group model
    * URL: /operation/casesubject-list
    * Input:NA
    * Output: 
            {
    "count": 2,
    "next": null,
    "previous": null,
    "results":  [
            {
                "case_subjectid": "test",
                "case_subject_name": "test name",
                "id": 3
            },
            {
                "case_subjectid": "casesubject id 1 updated twice",
                "case_subject_name": "case subject name 2",
                "id": 1
            }
        ]
    }


    * Create API for Group model
    * URL: /operation/casesubject-lis
    * Input: 
            {
    "case_subjectid": "casesubject id 1",
    "case_subject_name": "casesubject name 2",
    "user_id":1
            }
    * HTTP Method : POST
    * OUTPUT:
    {
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "case_subjectid": "casesubject id 1",
            "case_subject_name": "case subject name 2",
            "id": 1,
            "history": 1
        }
    ]
}

4. Casesubject Update
    * Update and delete API for Group Model
    * URL: /operation/casesubject-list-update/1
    * Input: 
            {
        "case_subjectid": "casesubject id 1 updated twice",
        "case_subject_name": "case subject name 2",
        "id": 1,
        "user_id":1
            }
    * HTTP Method : POST
    * OUTPUT:
            
            {
        "case_subjectid": "casesubject id 1 updated twice",
        "case_subject_name": "case subject name 2",
        "id": 1
            }

5. Casesubject List
    * List API
    * URL: /operation/casesubject-all/
    * Input: NA
    * Output: 
                {
        "count": 2,
        "next": null,
        "previous": null,
        "results": [
            {
                "id": 3,
                "name": "test name"
            }   ,
            {
                "id": 1,
                "name": "case subject name 2"
            }
        ]
    }

6. ActivityMaster
    * List API for Group model
    * URL: /operation/activity-list/
    * Input:NA
    * Output:   {
        "count": 1,
        "next": null,
        "previous": null,
        "results": [
            {
                "activity_id": "activity id 1",
                "activity_name": "activity name 1",
                "id": 1
            }
        ]
    }

    * Create API for Group model
    * URL: /operation/casesubject-list
    * Input: 
                {
        "activity_id": "activity id 1",
        "activity_name": "activity name 1",
        "user_id":1
    }

7. ActivityMaster Update
    * Update and delete API for Group Model
    * URL: /operation/casesubject-list-update/1
    * Input:    {
        "activity_id": "activity id 1",
        "activity_name": "activity name 1",
        "user_id":1
    }
    * Output:
            {
        "count": 1,
        "next": null,
        "previous": null,
        "results": [
            {
                "activity_id": "activity id 1",
                "activity_name": "activity name 1",
                "id": 1
            }
        ]
    }

8. StateMaster
    * List API for Group model
    * URL: /operation/statemaster-list/
    * Input:NA
    * Output: {
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
            {
                "state_name": "kerala",
                "country": "IN",
                "id": 1
            }
        ]
    }

    * Create API for Group model
    * URL: /operation/StateMaster-list
    * Input: 
                {
        "state_name": "",
        "country": null,
        "user_id":1
    }
    * Output:
                {
        "count": 1,
        "next": null,
        "previous": null,
        "results": [
            {
                "state_name": "kerala",
                "country": "IN",
                "id": 1
            }
        ]
    }

8. StateMaster Update
    * Update and delete API for Group Model
    * URL: /operation/statemaster-list-update/1
    * Input:   {
        "state_name": "kerala",
        "country": "IN",
        "id": 1,
        "user_id":1
    }
    * Output:
          {
        "state_name": "kerala update",
        "country": "IN",
        "id": 1
    }

8. DistrictMaster
    * List API for Group model
    * URL: /operation/Districtmaster-list/
    * Input:NA
    * Output:{
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "name": "ernakulam",
            "id": 1,
            "state": 1
        }
    ]

    * Create API for Group model
    * URL: /operation/DistrictMaster-list
    * Input: 
            {
        "name": "ernakulam",
        "state": 1,
        "user_id":1
    }
}
    * Output:
                {
    "name": "ernakulam",
    "id": 2,
    "state": 1
}

8. DistrictMaster Update
    * Update and delete API for Group Model
    * URL: /operation/districtmaster-list-update/2
    * Input:   {
    "name": "ernakulam update",
    "id": 2,
    "state": 1,
"user_id":1
}
    * Output:
          {
    "name": "ernakulam",
    "id": 2,
    "state": 1
}

9. PlaceMaster
    * List API for Group model
    * URL: /operation/Placemaster-list/
    * Input:NA
    * Output:{
        "count": 2,
        "next": null,
        "previous": null,
        "results": [
        {
            "name": "ernakulam",
            "id": 1,
            "district": 1
        },
        {
            "name": "njarakal",
            "id": 2,
            "district": 1
            }
        ]
    }

    * Create API for Group model
    * URL: /operation/PlaceMaster-list
    * Input: 
           {
        "name": "hospital jn",
        "district": 1,
        "user_id":1
        }
    }
    * Output:
              
        {
        "name": "hospital jn",
        "id": 3,
        "district": 1   
        }
10. PlaceMaster Update
    * Update and delete API for Group Model
    * URL: /operation/placemaster-list-update/2
    * Input:   {
    "name": "hospital jn update",
    "id": 3,
    "district": 1,
    "user_id":1
    }
    * Output:
         {
    "name": "hospital jn",
    "id": 3,
    "district": 1
    }


11. BillItemHead
    * List API for Group model
    * URL: /operation/billitem-list/
    * Input:NA
    * Output: {
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "bill_id": "bill id 1",
            "name": "bill name 1",
            "bill_type": "fee",
            "id": 1
        }
    ]
    }
    Create API for Group BillItemHead
    * URL: /operation/billitem-list/
    * Input: 
           {
    "bill_id": "bill id 1",
    "name": "bill name 1",
    "bill_type":"fee",
    "user_id":1
    }
    }
    * Output:
              
        {
            "bill_id": "bill id 1",
            "name": "bill name 1",
            "bill_type": "fee",
            "id": 1
        }

12. BillItemHead Update
    * Update and delete API for Group Model
    * URL: /operation/billitem-list-update/1
    * Input:   {
    "bill_id": "bill id 1",
    "name": "bill item name update",
    "bill_type": "fee",
    "user_id":1
    }
    * Output:
        {
    "bill_id": "bill id 1",
    "name": "bill item name update",
    "bill_type": "fee",
    "id": 2
    }

13. Courts
    * List API for Group Courts
    * URL: /operation/courts-list/
    * Input:NA
    * Output:{
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "name": "court 1",
            "place": 1,
            "court_type": 1,
            "id": 1
        }
    ]
    }
    Create API for Group Courts
    * URL: /operation/courts-list/
    * Input: 
           {
    "name": "court 1",
    "place": 1,
    "court_type": 1,
    "id": 1,
    "user_id":1
    }
    }
    * Output:
              
        {
    "name": "court 1",
    "place": 1,
    "court_type": 1,
    "id": 1
    }

14. Courts Update
    * Update and delete API for Group Courts
    * URL: /operation/Courts-list-update/1
    * Input:   {
    "name": "Courts 1 update",
    "place": 1,
    "court_type": 1,
    "user_id":1
    }
    * Output:
       {
    "name": "Courts 1 update",
    "place": 1,
    "court_type": 1,
    "id": 2
    }

15. Caseremarks
    * List API for Group Caseremarks
    * URL: /operation/caseremarks-list/
    * Input:NA
    * Output:{
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "name": "caseremarks name 2",
            "code": "case remarks code",
            "entered_date": "2018-02-03",
            "remarks": "caseremarks remarks",
            "id": 1,
            "case": 1
        }
    ]
    }
    Create API for Group Caseremarks
    * URL: /operation/caseremarks-list/
    * Input: 
           {
    "name": "case remarks name 1",
    "code": "1",
    "entered_date": "2018-05-04",
    "remarks": "caseremarks remarks",
    "case": 1,
    "user_id": 1
    }
    }
    * Output:
              
       {
    "name": "case remarks name 1",
    "code": "1",
    "entered_date": "2018-05-04",
    "remarks": "caseremarks remarks",
    "id": 2,
    "case": 1
    }

16. Caseremarks Update
    * Update and delete API for Group Caseremarks
    * URL: /operation/caseremarks-list-update/2
    * Input:  {
    "name": "case remarks name 1 update",
    "code": "1",
    "entered_date": "2018-05-04",
    "remarks": "caseremarks remarks",
    "id": 2,
    "case": 1,
    "user_id":1
    }
    * Output:
       {
    "name": "case remarks name 1",
    "code": "1",
    "entered_date": "2018-05-04",
    "remarks": "caseremarks remarks",
    "id": 2,
    "case": 1
    }

17. CaseThingstodo
    * List API for Group Casethingstodo
    * URL: /operation/casethingstodo-list
    * Input:NA
    * Output:{
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "name": "casethingstodo name 1",
            "code": "case things todo code 1",
            "entered_date": "2018-04-19",
            "todo_date": "2018-04-05",
            "case": 1,
            "description": "abcd",
            "id": 1
        }
    ]
    }
    Create API for Group Casethingstodo
    * URL: /operation/casethingstodo-list/
    * Input: 
          {
    "name": "casethingstodo name 1",
    "code": "case things todo code 1",
    "todo_date": "2018-04-05",
    "case": 1,
    "description": "abcd",
    "user_id":1
    }
    * Output:
              
      {
    "name": "casethingstodo name 1",
    "code": "case things todo code 1",
    "entered_date": "2018-04-19",
    "todo_date": "2018-04-05",
    "case": 1,
    "description": "abcd",
    "id": 1
}

18. Casethingstodo Update
    * Update and delete API for Group Casethingstodo
    * URL: /operation/casethingstodo-list-update/1
    * Input: {
    "name": "casethingstodo name 1 updated",
    "code": "case things todo code 1",
    "entered_date": "2018-04-19",
    "todo_date": "2018-04-05",
    "case": 1,
    "description": "abcd updated",
    "id": 1,
    "user_id":1
    }
    * Output:
      {
    "name": "casethingstodo name 1 updated",
    "code": "case things todo code 1",
    "entered_date": "2018-04-19",
    "todo_date": "2018-04-05",
    "case": 1,
    "description": "abcd updated",
    "id": 1
    }

19. Casereminder
    * List API for Group Casereminder
    * URL: /operation/casereminder-list/
    * Input:NA
    * Output:
    {
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "name": "casereminder name 1",
            "code": "case reminder code 1",
            "entered_date": "2018-04-19",
            "reminder_date": "2018-02-03",
            "case": 1,
            "description": "abcd",
            "id": 1
        }
    ]
    }
    Create API for Group Casereminder
    * URL: /operation/casereminder-list/
    * Input: 
          {
    "name": "casereminder name 1",
    "code": "case reminder code 1",
    "reminder_date": "2018-02-03",
    "case": 1,
    "description": "abcd",
    "user_id":1

    }
    * Output:
              
    {
            "name": "casereminder name 1",
            "code": "case reminder code 1",
            "entered_date": "2018-04-19",
            "reminder_date": "2018-02-03",
            "case": 1,
            "description": "abcd",
            "id": 1
    }

20. Casereminder Update
    * Update and delete API for Group Casereminder
    * URL: /operation/casereminder-list-update/1
    * Input: {
    "name": "casereminder name 1 updated",
    "code": "case reminder code 1",
    "entered_date": "2018-04-19",
    "reminder_date": "2018-02-03",
    "case": 1,
    "description": "abcd updated",
    "id": 1,
    "user_id":1
    }
    * Output:
     {
    "name": "casereminder name 1 updated",
    "code": "case reminder code 1",
    "entered_date": "2018-04-19",
    "reminder_date": "2018-02-03",
    "case": 1,
    "description": "abcd updated",
    "id": 1
    }

21. Opinion Remarks
    * List API for Group Opinion Remarks
    * URL: /operation/opinionremarks-list/
    * Input:NA
    * Output:
    {
    "count": 2,
    "next": null,
    "previous": null,
    "results": [
        {
            "name": "opinion remarks name 1",
            "code": "code 1",
            "entered_date": "2018-04-20",
            "remarks": "",
            "id": 1,
            "opinion": 1
        },
        {
            "name": "opinion remarks name 1",
            "code": "opinion remarks code 1",
            "entered_date": "2018-04-20",
            "remarks": "opinion remarks bla bla",
            "id": 2,
            "opinion": 1
        }
    ]
    }
    Create API for Group opinion remarks
    * URL: /operation/opinionremarks-list/
    * Input: 
         {
    "name": "opinion remarks name 1",
    "code": "opinion remarks code 1",
    "remarks": "opinion remarks bla bla",
    "opinion": 1,
    "user_id":1
    }
    * Output:
              
    {
    "name": "opinion remarks name 1",
    "code": "opinion remarks code 1",
    "entered_date": "2018-04-20",
    "remarks": "opinion remarks bla bla",
    "id": 2,
    "opinion": 1
    }

22. Opinion Remarks Update
    * Update and delete API for Group Opinion remarks
    * URL: /operation/opinionremarks-list-update/2
    * Input:{
    "name": "opinion remarks name 1 updated",
    "code": "opinion remarks code 1",
    "entered_date": "2018-04-20",
    "remarks": "opinion remarks bla bla updated",
    "id": 2,
    "opinion": 1,
    "user_id":1
    }
    * Output:
     {
    "name": "opinion remarks name 1 updated",
    "code": "opinion remarks code 1",
    "entered_date": "2018-04-20",
    "remarks": "opinion remarks bla bla updated",
    "id": 2,
    "opinion": 1
    }

23. Opinion Thingstodo
    * List API for Group Opinion Thingstodo
    * URL: /operation/opinionthingstodo-list/
    * Input:NA
    * Output:
    {
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "name": "opinion things todo",
            "code": "opinion code",
            "entered_date": "2018-04-26",
            "description": "opinion descrptn",
            "id": 1,
            "opinion": 1,
            "todo_date": "2018-03-02"
        }
    ]
    }
    Create API for Group Opinion thingstodo
    * URL: /operation/opinionthingstodo-list/
    * Input: 
          {
            "name": "opinion things todo",
            "code": "opinion code",
            "description": "opinion descrptn",
            "opinion": 1,
            "todo_date": "2018-03-02"
        }
    * Output:
              
     {
            "name": "opinion things todo",
            "code": "opinion code",
            "entered_date": "2018-04-26",
            "description": "opinion descrptn",
            "id": 1,
            "opinion": 1,
            "todo_date": "2018-03-02"
        }

24. Opinion Thingstodo Update
    * Update and delete API for Group Opinion thingstodo
    * URL: /operation/opinionthingstodo-list-update/1
    * Input:{
    "name": "opinion things todo updated",
    "code": "opinion code updated",
    "entered_date": "2018-04-26",
    "description": "opinion descrptn updated",
    "id": 1,
    "opinion": 1,
    "todo_date": "2018-03-02",
    "user_id":1
    }
    * Output:
     {
    "name": "opinion things todo updated",
    "code": "opinion code updated",
    "entered_date": "2018-04-26",
    "description": "opinion descrptn updated",
    "id": 1,
    "opinion": 1,
    "todo_date": "2018-03-02"
    }

25. Opinion Reminder
    * List API for Group Opinion Reminder
    * URL: /operation/opinionreminder-list/
    * Input:NA
    * Output:
    
    {
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "name": "opinion reminder name",
            "code": "opinion reminder code",
            "entered_date": "2018-04-26",
            "description": "opinion reminder descrptn",
            "id": 1,
            "opinion": 1,
            "reminder_date": "2018-04-02"
        }
    ]
    }
    Create API for Group Opinion reminder
    * URL: /operation/opinionreminder-list/
    * Input: 
          {
    "name": "opinion reminder name",
    "code": "opinion reminder code",
    "description": "opinion reminder descrptn",
    "opinion": 1,
    "reminder_date": "2018-04-02",
    "user_id":1
    }
    * Output:
              
     {
    "name": "opinion reminder name",
    "code": "opinion reminder code",
    "entered_date": "2018-04-26",
    "description": "opinion reminder descrptn",
    "id": 1,
    "opinion": 1,
    "reminder_date": "2018-04-02"
    }

26. Opinion Reminder Update
    * Update and delete API for Group Opinion reminder
    * URL: /operation/opinionreminder-list-update/1
    * Input:{
    "name": "opinion reminder name updated",
    "code": "opinion reminder code updated",
    "entered_date": "2018-04-26",
    "description": "opinion reminder descrptn",
    "id": 1,
    "opinion": 1,
    "reminder_date": "2018-04-02",
    "user_id":1
    }
    * Output:
     {
    "name": "opinion reminder name updated",
    "code": "opinion reminder code updated",
    "entered_date": "2018-04-26",
    "description": "opinion reminder descrptn",
    "id": 1,
    "opinion": 1,
    "reminder_date": "2018-04-02"
    }

27.  Notice Remarks
    * List API for Group Notice Remarks
    * URL: /operation/noticeremarks-list/
    * Input:NA
    * Output:
    
    {
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "name": "notice remarks name",
            "code": "notice remarks code",
            "entered_date": "2018-04-05",
            "remarks": "notice remarks",
            "id": 1,
            "notice": 1
        }
    ]
    }
    Create API for Group Notice remarks
    * URL: /operation/noticeremarks-list/
    * Input: 
          {
    "name": "notice remarks name",
    "code": "notice remarks code",
    "entered_date": "2018-04-05",
    "remarks": "notice remarks",
    "notice": 1,
    "user_id":1
    }
    * Output:
              
     {
    "name": "notice remarks name",
    "code": "notice remarks code",
    "entered_date": "2018-04-05",
    "remarks": "notice remarks",
    "id": 1,
    "notice": 1
    }

28. Notice Remarks Update
    * Update and delete API for Group Notice Remarks 
    * URL: /operation/noticeremarks-list-update/1
    * Input:{
    "name": "notice remarks name updated",
    "code": "notice remarks code",
    "entered_date": "2018-04-05",
    "remarks": "notice remarks",
    "id": 1,
    "notice": 1,
    "user_id":1
    }
    * Output:
     
    {
    "name": "notice remarks name updated",
    "code": "notice remarks code",
    "entered_date": "2018-04-05",
    "remarks": "notice remarks",
    "id": 1,
    "notice": 1
    }

29. Notice Thingstodo
    * List API for Group Notice Things todo
    * URL: /operation/noticethingstodo-list/
    * Input:NA
    * Output:
    
    {
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "name": "notice thingstodo name",
            "code": "notice thingstodo code",
            "entered_date": "2018-04-27",
            "description": "notice things todo descrtn",
            "id": 1,
            "notice": 1,
            "todo_date": "2018-03-02"
        }
    ]
    }
    Create API for Group Notice things todo
    * URL: /operation/noticethingstodo-list/
    * Input: 
          {
    "name": "notice thingstodo name",
    "code": "notice thingstodo code",
    "description": "notice things todo descrtn",
    "notice": 1,
    "todo_date": "2018-03-02",
    "user_id":1
    }
    * Output:
              
    {
    "name": "notice thingstodo name",
    "code": "notice thingstodo code",
    "entered_date": "2018-04-27",
    "description": "notice things todo descrtn",
    "id": 1,
    "notice": 1,
    "todo_date": "2018-03-02"
    }

30. Notice Thingstodo Update
    * Update and delete API for Group Notice Thingstodo
    * URL: /operation/noticethingstodo-list-update/1
    * Input:{
    "name": "notice thingstodo name updated",
    "code": "notice thingstodo code",
    "entered_date": "2018-04-27",
    "description": "notice things todo descrtn  updated",
    "id": 1,
    "notice": 1,
    "todo_date": "2018-03-02",
    "user_id":1
    }
    * Output:
    {
    "name": "notice thingstodo name updated",
    "code": "notice thingstodo code",
    "entered_date": "2018-04-27",
    "description": "notice things todo descrtn  updated",
    "id": 1,
    "notice": 1,
    "todo_date": "2018-03-02"
    }

31. Notice Reminder
    * List API for Group Notice Reminder
    * URL: /operation/noticereminder-list/
    * Input:NA
    * Output:
    {
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "name": "notice reminder name",
            "code": "notice reminder code",
            "entered_date": "2018-04-27",
            "description": "notice reminder descrptn",
            "id": 1,
            "notice": 1,
            "reminder_date": "2018-03-08"
        }
    ]
    }
    Create API for Group Notice Reminder
    * URL: /operation/noticereminder-list/
    * Input: 
          {
    "name": "notice reminder name",
    "code": "notice reminder code",
    "description": "notice reminder descrptn",
    "notice": 1,
    "reminder_date": "2018-03-08",
    "user_id":1
    }
    * Output:
              
    {
    "name": "notice reminder name",
    "code": "notice reminder code",
    "entered_date": "2018-04-27",
    "description": "notice reminder descrptn",
    "id": 1,
    "notice": 1,
    "reminder_date": "2018-03-08"
    }

32. Notice Reminder Update
    * Update and delete API for Group Notice Reminder
    * URL: /operation/noticereminder-list-update/1
    * Input:{
    "name": "notice reminder name updated",
    "code": "notice reminder code",
    "entered_date": "2018-04-27",
    "description": "notice reminder descrptn updated",
    "id": 1,
    "notice": 1,
    "reminder_date": "2018-03-08",
    "user_id":1
    }
    * Output:
    {
    "name": "notice reminder name updated",
    "code": "notice reminder code",
    "entered_date": "2018-04-27",
    "description": "notice reminder descrptn updated",
    "id": 1,
    "notice": 1,
    "reminder_date": "2018-03-08"
    }

33. Documentation Remarks
    * List API for Group Documentation Remarks
    * URL: /operation/documentationremarks-list/
    * Input:NA
    * Output:
    {
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "name": "documentation remarks name 1",
            "code": "documentation remarks code",
            "entered_date": "2018-04-27",
            "id": 1,
            "documentation": 1,
            "remarks": "documentation remarks"
        }
    ]
    }
    Create API for Group Documentation Remarks
    * URL: /operation/documentationremarks-list/
    * Input: 
          {
    "name": "documentation remarks name 1",
    "code": "documentation remarks code",
    "documentation": 1,
    "remarks": "documentation remarks",
    "user_id":1
    }
    * Output:
              
    {
    "name": "documentation remarks name 1",
    "code": "documentation remarks code",
    "entered_date": "2018-04-27",
    "id": 1,
    "documentation": 1,
    "remarks": "documentation remarks"
    }

34. Documentation Remarks Update
    * Update and delete API for Group Documentation Remarks
    * URL: /operation/documentationremarks-list-update/1
    * Input:{
    "name": "documentation remarks name 1 updated",
    "code": "documentation remarks code",
    "entered_date": "2018-04-27",
    "id": 1,
    "documentation": 1,
    "remarks": "documentation remarks updated",
    "user_id":1
    }
    * Output:
    {
    "name": "documentation remarks name 1 updated",
    "code": "documentation remarks code",
    "entered_date": "2018-04-27",
    "id": 1,
    "documentation": 1,
    "remarks": "documentation remarks updated"
    }

35. Documentation ThingsTODO
    * List API for Group Documentation Thingstodo
    * URL: /operation/documentationthingstodo-list/
    * Input:NA
    * Output:
    {
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "name": "documentation things todo name",
            "code": "documentation things todo code",
            "entered_date": "2018-04-27",
            "todo_date": "2018-02-09",
            "documentation": 1,
            "description": "descrptn 1",
            "id": 1
        }
    ]
    }
    Create API for Group Documentation Thingstodo
    * URL: /operation/documentationthingstodo-list/
    * Input: 
          {
    "name": "documentation things todo name",
    "code": "documentation things todo code",
    "todo_date": "2018-02-09",
    "documentation": 1,
    "description": "descrptn 1",
    "user_id":1
    }
    * Output:
    {
    "name": "documentation things todo name",
    "code": "documentation things todo code",
    "entered_date": "2018-04-27",
    "todo_date": "2018-02-09",
    "documentation": 1,
    "description": "descrptn 1",
    "id": 1
    }

36. Documentation Thingstodo Update
    * Update and delete API for Group Documentation Thingstodo
    * URL: /operation/documentationthingstodo-list-update/1
    * Input:{
    "name": "documentation things todo name updated",
    "code": "documentation things todo code",
    "entered_date": "2018-04-27",
    "todo_date": "2018-02-09",
    "documentation": 1,
    "description": "descrptn 1 updated",
    "id": 1,
    "user_id":1
    }
    * Output:
    {
    "name": "documentation things todo name updated",
    "code": "documentation things todo code",
    "entered_date": "2018-04-27",
    "todo_date": "2018-02-09",
    "documentation": 1,
    "description": "descrptn 1 updated",
    "id": 1
    }

37. Documentation Reminder
    * List API for Group Documentation Reminder
    * URL: /operation/documentationreminder-list/
    * Input:NA
    * Output:
    {
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "name": "documentation reminder name",
            "code": "documentation reminder code",
            "entered_date": "2018-04-27",
            "reminder_date": "2018-03-02",
            "documentation": 1,
            "description": "descrptn",
            "id": 1
        }
    ]
    }
    Create API for Group Documentation Reminder
    * URL: /operation/documentationreminder-list/
    * Input: 
         {
    "name": "documentation reminder name",
    "code": "documentation reminder code",
    "reminder_date": "2018-03-02",
    "documentation": 1,
    "description": "descrptn",
    "user_id":1
    }
    * Output:
    {
    "name": "documentation reminder name",
    "code": "documentation reminder code",
    "entered_date": "2018-04-27",
    "reminder_date": "2018-03-02",
    "documentation": 1,
    "description": "descrptn",
    "id": 1
    }

38. Documentation Reminder Update
    * Update and delete API for Group Documentation Reminder
    * URL: /operation/documentationreminder-list-update/1
    * Input:{
    "name": "documentation reminder name update",
    "code": "documentation reminder code",
    "entered_date": "2018-04-27",
    "reminder_date": "2018-03-02",
    "documentation": 1,
    "description": "descrptn updated",
    "id": 1,
    "user_id":1
    }
    * Output:
    {
    "name": "documentation reminder name update",
    "code": "documentation reminder code",
    "entered_date": "2018-04-27",
    "reminder_date": "2018-03-02",
    "documentation": 1,
    "description": "descrptn updated",
    "id": 1
    }

39. Others Remarks
    * List API for Group Others Remarks
    * URL: /operation/othersremarks-list/
    * Input:NA
    * Output:
    {
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "name": "others name 1",
            "code": "others code q2",
            "entered_date": "2018-04-27",
            "remarks": "others remarks",
            "id": 1,
            "others": 1
        }
    ]
    }
    Create API for Group Others Remarks
    * URL: /operation/Othersremarks-list/
    * Input: 
    {
    "name": "others name 1",
    "code": "others code q2",
    "remarks": " others remarks",
    "others": 1,
    "user_id":1
    }
    * Output:
    {
    "name": "others name 1",
    "code": "others code q2",
    "entered_date": "2018-04-27",
    "remarks": "others remarks",
    "id": 1,
    "others": 1
    }

40. Others Remarks Update
    * Update and delete API for Group Others Remarks
    * URL: /operation/Othersremarks-list-update/1
    * Input:{
    "name": "others name 1 updated",
    "code": "others code q2",
    "entered_date": "2018-04-27",
    "remarks": "others remarks updated",
    "id": 1,
    "others": 1,
    "user_id":1
    }
    * Output:
    {
    "name": "others name 1 updated",
    "code": "others code q2",
    "entered_date": "2018-04-27",
    "remarks": "others remarks updated",
    "id": 1,
    "others": 1
    }

41. Others Thingstodo
    * List API for Group Others Thingstodo
    * URL: /operation/othersthingstodo-list/
    * Input:NA
    * Output:
    {
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "name": "others thingstodo name",
            "code": "others things to do code",
            "entered_date": "2018-04-27",
            "todo_date": "2018-03-02",
            "others": 1,
            "description": "descrptn",
            "id": 1
        }
    ]
    }
    Create API for Group Others Thingstodo
    * URL: /operation/Othersthingstodo-list/
    * Input: 
    {
    "name": "others thingstodo name",
    "code": "others things to do code",
    "todo_date": "2018-03-02",
    "others": 1,
    "description": "descrptn",
    "user_id":1
    }
    * Output:
    {
    "name": "others thingstodo name",
    "code": "others things to do code",
    "entered_date": "2018-04-27",
    "todo_date": "2018-03-02",
    "others": 1,
    "description": "descrptn",
    "id": 1
    }

42. Others Things todo Update
    * Update and delete API for Group Others thingstodo
    * URL: /operation/Othersthingstodo-list-update/1
    * Input:{
    "name": "others thingstodo name updated",
    "code": "others things to do code",
    "entered_date": "2018-04-27",
    "todo_date": "2018-03-02",
    "others": 1,
    "description": "descrptn updated",
    "id": 1,
    "user_id":1
    }
    * Output:
    {
    "name": "others thingstodo name updated",
    "code": "others things to do code",
    "entered_date": "2018-04-27",
    "todo_date": "2018-03-02",
    "others": 1,
    "description": "descrptn updated",
    "id": 1
    }

43. Others Reminder
    * List API for Group Others Reminder
    * URL: /operation/othersreminder-list/
    * Input:NA
    * Output:
    {
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "name": "others reminder",
            "code": "others reminder code",
            "entered_date": "2018-04-27",
            "reminder_date": "2018-03-02",
            "others": 1,
            "description": "descriptn",
            "id": 1
        }
    ]
    }
    Create API for Group Others Reminder
    * URL: /operation/Othersreminder-list/
    * Input: 
    {
    "name": "others reminder",
    "code": "others reminder code",
    "reminder_date": "2018-03-02",
    "others": 1,
    "description": "descriptn",
    "user_id":1
    }
    * Output:
    {
    "name": "others reminder",
    "code": "others reminder code",
    "entered_date": "2018-04-27",
    "reminder_date": "2018-03-02",
    "others": 1,
    "description": "descriptn",
    "id": 1
    }

42. Others Reminder Update
    * Update and delete API for Group Others Reminder
    * URL: /operation/Othersreminder-list-update/1
    * Input:{
    "name": "others thingstodo name updated",
    "code": "others things to do code",
    "entered_date": "2018-04-27",
    "todo_date": "2018-03-02",
    "others": 1,
    "description": "descrptn updated",
    "id": 1,
    "user_id":1
    }
    * Output:
    {
    "name": "others reminder updated",
    "code": "others reminder code",
    "entered_date": "2018-04-27",
    "reminder_date": "2018-03-02",
    "others": 1,
    "description": "descriptn updated",
    "id": 1,
    "user_id":1
    }%      
