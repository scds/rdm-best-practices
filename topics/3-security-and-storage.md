---
layout: default
title: 3 - Data Security and Storage
nav_order: 6
---

<img src="../assets/img/lessons/backup-header.png" width="100%">

{: .no_toc}  
# Data Security and Storage
Data security is important not only to prevent unwanted access to your data but also to prevent data loss.

<details markdown="block" class="toc">
  <summary>
    Table of Contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

<!-- ## Lesson Video
The following video demonstrates each of the steps outlined below in text.

<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/a65689c0-c35c-4f33-9c12-f0ac97883f54/public?autoplay=false&automute=false"></iframe>
[View original here.](https://echo360.ca/media/a65689c0-c35c-4f33-9c12-f0ac97883f54/public?autoplay=false&automute=false) -->

## Even cautious people can lose data. 
<img src="../assets/img/lessons/research-security.png" alt="research is locked in a cage" width="40%" align=right style="display: block; margin: 10px; border-radius: 30px">
<i>Dr. X leads a large, well-funded lab that conducts multiple expansive research projects. Because the lab is so busy, Dr. X and their team also receive many emails every day.
Although they have taken some IT training, one of them clicks a link in a carefully-worded email and their research system becomes infected. All of Dr. X’s critical research files are encrypted; locked down until the university pays a ransom. Depending on how well Dr. X’s research is backed up, they could be facing an impossible decision: lose years of research...or pay up.</i>

Backup strategies, encrypting sensitive data, and data security measures help you store your data safely. This can help **avoid data loss** through theft or loss of your devices, accidental damage or destruction. It can also help you maintain **IT security** by avoiding computer viruses, malware, ransomware, and more. 

## Backup Strategies (3-2-1)

A good data storage plan should balance making your data easily accessible while being reliable and secure.

The good rule of thumb is:
- **3** copies of your data (at least!)
- **2** copies are on-hand (easily accessible) on different systems (internal hard drive, cloud storage, etc.).
  - a "production" (working) copy
  - a "production backup" copy
- **1** copy is in another location ("off-site") from the others with a trusted service provider.

{: .new-title}
> Example
>
> 1 copy is stored locally on **hard drive** for analysis  
> 1 copy is stored on **cloud storage** platform  
> 1 copy is stored in a **secure campus drive**

If you want to learn more about data backups, check out our workshop "[Strategies for Research Data Storage and Backup](https://scds.github.io/intro-rdm/storage.html)".

## Research Data Storage Finder Tool

McMaster provides a research data storage finder tool online, which is an interactive tool to help you find, compare, and get access to different storage solutions depending on risk, volume, and other needs.

You can access this tool at <https://rdm.mcmaster.ca/finder>.

<img width="100%" alt="the three different story view buttons" src="../assets/img/lessons/sec1.png" style="border: solid 2px black; grid-row-start: 1; grid-column-start: 2; margin: auto; display: block"> 

## How Should I Protect my Data?

### Encrypt Sensitive Data
<div style="width:45%; float: right; margin-left: 10px" markdown="1">
  <img src="../assets/img/lessons/sensitive-data.png" style="border-radius: 30px" alt="" width="100%">  
  <ins>Image credit: [Kevin Patrick Robbins, “Moms to Babies Research, Focus Group,” June 19, 2018, McMaster Asset Bank](https://brand-resources.mcmaster.ca/asset-bank/action/viewAsset?id=7293&index=21&total=68&view=viewSearchItem)</ins>
</div>
  
Sensitive data is any data that could cause harm if released openly. This includes personally identifiable information or personal health information. It can also include confidential business information (such as data that might lead to a patent), sensitive ecological information (like nesting sites for endangered species), or Indigenous cultural pracitces. 

Sensitive data stored on a device that is connected to the internet should be encrypted. Encryption is when information is changed so only a person with the correct password can read it. 

- Use **"Full disk encryption"** if you are using a personal computer or laptop. This is called FileVault on Mac OS and "device encryption" or Bitlocker on Windows.
- Encrypt individual files in Microsoft Office using the "Protect Document" function.
- Other files can be encrypted using Disk Utility on Mac OS or with a third-party tool like [VeraCrypt](https://www.veracrypt.fr/en/Home.html).

For more details about working with and managing sensitive data, check out our workshop "[Securely Managing and Publishing Sensitive Data](https://scds.github.io/intro-rdm/sensitive.html)".

### Enable Multi-Factor Authenticator (MFA)

- Also known as 2 factor authentication (2FA).
- Requires more than one code or 'Factor' to login - typically 2 factors: password and a security code sent to your phone number or generated by a linked authenticator app.
- Many other web services (Gmail, Dropbox, etc) support MFA.
- MFA is now mandatory for McMaster students, faculty, and staff - [learn more here](https://office365.mcmaster.ca/mfa/#tab-content-getting-started).

### Password Best Practices

Make sure your online information is secure by ensuring your password is:

**Strong**
: Make a strong password by combining a series of numbers, letters, and symbols into a long series of words. Try to combine them into something memorable - Like L1br@ryt1pS.

**Unique**
: Use a different password for every website/service.

**Secret**
: Never share your passwords with anybody, even if you trust them. Keep your passwords secret by storing them only in your head. Never send them in an email!

**Fresh**
: Change your password once a year or following notification of a data breach.

**Devices**
: Use a strong password on your computer and phone, too.

{: .note-title}
> Tip
>
> Remembering multiple passwords can be difficult. Use a trusted password manager to keep track of your passwords for you. Some examples are [BitWarden](https://bitwarden.com/) and [1Password](https://1password.com/).

### Common Password Mistakes
Make sure your passwords aren't:

Written Down
: Passwords written down on a piece of paper or stored in plain text on a computer may be stolen by somebody with malicious intent or easily lost.

Too Simple
: Simple or common passwords are easy to guess or brute-force. Examples: apple, rowboat, bumblebee, blizzard, password, admin

Identical
: Using the same password for multiple websites is like having one key for multiple locks; if it's stolen, the thief can open them all.

<img src="../assets/img/lessons/bad-passwords.png" alt="an image of password bad practices: stored in a spreadsheet, and all of them are football" width="70%"  style="margin: auto; display: block">

For more tips on data privacy, check out our [Data Privacy Best Practices](https://scds.github.io/intro-rdm/privacy.html) workshop.

### Try this quick quiz - Try and guess which of the following practices for storing, securing, and backing up data are <u>true</u> or <u>false</u>?

<iframe src="https://h5pstudio.ecampusontario.ca/h5p/57143/embed" width="672" height="256" frameborder="0" allowfullscreen="allowfullscreen"></iframe><script src="https://h5pstudio.ecampusontario.ca/modules/contrib/h5p/vendor/h5p/h5p-core/js/h5p-resizer.js" charset="UTF-8"></script>

## Key Points / Summary

- Data security can prevent unwanted data access and loss.
- You should have 3 copies of your data, 2 of which should be easily accessible, and 1 should be stored in another location.

## Additional Resources
- [Research Data Storage Finder Tool](https://rdm.mcmaster.ca/finder)
- Disk Encryption Tool: [VeraCrypt](https://www.veracrypt.fr/en/Home.html)
- Password Managers: [BitWarden](https://bitwarden.com/), [1Password](https://1password.com/)

### Workshops
- [Strategies for Research Data Storage and Backup](https://scds.github.io/intro-rdm/storage.html)
- [Securely Managing and Publishing Sensitive Data](https://scds.github.io/intro-rdm/sensitive.html)
- [Data Privacy Best Practices](https://scds.github.io/intro-rdm/privacy.html)
