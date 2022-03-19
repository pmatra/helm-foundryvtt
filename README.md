# helm-foundryvtt
helm template for foundryvtt
----don't forget the charts directory. It is a holder file in this template, delete it "delete.me".

use image from docker.io/petermatra/foundryvtt89  TAG: latest
also there is docker.io/petermatra/foundryvtt9 TAG: latest that is not always kept up to date.

registry.gitlab.com/nypedro/foundryvttver9 TAG: main  THIS is my CI/CD pipeline that is mostly kept up to date

a Peristant Volume Claim called 'foundry-data-pvc' must be created first for this to work with a host path of /foundry_data

These are the PVC Yamls you can use to create your Volume https://github.com/pmatra/foundryvtt-pvc-yamls
