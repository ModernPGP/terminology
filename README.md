Terminology
===========

A collection of agreed upon terminology to presented to end users


The following is dump of working session held at the GnuPG summit, April 19, 2015


-----------------------------------------

Here are the recommended end-user facing terms
"If you are going to expose these terms to the users (which is definitely not mandatory), which terms shall they be?"

Meta:
-----

- do it for any language
- how do we maintain this doc ? (github repo using markdown on modernpgp)
- doing user test cases on those terms could be great
- for each term, put a precise english description of it.
- put a "ranking" on those terms to say whether they better be exposed to the user or definitely not
- also write down the horrible terms we should definitely NOT use, to remember we expelled them

- other (non PGP specific) security & privacy icons under development - https://github.com/opensourcedesign/icons

English, 2015 pgp meeting, Dreieich
-----------------------------------

PGP vs OpenPGP vs GPG vs...

Headers / protected headers

Smartcard / Hardware token 

Key capabilities / Key usage

Keyring / Contacts 

Fingerprint / Key Address
> strong discussion, key
> Maybe "Verification Code" ?

How to visualise a valid signature with expired key

Refresh / Upload / Update 

PGP / PGPMime

Certificate / Key / Key block

Key owner Trust / identity Validity

Private / Secret Key
 > replace it by "my key"  and "your key" (or equivalent) ??

Passphrase / Password 
 > password, 
 because people should use phrases as password anyway, 
 so better stick with password, that is everywhere people should use phrases
 "Mantra" (blacklist)

Keyserver / Cloud 

Encryption / Protection 

Not Trusted / Expiry / Revoked

Key Size / Algorithm / Strength

Signed / Certified / Authenticated / Untampered 

UserID / Identity

Exportable Certificate 

User Verification / Key Verification / Key-User assignement 
> What about "Identity confirmation" or "Confirm Identity" ?

We put the following terms to Blacklist
---------------------------------------

inline-pgp / pgp-mime
short key-id / long key-id / key-i




Icons
-----


(just saying
a padlock shall be shown WIDE OPEN, not "slightly" )

BAD   GOOD 
---     ---
! !     ! !
!       !  
+-+   +-+  
! !   ! !  
+-+   +-+  




