# Group Policy



## Installation

\-> Apps And Features -> Group Policy Management Tools

## Password Policy Quick Way

```powershell
net accounts
```

## Enabling Group Policy Lockouts

Default Domain Policy -> Edit -> Computer Configuration -> Windows Settings -> Security Settings -> Account Policies

Account lockout threshold

<figure><img src="../../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>

```powershell
gpupdate
gpupdate /force
gpresults /h c:\gpresults.htlm
```



## Software Deployment

## Group Policy for Software Installation

<figure><img src="../../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

### Creating a Share

Properties -> Sharing -> Advanced Sharing -> Permissions -> add -> Type Domain Users

<figure><img src="../../.gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>

It is important to remember or take into consideration the network path

<figure><img src="../../.gitbook/assets/image (32).png" alt=""><figcaption></figcaption></figure>



## Deployment with MSI

<figure><img src="../../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (3) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (4) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (5) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>



### Add Security Filtering to a Computer

<figure><img src="../../.gitbook/assets/image (6) (1) (1).png" alt=""><figcaption></figcaption></figure>

```powershell
#go back to the computer and enter this on cmd
gpupdate /all
#type Y for yes and when you restart the computer the software should be ther

```

