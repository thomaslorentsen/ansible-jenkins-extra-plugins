# Jenkins Extra Plugins

```yaml
- host: all
  roles:
    - jenkins-extra-plugins
```

Passing plugin to install with ```vars.yml```.
```yaml
jenkins_plugins_manual:
  - name: ansible-tower
    url: http://updates.jenkins-ci.org/download/plugins/ansible-tower/0.8.5/ansible-tower.hpi
    checksum: sha256:177694dda4dfed6ef2daa57b811fa57c4b2a2307c6b0e0df456a81e2f35bc8ef
```
