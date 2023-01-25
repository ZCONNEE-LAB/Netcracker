<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>
<script src="./core-min.js"></script>
<script src="./md5-min.js"></script>
<script src="./wildfire-labs.js"></script>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KyZXEAg3QhqLMpG8r+8fhAXLRk2vvoC2f3B09zVXn8CA5QIVfZOJ3BCsw2P0p/We" crossorigin="anonymous">

## Welcome

Thank you for attending this Washington Systems Center(WSC) workshop. 

[//]: The WSC's z/OS Connect EE Getting Started Guide can be downloaded from [here](https://github.com/ibm-wsc/zCONNEE-Wildfire-Workshop/blob/master/zOS%20Connect%20EE%20V3%20Getting%20Started.pdf) to view it locally.
  

## Accessing the hands-on lab

Click [here](https://github.com/ZCONNEE-LAB/Netcracker/blob/ee22808a27077f1dc6273d60292479ebc3688915/Remote%20Lab%20System%20Connection%20Instructions%20-%20github.pdf) to read the directions for IBM System access.

All API Requester lab instructions are in the "Lab Docs" folder on your remote desktop, or can be downloaded from [here](https://github.com/ibm-wsc/zCONNEE-Wildfire-Workshop/tree/master/APIRequesters) to view it locally.

The server XML configuration files referenced in the exercises can be downloaded from [here](https://github.com/ibm-wsc/zCONNEE-Wildfire-Workshop/tree/master/XML%20Samples) to view it locally.


**Please enter your email address (ex: johndoe@yourcompany.com) to retrieve your unique log in details.**

<form onsubmit="return false;">
<div class="input-group mb-3 col-6">
<span class="input-group-text" id="basic-addon1">@</span>
<input type="email" class="form-control" placeholder="Email Address" aria-label="Email" aria-describedby="basic-addon1" id="registration-email" maxlength="50" required oninput="validate();">
</div>
<div class="col-6">
<button id="btn-submit" class="btn btn-primary" type="submit" onclick="getLab(document.getElementById('registration-email').value)" disabled>Submit</button>
</div>
</form>
<div id="lab" class=".container .text-monospace">
</div>

## Help 
Having trouble with labs? Send an email to [Mitch Johnson](mailto: mitchj@us.ibm.com) or [Kenishia Callaway](mailto: kenishia@us.ibm.com) and we will help you sort it out.
