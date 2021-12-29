## The licence object

> THE LICENCE OBJECT

```json
{
  "referenceNumber": "string",
  "address": {
    "addressLine1": "Flat 123",
    "addressLine2": "Imaginary Court",
    "addressLine3": "Example Estate",
    "addressLine4": "Abstract City",
    "city": "London",
    "country": "United Kingdom",
    "county": "Fantasy",
    "postcode": "A1 2BC",
    "uprn": "12345678910",
    "usrn": "1234567",
    "latitude": "1.230045",
    "longitude": "-5.430021",
    "ward": "Dream Ward"
  },
  "licencePhase": "string",
  "licenceType": {
    "id": 0,
    "name": "string"
  },
  "licenceStatus": {
    "id": 0,
    "name": "string"
  },
  "assignee": {
    "id": 0,
    "name": "string"
  },
  "dateSubmitted": "2021-12-29T14:44:53.657Z",
  "datePaid": "2021-12-29T14:44:53.657Z",
  "propertyRooms": {
    "bathrooms": [
      {
        "location": "string",
        "exclusivity": "Shared",
        "washHandBasins": 0,
        "toilets": 0,
        "bathsAndShowers": 0
      }
    ],
    "bedrooms": [
      {
        "location": "string",
        "size": 0,
        "exclusivity": "Shared",
        "bathroomFacilities": "Yes",
        "washBasins": 0,
        "toilets": 0,
        "bathShower": 0,
        "kitchenFacilities": "Yes",
        "ovens": 0,
        "hobs": 0,
        "sinks": 0,
        "fridges": 0,
        "freezers": 0
      }
    ],
    "communalRooms": [
      {
        "location": "string",
        "size": 0,
        "exclusivity": "Shared",
        "smokeAlarm": "Yes",
        "bestDescription": "Dining room",
        "washHandBasins": 0
      }
    ],
    "kitchens": [
      {
        "location": "string",
        "size": 0,
        "exclusivity": "Shared",
        "smokeAlarm": "Yes",
        "ovens": 0,
        "hobs": 0,
        "sinks": 0,
        "fridges": 0,
        "freezers": 0
      }
    ]
  },
  "propertyUnits": {
    "unitsNotUnderLicenceHolder": [
      {
        "name": "string",
        "floor": 0,
        "occupied": "Residential"
      }
    ],
    "flatsUnderLicenceHolder": [
      {
        "name": "string",
        "floor": 0,
        "entrance": "Shared",
        "roomsInFlat": 0,
        "tenancyType": "Assured shorthold tenancy (AST)",
        "tenancyTypeOther": "string",
        "occupiersCount": 0,
        "namesOfAllOccupiers": "string"
      }
    ],
    "bedsitsUnderLicenceHolder": [
      {
        "name": "string",
        "floor": 0,
        "entrance": "Shared",
        "size": 0,
        "tenancyType": "Assured shorthold tenancy (AST)",
        "tenancyTypeOther": "string",
        "occupiersCount": 0,
        "namesOfAllOccupiers": "string"
      }
    ]
  },
  "eligibilityInformation": {
    "unspentConvictions": "Yes",
    "unspentConvictionsDetails": "string",
    "unlawfulDiscrimination": "Yes",
    "unlawfulDiscriminationDetails": "string",
    "judgementMadeAgainstYou": "Yes",
    "judgementMadeAgainstYouDetails": "string",
    "experienceOfManagingRentedProperty": "Yes",
    "licenceHolderBelongToLandlords": "Yes",
    "nameOfAssociation": "string",
    "registrationNumber": "string",
    "propertyVisited": "Yes",
    "hasFunds": "Yes",
    "fundsInfo": "string",
    "hasPropertyInControlToManagementOrder": "Yes",
    "hasPropertyInControlToManagementOrderDetails": "string",
    "hasPropertyThatHasBeenRefused": "Yes",
    "hasPropertyThatHasBeenRefusedDetails": "string",
    "regularInspection": "Yes",
    "regularInspectionMonthly": 0,
    "regularInspectionPerson": "string",
    "regularCleaning": "Yes",
    "regularCleaningMonthly": 0,
    "regularCleaningPerson": "string",
    "problems": "Yes",
    "problemsDetails": "string"
  },
  "healthAndSafety": {
    "smokeAlarmsAmount": 0,
    "hasKitchenFireDoors": "Yes",
    "hasFireBlankets": "Yes",
    "hasFireExtinguishers": "Yes",
    "fireExtinguishersInfo": "string",
    "hasFireDetectionSystem": "Yes",
    "hasSafetyInformation": "Yes",
    "hasRegulationsCompliance": "Yes",
    "hasGasSupply": "Yes",
    "gasSafety": "string",
    "fireDoors": "Yes - all",
    "fireDoorsDetails": "Yes",
    "basementOrCellar": "Yes",
    "basementOrCellarDetails": "Yes",
    "fireDetection": "Yes",
    "fireDetectionDetails": "string",
    "emergencyLighting": "Yes",
    "extinguisher": "Yes",
    "fireSafety": "Yes",
    "electricalInstallation": "Yes",
    "gasInstallation": "Yes",
    "electricalSupply": "Yes",
    "exitDoors": "Yes"
  },
  "propertyDetails": {
    "propertyUsage": "House in multiple occupation",
    "propertyStoriesAmount": 0,
    "floorsSituation": "string",
    "buildingStoriesAmount": 0,
    "propertyHouseholdAmount": 0,
    "propertyPeopleAmount": 0,
    "propertyPeopleAmountToLet": 0,
    "propertyHouseholdAmountToLet": 0,
    "occupiedDate": "2021-12-29T14:44:53.658Z",
    "separateLettingsAmount": 0,
    "habitableRoomsAmount": 0,
    "propertyApproxYear": "string",
    "externalStructures": "Yes",
    "maxOccupants": 0,
    "maxHouseholds": 0,
    "hasBuildingBeenConvertedIntoFlats": "Whole building",
    "dateOfConversion": "string",
    "howIsTheBuildingOccupied": "Residential",
    "howIsTheBuildingOccupiedInfo": "string",
    "residentialFlatsNumber": 0,
    "unitsUnderLicenceHolder": 0,
    "residingLicenceHolderInUnit": "Yes",
    "residingLicenceHolderInUnitInfo": "string"
  },
  "interestedParties": {
    "licenceHolder": "string",
    "personWhoCollectRent": "string",
    "applicant": "string",
    "parties": [
      {
        "title": "string",
        "firstName": "string",
        "surname": "string",
        "dateOfBirth": "2021-12-29T14:44:53.658Z",
        "companyName": "string",
        "address": {
          "addressLine1": "Flat 123",
          "addressLine2": "Imaginary Court",
          "addressLine3": "Example Estate",
          "addressLine4": "Abstract City",
          "city": "London",
          "country": "United Kingdom",
          "county": "Fantasy",
          "postcode": "A1 2BC",
          "uprn": "12345678910",
          "usrn": "1234567",
          "latitude": "1.230045",
          "longitude": "-5.430021",
          "ward": "Dream Ward"
        },
        "phoneNumber": "string",
        "emailAddress": "string",
        "partyType": "string",
        "partyTypeName": "string",
        "organisation": true,
        "dateContacted": "2021-12-29T14:44:53.659Z"
      }
    ]
  },
  "dateDraftIssued": "2021-12-29T14:44:53.659Z",
  "dateFinalIssued": "2021-12-29T14:44:53.659Z",
  "dateValidFrom": "2021-12-29T14:44:53.659Z",
  "dateValidTo": "2021-12-29T14:44:53.659Z",
  "totalMaxPersons": 0,
  "totalMaxHouseholds": 0
}
```







### Attributes

<p style="max-width:440px; margin-bottom:0; margin-left:28px; padding-top:15px; padding-left:0px; border-top-style:solid; border-top-color:#eee; border-top-width:1px">
<span style="font-size:13px; font-weight:700; color:#2a2f45; font-family:Menlo, Consolas, monospace">id</span> <span style="font-size:12px; font-weight:600; color:#8792a2">string</span>
</p>

Unique identifier for the object.

<p style="max-width:440px; margin-bottom:0; margin-left:28px; border-bottom-style:solid; border-bottom-color:#eee; border-bottom-width:1px"></p>



<p style="max-width:440px; margin-bottom:0; margin-top:15px">
<span style="font-size:13px; font-weight:700; color:#2a2f45; font-family:Menlo, Consolas, monospace">referenceNumbers</span> <span style="font-size:12px; font-weight:600; color:#8792a2">array</span>
</p>

List of reference numbers of any licences, applications and temporary exemptions associated with the property.

<p style="max-width:440px; margin-bottom:0; margin-left:28px; border-bottom-style:solid; border-bottom-color:#eee; border-bottom-width:1px"></p>


<p style="max-width:440px; margin-bottom:0; margin-top:15px">
<span style="font-size:13px; font-weight:700; color:#2a2f45; font-family:Menlo, Consolas, monospace">address</span> <span style="font-size:12px; font-weight:600; color:#8792a2">array</span>
</p>

All address data.


<p style="max-width:440px; margin-bottom:0; margin-top:15px; padding-left:56px">
<span style="font-size:13px; font-weight:700; color:#2a2f45; font-family:Menlo, Consolas, monospace"><span style="color:#a3acb9">address.</span>addressLine1</span> <span style="font-size:12px; font-weight:600; color:#8792a2">string</span>
</p>

<span style="padding-left:28px">First line of the property's address.</span>


<p style="max-width:440px; margin-bottom:0; margin-top:15px; padding-left:56px">
<span style="font-size:13px; font-weight:700; color:#2a2f45; font-family:Menlo, Consolas, monospace"><span style="color:#a3acb9">address.</span>addressLine2</span> <span style="font-size:12px; font-weight:600; color:#8792a2">string</span>
</p>

<span style="padding-left:28px">Second line of the property's address.</span>


<p style="max-width:440px; margin-bottom:0; margin-top:15px; padding-left:56px">
<span style="font-size:13px; font-weight:700; color:#2a2f45; font-family:Menlo, Consolas, monospace"><span style="color:#a3acb9">address.</span>addressLine3</span> <span style="font-size:12px; font-weight:600; color:#8792a2">string</span>
</p>

<span style="padding-left:28px">Third line of the property's address.</span>


<p style="max-width:440px; margin-bottom:0; margin-top:15px; padding-left:56px">
<span style="font-size:13px; font-weight:700; color:#2a2f45; font-family:Menlo, Consolas, monospace"><span style="color:#a3acb9">address.</span>addressLine4</span> <span style="font-size:12px; font-weight:600; color:#8792a2">string</span>
</p>

<span style="padding-left:28px">Fourth line of the property's address.</span>


<p style="max-width:440px; margin-bottom:0; margin-top:15px; padding-left:56px">
<span style="font-size:13px; font-weight:700; color:#2a2f45; font-family:Menlo, Consolas, monospace"><span style="color:#a3acb9">address.</span>city</span> <span style="font-size:12px; font-weight:600; color:#8792a2">string</span>
</p>

<span style="padding-left:28px">City of the address.</span>


<p style="max-width:440px; margin-bottom:0; margin-top:15px; padding-left:56px">
<span style="font-size:13px; font-weight:700; color:#2a2f45; font-family:Menlo, Consolas, monospace"><span style="color:#a3acb9">address.</span>country</span> <span style="font-size:12px; font-weight:600; color:#8792a2">string</span>
</p>

<span style="padding-left:28px">Country of the address.</span>


<p style="max-width:440px; margin-bottom:0; margin-top:15px; padding-left:56px">
<span style="font-size:13px; font-weight:700; color:#2a2f45; font-family:Menlo, Consolas, monospace"><span style="color:#a3acb9">address.</span>county</span> <span style="font-size:12px; font-weight:600; color:#8792a2">string</span>
</p>

<span style="padding-left:28px">County of the address.</span>


<p style="max-width:440px; margin-bottom:0; margin-top:15px; padding-left:56px">
<span style="font-size:13px; font-weight:700; color:#2a2f45; font-family:Menlo, Consolas, monospace"><span style="color:#a3acb9">address.</span>postcode</span> <span style="font-size:12px; font-weight:600; color:#8792a2">string</span>
</p>

<span style="padding-left:28px">Postcode of the address.</span>


<p style="max-width:440px; margin-bottom:0; margin-top:15px; padding-left:56px">
<span style="font-size:13px; font-weight:700; color:#2a2f45; font-family:Menlo, Consolas, monospace"><span style="color:#a3acb9">address.</span>uprn</span> <span style="font-size:12px; font-weight:600; color:#8792a2">string</span>
</p>

<span style="padding-left:28px">Unique Property Reference Number (UPRN) of the address.</span>


<p style="max-width:440px; margin-bottom:0; margin-top:15px; padding-left:56px">
<span style="font-size:13px; font-weight:700; color:#2a2f45; font-family:Menlo, Consolas, monospace"><span style="color:#a3acb9">address.</span>usrn</span> <span style="font-size:12px; font-weight:600; color:#8792a2">string</span>
</p>

<span style="padding-left:28px">Unique Street Reference Number (USRN) of the address.</span>


<p style="max-width:440px; margin-bottom:0; margin-top:15px; padding-left:56px">
<span style="font-size:13px; font-weight:700; color:#2a2f45; font-family:Menlo, Consolas, monospace"><span style="color:#a3acb9">address.</span>latitude</span> <span style="font-size:12px; font-weight:600; color:#8792a2">string</span>
</p>

<span style="padding-left:28px">Latitude of the address in decimal degrees (<a href="https://wikipedia.org/wiki/ISO_6709" target="_blank">ISO 6709</a>).</span>


<p style="max-width:440px; margin-bottom:0; margin-top:15px; padding-left:56px">
<span style="font-size:13px; font-weight:700; color:#2a2f45; font-family:Menlo, Consolas, monospace"><span style="color:#a3acb9">address.</span>longitude</span> <span style="font-size:12px; font-weight:600; color:#8792a2">string</span>
</p>

<span style="padding-left:28px">Longitude of the address in decimal degrees (<a href="https://wikipedia.org/wiki/ISO_6709" target="_blank">ISO 6709</a>).</span>


<p style="max-width:440px; margin-bottom:0; margin-top:15px; padding-left:56px">
<span style="font-size:13px; font-weight:700; color:#2a2f45; font-family:Menlo, Consolas, monospace"><span style="color:#a3acb9">address.</span>ward</span> <span style="font-size:12px; font-weight:600; color:#8792a2">string</span>
</p>

<span style="padding-left:28px">Ward of the address.</span>
