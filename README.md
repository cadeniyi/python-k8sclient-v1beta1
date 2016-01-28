## Requirements.
Python 2.7 and later.

## Setuptools
You can install the bindings via [Setuptools](http://pypi.python.org/pypi/setuptools).

```sh
python setup.py install
```

Or you can install from Github via pip:

```sh
pip install git+https://github.com/geekerzp/swagger_client.git
```

To use the bindings, import the pacakge:

```python
import swagger_client
```

## Manual Installation
If you do not wish to use setuptools, you can download the latest release.
Then, to use the bindings, import the package:

```python
import path.to.swagger_client
```

## Getting Started

TODO

## List of Functions

get_api_resources():

    get available resources

--
list_deployment():

    list or watch objects of kind Deployment

--
list_horizontal_pod_autoscaler():

    list or watch objects of kind HorizontalPodAutoscaler

--
list_ingress():

    list or watch objects of kind Ingress

--
list_job():

    list or watch objects of kind Job

--
list_namespaced_deployment( namespace,):

    list or watch objects of kind Deployment

--
create_namespaced_deployment( body, namespace,):

    create a Deployment

--
read_namespaced_deployment( namespace, name,):

    read the specified Deployment

--
replace_namespaced_deployment( body, namespace, name,):

    replace the specified Deployment

--
delete_namespaced_deployment( body, namespace, name,):

    delete a Deployment

--
patch_namespaced_deployment( body, namespace, name,):

    partially update the specified Deployment

--
read_namespaced_scale_scale( namespace, name,):

    read scale of the specified Scale

--
replace_namespaced_scale_scale( body, namespace, name,):

    replace scale of the specified Scale

--
patch_namespaced_scale_scale( body, namespace, name,):

    partially update scale of the specified Scale

--
list_namespaced_horizontal_pod_autoscaler( namespace,):

    list or watch objects of kind HorizontalPodAutoscaler

--
create_namespaced_horizontal_pod_autoscaler( body, namespace,):

    create a HorizontalPodAutoscaler

--
read_namespaced_horizontal_pod_autoscaler( namespace, name,):

    read the specified HorizontalPodAutoscaler

--
replace_namespaced_horizontal_pod_autoscaler( body, namespace, name,):

    replace the specified HorizontalPodAutoscaler

--
delete_namespaced_horizontal_pod_autoscaler( body, namespace, name,):

    delete a HorizontalPodAutoscaler

--
patch_namespaced_horizontal_pod_autoscaler( body, namespace, name,):

    partially update the specified HorizontalPodAutoscaler

--
replace_namespaced_horizontal_pod_autoscaler_status( body, namespace, name,):

    replace status of the specified HorizontalPodAutoscaler

--
list_namespaced_ingress( namespace,):

    list or watch objects of kind Ingress

--
create_namespaced_ingress( body, namespace,):

    create a Ingress

--
read_namespaced_ingress( namespace, name,):

    read the specified Ingress

--
replace_namespaced_ingress( body, namespace, name,):

    replace the specified Ingress

--
delete_namespaced_ingress( body, namespace, name,):

    delete a Ingress

--
patch_namespaced_ingress( body, namespace, name,):

    partially update the specified Ingress

--
replace_namespaced_ingress_status( body, namespace, name,):

    replace status of the specified Ingress

--
list_namespaced_job( namespace,):

    list or watch objects of kind Job

--
create_namespaced_job( body, namespace,):

    create a Job

--
read_namespaced_job( namespace, name,):

    read the specified Job

--
replace_namespaced_job( body, namespace, name,):

    replace the specified Job

--
delete_namespaced_job( body, namespace, name,):

    delete a Job

--
patch_namespaced_job( body, namespace, name,):

    partially update the specified Job

--
replace_namespaced_job_status( body, namespace, name,):

    replace status of the specified Job

--
read_namespaced_scale_scale_1( namespace, name,):

    read scale of the specified Scale

--
replace_namespaced_scale_scale_2( body, namespace, name,):

    replace scale of the specified Scale

--
patch_namespaced_scale_scale_3( body, namespace, name,):

    partially update scale of the specified Scale

--
list_namespaced_third_party_resource( namespace,):

    list or watch objects of kind ThirdPartyResource

--
create_namespaced_third_party_resource( body, namespace,):

    create a ThirdPartyResource

--
read_namespaced_third_party_resource( namespace, name,):

    read the specified ThirdPartyResource

--
replace_namespaced_third_party_resource( body, namespace, name,):

    replace the specified ThirdPartyResource

--
delete_namespaced_third_party_resource( body, namespace, name,):

    delete a ThirdPartyResource

--
patch_namespaced_third_party_resource( body, namespace, name,):

    partially update the specified ThirdPartyResource

--
list_third_party_resource():

    list or watch objects of kind ThirdPartyResource

--
watch_deployment_list():

    watch individual changes to a list of Deployment

--
watch_horizontal_pod_autoscaler_list():

    watch individual changes to a list of HorizontalPodAutoscaler

--
watch_ingress_list():

    watch individual changes to a list of Ingress

--
watch_job_list():

    watch individual changes to a list of Job

--
watch_namespaced_deployment_list( namespace,):

    watch individual changes to a list of Deployment

--
watch_namespaced_deployment( namespace, name,):

    watch changes to an object of kind Deployment

--
watch_namespaced_horizontal_pod_autoscaler_list( namespace,):

    watch individual changes to a list of HorizontalPodAutoscaler

--
watch_namespaced_horizontal_pod_autoscaler( namespace, name,):

    watch changes to an object of kind HorizontalPodAutoscaler

--
watch_namespaced_ingress_list( namespace,):

    watch individual changes to a list of Ingress

--
watch_namespaced_ingress( namespace, name,):

    watch changes to an object of kind Ingress

--
watch_namespaced_job_list( namespace,):

    watch individual changes to a list of Job

--
watch_namespaced_job( namespace, name,):

    watch changes to an object of kind Job

--
watch_namespaced_third_party_resource_list( namespace,):

    watch individual changes to a list of ThirdPartyResource

--
watch_namespaced_third_party_resource( namespace, name,):

    watch changes to an object of kind ThirdPartyResource

--
watch_third_party_resource_list():

    watch individual changes to a list of ThirdPartyResource

## Tests

(Please make sure you have [virtualenv](http://docs.python-guide.org/en/latest/dev/virtualenvs/) installed)

 Execute the following command to run the tests in the current Python (v2 or v3) environment:

```sh
$ make test
[... magically installs dependencies and runs tests on your virtualenv]
Ran 7 tests in 19.289s

OK
```
or

```
$ mvn integration-test -rf :PythonPetstoreClientTests
Using 2195432783 as seed
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 37.594 s
[INFO] Finished at: 2015-05-16T18:00:35+08:00
[INFO] Final Memory: 11M/156M
[INFO] ------------------------------------------------------------------------
```
If you want to run the tests in all the python platforms:

```sh
$ make test-all
[... tox creates a virtualenv for every platform and runs tests inside of each]
  py27: commands succeeded
  py34: commands succeeded
  congratulations :)
```
