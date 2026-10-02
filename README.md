# CiaraForever
Let's make some changes
GoDaddy portal domain upates
- added TXT 
 - Changed on the GoDaddy portal CNAME www → ciaraforever.com.: This needs editing. It currently points back to your root domain (ciaraforever), which is GoDaddy's default. Click the pencil icon and change the value to your app's default hostname from the portal's Overview page (lively-cliff-09306341e.2.azurestaticapps.net). Then add www.ciaraforever.com in the app's Custom domains blade using CNAME validation.
 -Setup forwarding on GoDaddy Type - Temporary (302)

 -Static Web App → Custom domains → + Add → Custom domain on other DNS, enter www.ciaraforever.com, and choose CNAME validation.
