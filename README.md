# MCDA
MCDA - Move Chromebooks Automatically

## Do note!
MCBA will soon be altered to use GAMADV-XTD3 to push data to the Sheets Devices and Users. So this GAS version will not be developed much longer. I will rename this repository to indicate when that happens. A new repo will carry on with this short name.

MCBA was developed to support automatic relocation of Chromebook devices. MCBA has an overview of every CBs serial number, most recent user, where it is located (Device_OU) and where the most recent user is located (MRU_OU). It uses GAMADV-XTD3 to push fresh data to the two sheets Devices & Users, and then uses a number of formulas to calculate their current relationship, and decide what to do with the devices.						

I definitely recommend you read the contents of the scripts before running any functions. If for nothing else at least so you know it looks like it'll only do what I say. Click _Tools /Script editor_ in the Sheets menu to open it to read.

_**Any existing scripts can't do anything at all until you authorise them.**_

### Link to copyable MCBA.

[MCBA template](https://docs.google.com/spreadsheets/d/1Sa6p_tjSz1rYRJ8B7xSIBkBHen3uQYcCBA2b_4hIGDM/copy)

Click the link with your Chromebook admin (often superadmin) account.

All headers have small comments on what you can do and shouldn't.

If you don't want to create a Sheet copy, the scripts are also available here in this repo.

**DO NOTE!** If you copy the scripts from here, instead of copying the entire Sheets file, you will have to enable the API manually. Here's how you do that. Click the following menus.

Tools / Script Editor
Resources
Advanced Google Services

Then click the button for

Admin Directory API

Ok and save.

## PRIVACY POLICY

**You are in full control of all the data. The script is only accessing data you yourself have access to. No data is sent anywhere, except between you and Google. No matter if you create a copy of my Sheet or my scripts, I will never gain access to any of your data. All data reading and writing is done by you on your own account.**