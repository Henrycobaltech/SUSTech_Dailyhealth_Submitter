# SUSTech Daily Health Submitter

**Update on June, 2020: This program no longer works since June 2, 2020 because the ITS of SUSTech changed the vailidity of the access token to be shorter than 24hrs. Which requires us to get a new access token every day.**


A program to automatically submit your health status to SUSTech.

A documentation explaining the entries in `config.json` is needed.
Pull requests are welcomed.

## ⚠️ Warning 警告

This program is used by myself for convenience, the quality of the program is not guaranteed, and the author of the program is NOT responsible for any consequence caused.

本程序仅为个人出于方便目的编写，本人对程序的质量不作任何保证，也**不会**对使用此程序造成的任何后果承担任何责任。

Use at your own risk.

请三思而后用。


## Usage

### Constructing the `config.json`
- Complete your information in `config.json` manually, or
- Capture the request sent to SUSTech server using developer tools provided by browser, and fill the headers and form in `config.json` with captured data (recommended).

### Run the submitter
```bash
$ python3 src/submitter.py config.json
```


