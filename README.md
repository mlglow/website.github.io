# MLGlow
The code for the websites: www.mlglow.com/www.mlglow.eu


# (1) Steps in Domain
* Add the follwing DNS entries in Domains "www.mlglow.com" & "www.mlglow.eu"
  - @	A	10800	185.199.108.153	
  - @	A	10800	185.199.109.153	
  - @	A	10800	185.199.110.153	
  - @	A	10800	185.199.111.153
  - www	CNAME	10800	mlglow.github.io.
    - Delete if exists "www CNAME ..." entry in the DNS


# (2) Steps in Github (One Repo)
* Name the repo as <suitable_name>
* Crete the HTML website 
* Create a file "CNAME" with "www.mlglow.com" as the only content
* Push to the "main" branch
* Under "Actions"
  - Select the workflow template for GitHub pages
  - Commit to the "main" branch
  - Check in "Pages" if the site is deployed
  


# (3) Steps in Github (Another Repo)
* Name the repo as <suitable_name>.github.io
* Add the same contents of the other repo (i.e., <suitable_name>)
* Adapt the file "CNAME" with "www.mlglow.eu" as the only content
* Push to the "main" branch
* The deployment should start automatically
* Check in "Pages" if the site is deployed
  

# Useful Resources
* https://deanattali.com/blog/multiple-github-pages-domains/
