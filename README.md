# Riak for Red Hat OpenShift

## This doesn't work yet :-(

A work in progress

Based on:
https://github.com/marianoguerra/couchdb-for-openshift

# Usage

```
cd my-openshift_app
git remode add riak-for-openshift git@github.com:metadave/riak-for-openshift.git
git pull -s recursive -X theirs riak-for-openshift master
git push
```


# IMPORTANT NOTE!
This only deploys a single Riak node for development. Basho recommends at least **5** nodes to run Riak in a production environment.


