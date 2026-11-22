# OpenPrintHQ Installer License Agreement

Version 5, 22 November 2026.

This agreement is between you and James Norman, who develops and owns OpenPrintHQ ("we", "us"). It covers
the OpenPrintHQ installer: the manager container, its screens, its API and its documentation (the
"Installer"). Read it before you use the Installer. By choosing **Accept** you agree to it, for yourself
or for the organization you install for, and you confirm you may agree on its behalf. If you do not agree,
do not use the Installer.

## 1. What you may do

We grant you a non-exclusive, non-transferable license to install and run the Installer on computers you
own or control, to set up, run, back up, restore and update your own OpenPrintHQ installations, for as
long as this agreement is in force. If you obtained the Installer under a paid plan, the number of
installations, the term and the fees are those of your plan.

## 2. What you may not do

Except where the law gives you a right that this agreement cannot take away, you may not:

- copy, sell, rent, sublicense or distribute the Installer, or offer it to others as a service;
- reverse engineer, decompile or disassemble it, or try to recover its source code;
- remove or change any notice of ownership or license in it;
- get around any limit on how many installations you may run, or any check of your license.

## 3. Open-source software is not restricted by this agreement

The Installer sets up open-source software listed on this screen, among them the OpenPrintHQ hub and
OpenPrintHQ Farm, which are published under the GNU Affero General Public License, version 3. Each of
those programs is licensed to you by its own authors under its own license, not under this agreement.
Nothing here limits any right those licenses give you. The Installer pulls those programs from their
publishers when you ask it to; we do not redistribute them.

## 4. Your data, and the record of your acceptance

The Installer runs on your machine. It keeps its answers, plan and secrets in its own data volume, and
your backups where you choose. It does not send your data to us, except as this section says and what you
choose to send, such as a diagnostic bundle or optional telemetry where it is offered and you turn it on.

When you accept this agreement, or a new version of it, the Installer sends us a record of that acceptance,
and we keep it in a private repository on GitHub: the agreement's version and fingerprint (a SHA-256 hash
of its text), the time you accepted, the Installer's version, and a fingerprint of this installation. The
installation's fingerprint is a one-way SHA-256 hash of the installation's random identifier and the
identifier Docker gives this machine; it identifies the installation to us without containing either. The
record holds nothing else: no names, addresses, passwords, answers or data of yours. You can accept only
while the Installer can reach us to record it; until your acceptance is recorded, the Installer cannot be
used.

## 5. Ownership

James Norman develops and owns the Installer, the OpenPrintHQ hub and OpenPrintHQ Farm. The Installer is
licensed, not sold, and we and our licensors keep all rights in it that this agreement does not expressly
grant to you. The OpenPrintHQ hub and OpenPrintHQ Farm are licensed to you under the GNU Affero General Public
License, version 3, as section 3 says; owning them does not limit what that license lets you do.

## 6. Changes to this agreement

We may change this agreement in the future. A new version binds you only once you accept it: the Installer
shows it to you and asks you to accept it before you can go on using the Installer. Until you accept, the
version you last accepted still applies, and your OpenPrintHQ installations keep running. We may also offer
updates to the Installer.

## 7. No warranty

The Installer changes the computer it runs on: it starts containers, creates volumes and networks, and
configures services. Keep backups. To the extent the law allows, the Installer is provided "as is" and "as
available", without warranties of any kind, express or implied, including merchantability, fitness for a
particular purpose and non-infringement.

## 8. Limit of liability

To the extent the law allows, we are not liable for any indirect, incidental, special, consequential or
punitive damages, or for lost profits, revenue, data or business, arising from the Installer or this
agreement, even if we were told they were possible. Our total liability for any claim is limited to the
amount you paid for the Installer in the twelve months before the claim, or 1 US dollar if you paid
nothing.

## 9. Ending this agreement

You may end this agreement at any time by removing the Installer. It ends automatically if you break it.
When it ends you must stop using the Installer. Your OpenPrintHQ installations, the open-source software it
set up and your data stay yours and keep working.

## 10. General

This agreement is governed by the laws of the State of Iowa, United States, without regard to its rules on
conflict of laws. If a part of it cannot be enforced, the rest stays in force. It is the whole agreement
between you and us about the Installer, together with the terms of any paid plan.
