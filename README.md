Cloud Shift
===========
Red Hat's [OpenShift](https://openshift.com/) deployment-manager for [Google Cloud Platform (GCP)](https://cloud.google.com/)

## Resource list

### `region` & `zone`
```bash
$ gcloud compute regions list
$ gcloud compute zones list
```

### `machineType`
```bash
$ gcloud compute machine-types list
```
Value may of following forms:
1. `https://www.googleapis.com/compute/v1/projects/foobar/zones/us-central1-f/machineTypes/n1-standard-1`
2. `zones/us-central1-f/machineTypes/n1-standard-1`
3. `n1-standard-1`

### `sourceImage`
```bash
$ gcloud compute images list
```
Value may of following forms:

1. `https://www.googleapis.com/compute/v1/projects/debian-cloud/global/images/family/debian-8`
2. `https://www.googleapis.com/compute/v1/projects/debian-cloud/global/images/debian-8-jessie-vYYYYMMDD`
3. `projects/debian-cloud/global/images/family/debian-8`
4. `projects/debian-cloud/global/images/debian-8-jessie-vYYYYMMDD`
5. `global/images/family/my-image-family`
6. `global/images/my-image`
