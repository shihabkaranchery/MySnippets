
* to find select box value and text

```HTML

<select name="assign-ssid" class="form-control"
	(change)="getSSID($event)"
	>
	<option value="">Please Select SSID</option>
	<option *ngFor="let ssid of ssidArray"
	 value="{{ssid.vapid}}">{{ssid.ssid}}</option>
</select>

```

* write autocomplete of psuedo element, created dynamically

```javascript
  getSSID(e){
    this.new_ssid = e.target.value;
    let selectElementText = e.target['options']
      [e.target['options'].selectedIndex].text;
      console.log(selectElementText);
  }
```

## Programmatically navigate

```javascript
export class HomeComponent implements OnInit {

  constructor(private router: Router, private authService: AuthService) { }

  ngOnInit() {
  }

  onLoadServer(id: number) {
    // complex calculation
    this.router.navigate(['/servers'])
  }

  onLogin() {
    this.authService.login();
  }

  onLogout() {
    this.authService.logout();
  }
}

```



* @input() decorator used to make property of child component visbile for parent component

* @input('custome_name') // these name available in outside of the component, can use parent of this component

* local reference <input type="text" #inputTextreference /> we can use this reference in templates and pass to .ts code can use value like (reciveing_var.value)
* we can use @viewChild('inputTextreference') inputType: ElementRef;
  and use like this.inputType.nativeElement.value;

  ## Life cycle Hooks

  * ngOnChange. executed multiple times, 
  * ngOnInit, executed once component initialized, run after the constructer
  * ngDoCheck, execute lots, execute whenever change detected
  * ngAfterContentInit, called after content(ng-content) has been projected in to view
  * ngAfterContentChecked, 
  * ngAfterViewInit
  * ngAfterViewChecked
  * ngDestroy
  





