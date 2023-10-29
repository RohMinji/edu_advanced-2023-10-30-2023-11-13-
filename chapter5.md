
보안

```bash
[root@bastion elastic]# kubectl api-resources -o wide
NAME                                  SHORTNAMES                         APIVERSION                                    NAMESPACED   KIND                                 VERBS
bindings                                                                 v1                                            true         Binding                              [create]
componentstatuses                     cs                                 v1                                            false        ComponentStatus                      [get list]
configmaps                            cm                                 v1                                            true         ConfigMap                            [create delete deletecollection get list patch update watch]
endpoints                             ep                                 v1                                            true         Endpoints                            [create delete deletecollection get list patch update watch]
events                                ev                                 v1                                            true         Event                                [create delete deletecollection get list patch update watch]
limitranges                           limits                             v1                                            true         LimitRange                           [create delete deletecollection get list patch update watch]
namespaces                            ns                                 v1                                            false        Namespace                            [create delete get list patch update watch]
nodes                                 no                                 v1                                            false        Node                                 [create delete deletecollection get list patch update watch]
persistentvolumeclaims                pvc                                v1                                            true         PersistentVolumeClaim                [create delete deletecollection get list patch update watch]
persistentvolumes                     pv                                 v1                                            false        PersistentVolume                     [create delete deletecollection get list patch update watch]
pods                                  po                                 
...
```  

<br/>
