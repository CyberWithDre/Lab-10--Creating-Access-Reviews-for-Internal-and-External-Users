# Lab-10--Creating-Access-Reviews-for-Internal-and-External-Users
In this exercise, I created an internal access review in the Microsoft Entra admin center. I defined the review scope, selected a reviewer, and configured a review schedule. This exercise showed how access reviews are used to regularly validate group access and support identity governance.

<h2>https://youtu.be/ZnrF8z1B-pk<h2>
<h2>Walk-through:</h2>

<p align="center">
Sign in to Microsoft Entra admin center at https://entra.microsoft.com as Global Administrator.
  In the left navigation menu, expand the ID Governance, select Access reviews: <br/>
<img src=https://i.imgur.com/sj7IkVt.png/>
<br />
<br />
Select + New access review.....
  
  On the Create an access review page, under Choose an Access Review template, on the Resource review tile, select Select.  <br/>
<img src=https://i.imgur.com/mIghkUR.png/>
<br />
<br />
On the New access review page, under the Select what to review, open the Select review dropdown and select Teams + Groups.
Under the Review scope, select Select Teams + groups.
<img src=https://i.imgur.com/sR8EXih.png/>
<br />
<br />
Under the Group, select + Select group(s)
From the Select group pane, select Sales group from the list, and select Select:  <br/>
<img src=https://i.imgur.com/HqNwl9D.png/>
<br />
<br />Under the Scope, select All users
Select Next: Reviews :  <br/>
<img src=https://i.imgur.com/p9NuoQ2.png>
<br />


<br />On the Reviews tab, under Specify reviewers, open the Select reviewers dropdown and select Selected user(s) or group(s).

Under Users or Groups, select + Select reviewers.

In the Select reviewers pane, search for Joe Miles, select the user, and then select Select.

Under Specify recurrence of review, configure the following:
Duration (in days): keep the default value
Review recurrence: Annually
Start date: keep the default value
Select Next: Settings.:  <br/>
<img src=https://i.imgur.com/LPnKqm6.png/>
<img src=https://i.imgur.com/6FRxx8f.png/>
<img src=https://i.imgur.com/gcIc49u.png>

<br />Select Next: Review + Create.
<img src=https://i.imgur.com/LtIO1Fh.png>

<br />On the Review + Create tab enter my access review name and click create.
<img src=https://i.imgur.com/9lkmSav.png>



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
