# soapui-oorsprongcountryinfo_api

Soap API testing in [Oorsprong Country Info](http://webservices.oorsprong.org/websamples.countryinfo/CountryInfoService.wso). This project contains basic examples on how to use SoapUI to test Soap API tests. Good practices such as hooks, custom commands and tags, among others, are used. All the necessary support documentation to develop this project is placed here.

# Pre-requirements:

| Requirement                   | Version | Note                                                            |
| :---------------------------- |:--------| :---------------------------------------------------------------|
| SoapUI                        | 5.8.0   | -                                                               |    

# Installation:

- See [SoapUI](https://www.soapui.org/downloads/soapui/), hit :point_right:**Download SoapUI Open Source** and install SoapUI by keeping all the preferenced options as they are.

# Tests:

- On cmd.exe, execute the command ```"C:\Program Files\SmartBear\SoapUI-5.8.0\bin\testrunner.bat" -a -r -j -f "C:\soapui-oorsprongcountryinfo_api\reports" "C:\soapui-oorsprongcountryinfo_api\soapui-oorsprongcountryinfo_api.xml"``` to run the tests and generate the report on reports folder. 
 - On SoapUI, Right click on :point_right:**soapui-oorsprongcountryinfo_api**, :point_right:**Lauch TestRunner** and :point_right:**Lauch**.

# Support:

- [SoapUI](https://www.soapui.org/)
- [DataFlex Web Service for Country information](http://webservices.oorsprong.org/websamples.countryinfo/CountryInfoService.wso)
- [ChatGPT](https://chatgpt.com/)

# Tips:

- SoapUI can be trick at the first usage, but it is really helpfull to organize test suites and create test cases. 
- Trust ChatGPT