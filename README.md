<!--
N.B.: This README was edited by hand.
-->

<h1>
  Wiki-Go, packaged for YunoHost
</h1>

Databaseless flat-file wiki platform

**Warning**: Testing purpose only. Do NOT commit nothing FROM this branch.

Links :

- Wiki-Go repository: <https://github.com/leomoon-studios/wiki-go>
- YNH Wiki-Go package: <https://github.com/YunoHost-Apps/wiki-go_ynh>

Branch can be tested using:
```
# fresh install:
sudo yunohost app install https://github.com/bugsysop/wiki-go_ynh/tree/tmprs_250610

# upgrade an existing install:
sudo yunohost app upgrade wiki-go -u https://github.com/bugsysop/wiki-go_ynh/tree/tmprs_250610
```
You may also be interested in specifying the following parameters for yunohost app install command:

- `--debug` : prints detailed log information
- `--no-remove-on-failure` : won't remove the app if the install fails - therefore you can analyze and manually run/debug stuff, typically in /var/www/$app
- `--force` : so that you are not asked confirmation if the app is not safe to use (low quality, experimental or 3rd party), or when the app displays a post-install notification.

App packaging for YNH documentation: <https://doc.yunohost.org/packaging_apps>

---
### Logs

```
OK -- install
OK -- Uninstall
OK -- use of `is_admin` in `config.yaml`  
OK -- post-install notice in YNH Admin
OK -- edit config file from admin
OK -- backup
OK -- restore from backup
OK -- upgrade to same version (1.4.5~ynh1 > 1.4.5~ynh1)
OK -- upgrade (1.4.5~ynh1 > 1.5.6~ynh1)
OK -- change URL
```
---  
