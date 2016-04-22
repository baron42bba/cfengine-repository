# JB CFEngine repository
Repository of reusable CFEngine policy files. This repository contains number of policy files and their data files in form 
of JSON or YAML files. Reusability is achieved by displacing data values to data files and it shall be easily to adapt it to 
own needs or to different computer nodes. Files with no data files, contain pretty much static content that shall not change. 

Easy deployment is enabled with my fork of CFEngine masterfiles fork [here](https://github.com/jborozan/masterfiles).

## Files

Files will be explained in short together with own data files in subsequent paragraphs.

### jb_STIGs.cf & jb_STIGs.json

Implementation of many recomendations from [STIGs](https://www.stigviewer.com/stigs) site for Redhat/CentOS.

### jb_user.cf & jb_user.json

Policy file to create users on client.

### jb_vim.cf & jb_vim.json

Policy to install vim and CFEngine syntax extensions from Neil Watson.

### jb_yum_repos_epel.cf

Installs EPEL repository for yum.
	
### jb_yum_repos_glusterfs.cf

Installs Gluster FS repository for yum.

### jb_yum_repos_mariadb.cf

Installs Maria DB repository for yum.

### jb_yum_repos_mysql_community.cf

Installs Mysql community repository for yum.

### jb_yum_repos_nginx.cf

Installs nginx repository for yum.

### jb_yum_repos_vmware.cf

Installs VMware repository for yum.

