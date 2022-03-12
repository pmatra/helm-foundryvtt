# helm-foundryvtt
helm template for foundryvtt
----don't forget the charts directory. It is empty in this template.

use image from docker.io/petermatra/foundryvtt89  TAG: latest
also there is docker.io/petermatra/foundryvtt9 TAG: latest that is not always kept up to date.

registry.gitlab.com/nypedro/foundryvttver9 TAG: main  THIS is my CI/CD pipeline that is mostly kept up to date

a Peristant Volume called 'foundry-data-pvc' must be created first for this to work.
