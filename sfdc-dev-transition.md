## Platform I/II Transition Exam notes

What method for setting certificate in dual SSL callouts?
```
HttpRequest x;
x.setClientCertificateName('name');
```

Use of `System.Location` class to get distance between two coordinates
 ```
 Location x, y;
 Location.getDistance(x,y,'mi');
 ```
 
Checkpoints in the developer console
* do they stop execution or not? 
* what's the transaction behaviour?

How to embed Apex code in Flows?
* 2 options: annotation with `@invocableMethod` annotation or implementing the `Process.Plugin` interface
* differences supports bulks (i.e. are single objects supported? are bulk supproted? is it more or less verbose? is that available in the REST API? is that available in cloud designer?)
* use of tag attribute to categorise plugins in flow section
 
Apex managed sharing and recalculation with Batch classes

`RestContext` class, methods and attributes (how to access `RestRequest`, `RestResponse`)


How to update currency exchange rates through APIs
* `CurrencyType` and `DatedConversionRate` objects
* Can use the SOAP, REST API or DataLoader

How to use resources in Lightning Components

How to have WebServices and Rest methods to cohexist in the same class and limitations
* they can coexist, only post for parameters
* get parameters won't pass throughn in case of Soap calls

How to assign permission sets in Apex/SOQL, know the specific fields
* `PermissionSetAssignment` object, `AssigneeId` field
* Verify license on `PermissionSet` object, `UserLicenseId` field
