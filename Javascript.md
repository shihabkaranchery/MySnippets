



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

* Preview of image while open the file, in angular js 1.x

```javascript
    $scope.item_img = null;
    $scope.restItemImage = function(element) {
            // actual file send to server
            $scope.item_img = element.files[0];

            // for preview image in <img ng-src="disp_img" />
            var reader = new FileReader();
            reader.onload = function(event) {
                    $scope.disp_img = event.target.result
                    $scope.$apply()
                }
            reader.readAsDataURL(element.files[0]);
        }

```

* Save Image from angular js to server send via http call in formdata

```javascript
    // save image send img to server using form data
    $scope.updateRestMenu = function() {
            var fd = new FormData();
            fd.append("image", $scope.item_img);
            $http({
                method: 'POST',
                url: 'url',
                data: fd,
                headers: {
                    'Content-Type': undefined
                }
            }).then(function SuccessCallBack(response) {
               // response
            }, function errorCallBack(response) {});
        }

```