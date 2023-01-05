# weblogic-setup-automation-using-ansible
Full weblogic server set up using ansible

## How To

Clone this repository
```
git clone https://github.dev/Nirzak/weblogic-setup-automation-using-ansible.git
```
Download the weblogic setup jar file from here https://www.oracle.com/middleware/technologies/fusionmiddleware-downloads.html

Don't forget to change `- installer: "fmw_14.1.1.0.0_wls.jar"` according to your weblogic installer name.

Also update the inventory list according to your server list where you want to install weblogic.

After all things done correctly, just run the following command

```
ansible-playbook setup-weblogic.yml -i inventory
```

