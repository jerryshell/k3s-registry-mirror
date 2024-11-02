# K3s Registry Mirror

[GFW](https://en.wikipedia.org/wiki/Great_Firewall) is such a "great" thing to help me learn technology 🙃

```bash
vim /etc/rancher/k3s/registries.yaml
```

```yaml
mirrors:
  docker.io:
    endpoint:
      - https://dockerpull.org
  registry.k8s.io:
    endpoint:
      - https://k8s.m.daocloud.io
```

```bash
systemctl restart k3s
```

## More

[https://www.wangdu.site/course/2109.html](https://www.wangdu.site/course/2109.html)

## LICENSE

[GNU Affero General Public License v3.0](https://choosealicense.com/licenses/agpl-3.0/)
