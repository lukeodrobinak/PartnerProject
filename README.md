# PartnerProject

Computer Science AT project with Ethan Ayers 
Practicing GIT!!!

Q1:
  When _clone_ is used, it sets the origin to represent the branch cloned is called on, including the whole history.
Q2:
  _git push --set -upstream origin master_ sets the current local branch to the remote branch. Remote tracking is tracking the changes between the local copy and the remote branch.
Q3:
  _git pull origin master_ will pull the branch from the remote main and merge it to the local branch. This takes all staged changes locally and combines them with the remote origin, then combines them into one local branch.
Q4:
  _git pull origin master_ acted as a merge, combining both local and remote branches and keeping both of their changes, which doesn't overwrite the local changes.
Q5:
  The standard use of _git pull origin master_ is a merge, but it can be changed to rebase using flags.
Q6:
  Still behind the remote master
Q7:
  The branch did not delete locally on person B's repo. Removed it with _git branch -d branchy_
Q8:  
``*   commit 1d505abc2fbda4e16b6ba1acb17583d7e2e258f7 (HEAD -> main, origin/main, origin/HEAD)
|\  Merge: 7b41843 ef5c597
| | Author: lukeodrobinak <98421230+lukeodrobinak@users.noreply.github.com>
| | Date:   Mon Oct 2 08:46:00 2023 -0600
| | 
| |     Merge pull request #2 from lukeodrobinak/Feature2
| |     
| |     Overwrote Ethans changes to fix merge conflict!
| |   
| *   commit ef5c597f4ebc479727ce945ff9002bbf272f503d
| |\  Merge: 0bc15fe 7b41843
| |/  Author: lukeodrobinak <98421230+lukeodrobinak@users.noreply.github.com>
|/|   Date:   Mon Oct 2 08:45:27 2023 -0600
| |   
| |       Merge branch 'main' into Feature2
| |   
* |   commit 7b41843099c1642954c99f5cad574d3fa58c8150
|\ \  Merge: 8ce2448 bce9781
| | | Author: Zenitore <eayers25@kentdenver.org>
| | | Date:   Mon Oct 2 08:42:19 2023 -0600
| | | 
| | |     to make a pull
``
