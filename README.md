# acbuzz
Aadhar status API

Aadhar Tracking API is a service which is able to get the status of aadhar from official website. The API provides the current status along with the intermediate hub locations.

What is Aadhar API ?

You can track aadhar status from the official website with aadhar API. Alternatively, you can check status from <a href="https://acbuzz.com">www.acbuzz.com</a>

How to Use the Aadhar API

This is a simple API and easy to use. Here is the sample code is shown below

<?php
require_once "api.php"
$status = getTracking( UID number, Type);
?>
You have to include the api.php in your file and then call the getTracking function. This function accepts two parameters. The first one is the blue dart tracking number and the second one is the type ( WAYBILL / REFERENCE) of the number.

Future Requests

In future, we are planning to develop APIs for other blue dart functionalities lie branch location and customer care numbers by city. If you need any APIs, then you can request us.

Terms of Usage

To use this tracking API, you have to get permission from the official blue dart courier service. You cannot use this for any commercial or free purpose. You have to get authorization keys from the Blue dart in order to use this API.
