



* to find selected text in the text box

```javascript

var lang = $('#id_login_language').find(":selected").text();// find the selected text from <select> box

```

* write autocomplete of psuedo element, created dynamically

```javascript
//autocomplete dynamically loaded field
    $(document).on("focus", '.co-admin-name', function (e) {
        $(this).autocomplete({
            source: "url",
            selectFirst: true, // first option whouldbe selected
            select: function (event, ui) {
                $("#verid").val(ui.item.id);
            }
        });
    });
```

* Angular http call POST 

```javascript
    $http({
            method: 'POST',
            url: 'url',
            data: {
                "key": value
            },
            headers: {
                'Content-Type': undefined
            },
            }).then(function SuccessCallBack(response){
               // data contains in response.data
            }, function errorCallBack(response){
       });

       // Another way 

        $http.get('url')
            .then(function(response) {
               console.log(response.data)
        });
```

* In angular JS add CSRFMiddleware token put in to cookies, to avoid add csrf in each htttp call

```javascript
    var app = angular.module("app_name", []);
    app.config(['$httpProvider', function($httpProvider) {
        $httpProvider.defaults.xsrfCookieName = 'csrftoken';
        $httpProvider.defaults.xsrfHeaderName = 'X-CSRFToken';
    }]);


```
