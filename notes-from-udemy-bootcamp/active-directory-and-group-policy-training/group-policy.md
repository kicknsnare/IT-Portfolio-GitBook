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



## Group Policy for Software Installation

<figure><img src="../../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

### Creating a Share

Properties -> Sharing -> Advanced Sharing -> Permissions -> add -> Type Domain Users

<figure><img src="../../.gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>

It is important to remember or take into consideration the network path

<figure><img src="../../.gitbook/assets/image (32).png" alt=""><figcaption></figcaption></figure>
