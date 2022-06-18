Задача 1. 

https://ibb.co/JFW2m4b

Задача 2. 

https://ibb.co/BtnNknw

Задача 3. 

На шаге Installing tools, ansible вываливается с ошибкой:

TASK [Installing tools] **************************************************************************************************
failed: [node01.netology.cloud] (item=git) => {"ansible_loop_var": "item", "changed": false, "item": "git", "msg": "Unsupported parameters for (ansible.legacy.yum) module: package. Supported parameters include: lock_timeout, disable_excludes, exclude, allow_downgrade, disable_gpg_check, conf_file, use_backend, validate_certs, state, disablerepo, releasever, skip_broken, cacheonly, autoremove, download_dir, name (pkg), installroot, install_weak_deps, update_cache (expire-cache), download_only, bugfix, list, install_repoquery, update_only, disable_plugin, enablerepo, security, enable_plugin."}
failed: [node01.netology.cloud] (item=curl) => {"ansible_loop_var": "item", "changed": false, "item": "curl", "msg": "Unsupported parameters for (ansible.legacy.yum) module: package. Supported parameters include: lock_timeout, disable_excludes, exclude, allow_downgrade, disable_gpg_check, conf_file, use_backend, validate_certs, state, disablerepo, releasever, skip_broken, cacheonly, autoremove, download_dir, name (pkg), installroot, install_weak_deps, update_cache (expire-cache), download_only, bugfix, list, install_repoquery, update_only, disable_plugin, enablerepo, security, enable_plugin."}

Насколько я понимаю, он не может установить из-за недоступности репозиториев.