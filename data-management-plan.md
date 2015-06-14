---
title: Data Management Plan
author: William A. Stein
---

All data generated in this SBIR Phase I project is considered proprietary.

# Sharing of Primary Data: Computer Code

As stated in the proposal, one of the aims is to develop software for inclusion
in SageMathCloud.  This code will be progressively integrated into the
SageMathCloud codebase.  All software included in SageMathCloud that we produce will be
distributed under the copyright terms of the GNU General
Public License (GPL) (see http://www.gnu.org/licenses/). This
license requires that the source code be made available to all users of the
software, who in turn have the right to modify and distribute the software,
provided that they use a compatible license.  This is a standard license in
the world of open source software, designed for widespread dissemination and
sharing of the source-code behind the software, as well as any derivative
works.

# Other Data: SageMathCloud User Data

User data, including interactive homework problems, are
proprietary, and we protect it according to our Terms
of Service and Privacy Policies, which are described
at https://cloud.sagemath.com/policies.  This data will not be
dissimenated, except as laid out in the above policies.

We backup user data as follows:

1. The files in projects sit on a VM at Google, whose filesystem
is snapshotted twice per day, with snapshots saved for about 10 days.
2. The files are rsync'd to another server whenever the project is
saved (so every 5 minutes when actively used).
3. The files and the second server are snapshotted using btrfs with
snapshots saved for years (but trimmed over time).
4. Every 8 hours an incremental tarball is made of modified projects
and saved in a Google cloud storage nearline bucket.
5. At least once per week (and usually once per day), we rsync the new
incremental tarballs to an encrypted USB drive, which is usually not
connected to the Internet (and physically with me in most cases).
6. Once per week we rsync that usb drive to another encrypted USB
drive sitting at the headquarters of SageMath, Inc.
7. Once per month we swap that USB drive from step 6 out with another
encrypted USB drive that is kept in a locked office at University of
Washington.