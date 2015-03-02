'es-status' is a simple script to get a status of a node/cluster Elasticsearch

The usage is as following:
```bash
./es-status -h
         FILE: es-status

        USAGE: es-status [HOST PORT] [--help]

      OPTIONS: --help        this help
               HOST          host to use - default localhost
               PORT          port to connect to - default 9200

  DESCRIPTION: es-status shows status and health of a Elasticsearch cluster/node.


      VERSION: 0.1
       AUTHOR: Hugo Rosnet <hugo.rosnet@enovance.com>
      COMPANY: eNovance
```

Output of the script:
```bash
$  ./es-status localhost 9200

                    CLUSTER STATUS

             Cluster name:   cpl-search-sup
           Cluster status:   Green
             Cluster size:   3
                    Ready:   YES

--------------------------------------------------------
   NODE STATUS

                 Heap max:   1007.3mb
          Heap percentage:   74%
               Memory max:   3.6gb
        Memory percentage:   85%

--------------------------------------------------------
  SHARD STATUS

         Shard successful:   115
               Shard fail:   0
         Shard relocating:   0
       Shard initialising:   0
         Shard unassigned:   0
              Shard total:   115
```

Output on the screen:
TO BE ADDED

Note:
So far this is a first version, hasen't been deeply tested, or improved. Feel free to report any problem using it.
