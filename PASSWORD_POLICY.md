# Passowrd Policy

## 1. Overview

Passwords are an important aspect of computer security. A poorly chosen password may result in unauthorized access
and/or exploitation of our resources. All staff, including contractors and vendors with access to simfiny LLC systems,
are responsible for taking the appropriate steps, as outlined below, to select and secure their passwords.

## 2. Purpose

The purpose of this policy is to establish a standard for creation of strong passwords and the
protection of those passwords.

## 3. Scope

The scope of this policy includes all personnel who have or are responsible for an account (or any form of access that
supports or requires a password) on any system that resides at any simfiny LLC facility, has access to the simfiny LLC
network, or stores any nonpublic simfiny LLC information.

## 4. Policy

### 4.1 Password Creation

**4.1.1** All user-level and system-level passwords must conform to the [_Password Construction
Guidelines_](PASSWORD_CONSTRUCTION_GUIDELINES.md).

**4.1.2** Users must use a separate, unique password for each of their work related accounts. Users may not use any work
related passwords for their own, personal accounts.

**4.1.3** User accounts that have system-level privileges granted through group memberships or programs such as sudo
must have a unique password from all other accounts held by that user to access system-level privileges. In addition, it
is required that some form of multi-factor authentication is used for any privileged accounts.

### 4.2 Password Change

**4.2.1** Passwords should be changed when there is reason to believe a password has been compromised.

**4.2.2** Password cracking or guessing may be performed on a periodic or random basis by the InfoSec Team or its
delegates. If a password is guessed or cracked during one of these scans, the user will be required to change it to be
in compliance with the [_Password Construction Guidelines_](PASSWORD_CONSTRUCTION_GUIDELINES.md).

### 4.3 Password Protection

**4.3.1** Passwords must not be shared with anyone, including supervisors and coworkers. All passwords are to be treated
as sensitive, Confidential simfiny LLC information.

**4.3.2** Passwords must not be inserted into email messages, Alliance cases or other forms of electronic communication,
nor revealed over the phone to anyone.

**4.3.3** Passwords may be stored only in the 1Password password management software authorized and provided by the
organization.

**4.3.4** Do not use the "Remember Password" feature of applications (for example, web browsers).

**4.3.5** Any user suspecting that their password may have been compromised must report the incident and change all
passwords.

### 4.4 Application Development

Application developers must ensure that their programs contain the following security precautions:

**4.4.1** Applications must support authentication of individual users, not groups.

**4.4.2** Applications must not store passwords in clear text or in any easily reversible form.

**4.4.3** Applications must not transmit passwords in clear text over the network.

### 4.5 Multi-Factor Authentication

**4.5.1** Multi-factor authentication is required and should be used whenever possible, not only for work related
accounts but personal accounts also.

**4.5.2** SMS/Email is not a secure form of multi-factor authentication and is only permitted if the application does
not support any other forms of multi-factor authentication.

**4.5.3** If an application support hardware-key multi-factor authentication then it is required to use that over any
other method of multi-factor authentication.

## 5. Policy Compliance

### 5.1 Compliance Measurement

The InfoSec team will verify compliance to this policy through various methods, including but not limited to, business
tool reports, internal and external audits, and feedback to the policy owner.

### 5.2 Exceptions

Any exception to the policy must be approved by the InfoSec team in advance.

### 5.3 Non-Compliance

An employee found to have violated this policy may be subject to disciplinary action, up to and including termination of
employement.
