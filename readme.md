
- message d'erreur
```
max virtual memory areas vm.max_map_count [65530] is too low, increase to at least [262144]
```


- Solution officielle [Official Solution](https://www.elastic.co/guide/en/elasticsearch/reference/current/docker.html#_set_vm_max_map_count_to_at_least_262144)

// se connecter à wsl docker
```
wsl -d docker-desktop
```

// command to set max map count to 262144
```
sysctl -w vm.max_map_count=262144
```

