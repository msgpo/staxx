# Polarity STAXX Integration

Polarity's STAXX integration gives users access to automated MD5, SHA1, SHA256, IPv4, IPv6 and Domain lookups within Anomali's STAXX platform..

Anomali STAXX gives you a free, easy way to subscribe to any STIX / TAXII feed. Simply download the STAXX client, configure your data sources, and STAXX will handle the rest.

To learn more about Anomali STAXX please see their official website at [https://www.anomali.com/platform/staxx](https://www.anomali.com/platform/staxx)


| ![image](https://user-images.githubusercontent.com/306319/28879739-eda4e1ba-7770-11e7-9891-c520231a8a24.png)  |
|---|
|*Anomali STAXX Examples* |

## STAXX Integration Options

### Anomali STAXX Server URL

The URL for your STAXX server which should include the schema (i.e., http, https) and port if required.  For example `https://192.168.1.29:8080`

### Username

Your Anomali STAXX username

### Password

The password for the provided STAXX user

### Minimum Severity Level

A string value which specifies the minimum severity level required for an indicator to be displayed.   For example, if you set the value to high then only indicators with a severity level of "high" or "very-high" will be displayed in the notification overlay.

Allowed values are "low", "medium", "high", "very-high"

### Minimum Confidence Level

An integer value between 0 and 100 which specifies the minimum confidence level required for an indicator to be displayed.   For example, if you set the value to 55 then only indicators with a confidence of 55 or above will be displayed in the notification overlay.

### Ignore Private IPs

If set to true, private IPs (RFC 1918 addresses) will not be looked up (includes 127.0.0.1, 0.0.0.0, and 255.255.255.255)

## Polarity

Polarity is a memory-augmentation platform that improves and accelerates analyst decision making.  For more information about the Polarity platform please see: 

https://polarity.io/
