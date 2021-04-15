# zabbix-customizable-html-email-template

### Customizable Zabbix HTML Email Template - Problem/Recovery

---

This repository holds a set of customizable HTML Template to be used with the Zabbix Email HTML MediaType.

## Requirements

---
Zabbix 4.4 and up

## Customization

Basically you can customize anything on these HTML templates, from the Logo, Trigger/Host Information, Colours, footer. The only limitation is your HTML or Design Skills :)

- [html-online](https://html-online.com/editor/)
- [devexpress](https://demos.devexpress.com/ASPxHtmlEditorDemos/Features/General.aspx)

Check "Templates" directory for the HTML Templates

### Sample - HTML Template
<img src="https://raw.githubusercontent.com/JulioZanette/zabbix-html-email-template/main/Images/Problem.png" width="350"> <img src="https://raw.githubusercontent.com/JulioZanette/zabbix-html-email-template/main/Images/Recovery.png" height="400">

### Result - Demo Trigger
<img src="https://raw.githubusercontent.com/JulioZanette/zabbix-html-email-template/main/Images/Demo-Problem.png" width="350"> <img src="https://raw.githubusercontent.com/JulioZanette/zabbix-html-email-template/main/Images/Demo%20-%20Recovery.png" width="350">

## Installation

---
Installation is simple. From Zabbix WebUI, go to `Administration > Media Types > Email (HTML)`

<img src="https://raw.githubusercontent.com/JulioZanette/zabbix-html-email-template/main/Images/MidiaType.jpeg" width="350">

Update the `Message Templates` "Problem" and "Problem Recovery"

<img src="https://raw.githubusercontent.com/JulioZanette/zabbix-html-email-template/main/Images/MidiaType_Problem.jpeg" width="500"> <img src="https://raw.githubusercontent.com/JulioZanette/zabbix-html-email-template/main/Images/MidiaType_Recovery.jpeg" width="500">



For more details on Zabbix Media Type configuration, please refer to: [MEDIA TYPES](https://www.zabbix.com/documentation/4.4/manual/config/notifications/media)

# ToDo

---
- Add link to Event Details
- Add a Graph to the problematic item

---
Inspired by: https://github.com/maand75/zabbix-htmlmailtemplates