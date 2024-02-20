# Windows OS Issues

## Frequent Shutdowns

Causes

* Overheating issues
* Updates

How to fix it?

Driver roll back

* Driver Management (Windows Icon-> Device Manager or Computer Manager-> Device Manager)
* Identify what is causing the shutdowns

Check the device status for errors and look for documentation

<figure><img src="../../.gitbook/assets/image (33).png" alt=""><figcaption></figcaption></figure>

Roll back the driver

<figure><img src="../../.gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>



## Blue Scree of Death (BSOD)

<figure><img src="../../.gitbook/assets/image (35).png" alt=""><figcaption></figcaption></figure>

* Use event viewer to understand what happened and what caused the problem



## Sluggish Performance

* Task Manager can come handy



## Boot Problems&#x20;

```powershell
#Priviledged terminal
sfc /scannow
#System Configuration (search bar)
msconfig.exe
```

<figure><img src="../../.gitbook/assets/image (36).png" alt=""><figcaption></figcaption></figure>

If you don't get any problem with the dignostic startup it means that you have a third party driver that is causing the problem

You can also check the startups for programs that might slow down the process and therefore cause the problem\
Task Manager

<figure><img src="../../.gitbook/assets/image (37).png" alt=""><figcaption></figcaption></figure>



## Service not Starting

Some problematic services&#x20;

* Application Identity (Because of Applocker)
* Principle of Services

Computer Mangagement

<figure><img src="../../.gitbook/assets/image (39).png" alt=""><figcaption></figcaption></figure>

Some services are set to manual start up and the problem is the some of them need to start automatically

<figure><img src="../../.gitbook/assets/image (41).png" alt=""><figcaption></figcaption></figure>

Restart the process

<figure><img src="../../.gitbook/assets/image (42).png" alt=""><figcaption></figcaption></figure>



## Application Crashes

End Task with Task Manager

Re install the application or Repair

Apps and Features -> Right Top Programs and Features-> Change (the program) -> Repair

<figure><img src="../../.gitbook/assets/image (43).png" alt=""><figcaption></figcaption></figure>



## System Instability&#x20;

* Repair installation -> Troubleshooting -> Startup Repair/System Restore/Unistall Updates

## No OS found

Check the physical structure or startup repair&#x20;





## SUPER IMPORTANT

When you get a new windows it is recommended to hook an external drive and create a repair disk
