# selva
The code for the website: www.mlglow.com. 

# Steps in Github
* Crete the HTML website 
* Create a file "CNAME" with "www.mlglow.com" as the only content
* Push to the "main" branch
* Under "Actions"
  - Select the workflow template for GitHub pages
  - Commit to the "main" branch
  - Check in "Pages" if the site is deployed
  
# Steps in Domain
* Add the follwing DNS entries
  - @	A	10800	185.199.108.153	
  - @	A	10800	185.199.109.153	
  - @	A	10800	185.199.110.153	
  - @	A	10800	185.199.111.153
  - www	CNAME	10800	mlglow.github.io.
    - Delete if exists "www CNAME ..." entry in the DNS
