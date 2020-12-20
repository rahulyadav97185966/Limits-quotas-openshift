# Limits-quotas-openshift

    vi myquota.yml : compute resource yaml copy from cluster administration.
    oc project fedora
    ls
    oc create -f myquota.yml 
    oc describe quota myquota 
    cat > mylimit.yml   : limit range file 
    vi mylimit.yml  
    oc create -f mylimit.yml 
    oc describe limitrange mylimit 
