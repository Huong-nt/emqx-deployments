

### Exec command in pod:
```sh
~$ kubectl exec -it emqx-6d8597777c-jlzsz /bin/sh
/opt/emqx $ ./bin/emqx_ctl cluster status
Cluster status: [{running_nodes,['emqx@10.244.1.10','emqx@10.244.0.13']},
                 {stopped_nodes,['emqx@10.244.1.8']}]
/opt/emqx $ exit
```

### Reference:
```
https://github.com/emqx/emqx/issues/2608
```