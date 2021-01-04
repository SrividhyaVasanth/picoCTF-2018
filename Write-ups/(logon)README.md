 we use SQL injection and login with 'OR 1=1-- as the username and password
after that we can see that we have logged in but have not found the flag
<img width="610" alt="logon1" src="https://user-images.githubusercontent.com/76178081/103515423-b690c780-4e94-11eb-8d71-38c75e294d31.PNG">
Next, we go to the cookie editor and export the cookies
While we are importing the cookies we change the admin value to 'True' instead of 'False' and import the cookies

<img width="472" alt="logon2" src="https://user-images.githubusercontent.com/76178081/103515692-3323a600-4e95-11eb-900b-d84ef7f52e2e.PNG">

Next step is to refresh the page
After refreshing the page we will find the flag
