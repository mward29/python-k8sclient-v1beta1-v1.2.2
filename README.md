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

json from https://raw.githubusercontent.com/kubernetes/kubernetes/8b0e9c5739d8e7df9a237a0364966c873fe1b51a/api/swagger-spec/extensions_v1beta1.json

## Manual Installation
If you do not wish to use setuptools, you can download the latest release.
Then, to use the bindings, import the package:

```python
import path.to.swagger_client
```

## To Generate your own swagger_client
`swagger-codegen generate -i v1.json -l python -o swagger_client`


## List of Functions


`create_namespaced_deployment(self,body,namespace)`

createaDeployment

--

`create_namespaced_deployment_rollback_rollback(self,body,namespace,name)`

createrollbackofaDeploymentRollback

--

`create_namespaced_horizontal_pod_autoscaler(self,body,namespace)`

createaHorizontalPodAutoscaler

--

`create_namespaced_ingress(self,body,namespace)`

createaIngress

--

`create_namespaced_job(self,body,namespace)`

createaJob

--

`create_namespaced_replica_set(self,body,namespace)`

createaReplicaSet

--

`create_third_party_resource(self,body)`

createaThirdPartyResource

--

`delete_namespaced_daemon_set(self,body,namespace,name)`

deleteaDaemonSet

--

`delete_namespaced_deployment(self,body,namespace,name)`

deleteaDeployment

--

`delete_namespaced_horizontal_pod_autoscaler(self,body,namespace,name)`

deleteaHorizontalPodAutoscaler

--

`delete_namespaced_ingress(self,body,namespace,name)`

deleteaIngress

--

`delete_namespaced_job(self,body,namespace,name)`

deleteaJob

--

`delete_namespaced_replica_set(self,body,namespace,name)`

deleteaReplicaSet

--

`delete_third_party_resource(self,body,name)`

deleteaThirdPartyResource

--

`deletecollection_namespaced_daemon_set(self,namespace)`

deletecollectionofDaemonSet

--

`deletecollection_namespaced_deployment(self,namespace)`

deletecollectionofDeployment

--

`deletecollection_namespaced_horizontal_pod_autoscaler(self,namespace)`

deletecollectionofHorizontalPodAutoscaler

--

`deletecollection_namespaced_ingress(self,namespace)`

deletecollectionofIngress

--

`deletecollection_namespaced_job(self,namespace)`

deletecollectionofJob

--

`deletecollection_namespaced_replica_set(self,namespace)`

deletecollectionofReplicaSet

--

`deletecollection_third_party_resource(self)`

deletecollectionofThirdPartyResource

--

`get_api_resources(self)`

getavailableresources

--

`list_namespaced_daemon_set(self)`

listorwatchobjectsofkindDaemonSet

--

`list_namespaced_daemon_set_1(self,namespace)`

listorwatchobjectsofkindDaemonSet

--

`list_namespaced_deployment(self)`

listorwatchobjectsofkindDeployment

--

`list_namespaced_deployment_2(self,namespace)`

listorwatchobjectsofkindDeployment

--

`list_namespaced_horizontal_pod_autoscaler(self)`

listorwatchobjectsofkindHorizontalPodAutoscaler

--

`list_namespaced_horizontal_pod_autoscaler_3(self,namespace)`

listorwatchobjectsofkindHorizontalPodAutoscaler

--

`list_namespaced_ingress(self)`

listorwatchobjectsofkindIngress

--

`list_namespaced_ingress_4(self,namespace)`

listorwatchobjectsofkindIngress

--

`list_namespaced_job(self)`

listorwatchobjectsofkindJob

--

`list_namespaced_job_5(self,namespace)`

listorwatchobjectsofkindJob

--

`list_namespaced_replica_set(self,namespace)`

listorwatchobjectsofkindReplicaSet

--

`list_namespaced_replica_set_6(self)`

listorwatchobjectsofkindReplicaSet

--

`list_third_party_resource(self)`

listorwatchobjectsofkindThirdPartyResource

--

`patch_namespaced_daemon_set(self,body,namespace,name)`

partiallyupdatethespecifiedDaemonSet

--

`patch_namespaced_deployment(self,body,namespace,name)`

partiallyupdatethespecifiedDeployment

--

`patch_namespaced_horizontal_pod_autoscaler(self,body,namespace,name)`

partiallyupdatethespecifiedHorizontalPodAutoscaler

--

`patch_namespaced_ingress(self,body,namespace,name)`

partiallyupdatethespecifiedIngress

--

`patch_namespaced_job(self,body,namespace,name)`

partiallyupdatethespecifiedJob

--

`patch_namespaced_replica_set(self,body,namespace,name)`

partiallyupdatethespecifiedReplicaSet

--

`patch_namespaced_scale_scale(self,body,namespace,name)`

partiallyupdatescaleofthespecifiedScale

--

`patch_namespaced_scale_scale_7(self,body,namespace,name)`

partiallyupdatescaleofthespecifiedScale

--

`patch_namespaced_scale_scale_8(self,body,namespace,name)`

partiallyupdatescaleofthespecifiedScale

--

`patch_third_party_resource(self,body,name)`

partiallyupdatethespecifiedThirdPartyResource

--

`read_namespaced_daemon_set(self,namespace,name)`

readthespecifiedDaemonSet

--

`read_namespaced_deployment(self,namespace,name)`

readthespecifiedDeployment

--

`read_namespaced_horizontal_pod_autoscaler(self,namespace,name)`

readthespecifiedHorizontalPodAutoscaler

--

`read_namespaced_ingress(self,namespace,name)`

readthespecifiedIngress

--

`read_namespaced_job(self,namespace,name)`

readthespecifiedJob

--

`read_namespaced_replica_set(self,namespace,name)`

readthespecifiedReplicaSet

--

`read_namespaced_scale_scale(self,namespace,name)`

readscaleofthespecifiedScale

--

`read_namespaced_scale_scale_9(self,namespace,name)`

readscaleofthespecifiedScale

--

`read_namespaced_scale_scale_10(self,namespace,name)`

readscaleofthespecifiedScale

--

`read_third_party_resource(self,name)`

readthespecifiedThirdPartyResource

--

`replace_namespaced_daemon_set(self,body,namespace,name)`

replacethespecifiedDaemonSet

--

`replace_namespaced_daemon_set_status(self,body,namespace,name)`

replacestatusofthespecifiedDaemonSet

--

`replace_namespaced_deployment(self,body,namespace,name)`

replacethespecifiedDeployment

--

`replace_namespaced_deployment_status(self,body,namespace,name)`

replacestatusofthespecifiedDeployment

--

`replace_namespaced_horizontal_pod_autoscaler(self,body,namespace,name)`

replacethespecifiedHorizontalPodAutoscaler

--

`replace_namespaced_horizontal_pod_autoscaler_status(self,body,namespace,name)`

replacestatusofthespecifiedHorizontalPodAutoscaler

--

`replace_namespaced_ingress(self,body,namespace,name)`

replacethespecifiedIngress

--

`replace_namespaced_ingress_status(self,body,namespace,name)`

replacestatusofthespecifiedIngress

--

`replace_namespaced_job(self,body,namespace,name)`

replacethespecifiedJob

--

`replace_namespaced_job_status(self,body,namespace,name)`

replacestatusofthespecifiedJob

--

`replace_namespaced_replica_set(self,body,namespace,name)`

replacethespecifiedReplicaSet

--

`replace_namespaced_replica_set_status(self,body,namespace,name)`

replacestatusofthespecifiedReplicaSet

--

`replace_namespaced_scale_scale(self,body,namespace,name)`

replacescaleofthespecifiedScale

--

`replace_namespaced_scale_scale_11(self,body,namespace,name)`

replacescaleofthespecifiedScale

--

`replace_namespaced_scale_scale_12(self,body,namespace,name)`

replacescaleofthespecifiedScale

--

`replace_third_party_resource(self,body,name)`

replacethespecifiedThirdPartyResource

--

`watch_namespaced_daemon_set(self,namespace,name)`

watchchangestoanobjectofkindDaemonSet

--

`watch_namespaced_daemon_set_list(self)`

watchindividualchangestoalistofDaemonSet

--

`watch_namespaced_daemon_set_list_13(self,namespace)`

watchindividualchangestoalistofDaemonSet

--

`watch_namespaced_deployment(self,namespace,name)`

watchchangestoanobjectofkindDeployment

--

`watch_namespaced_deployment_list(self)`

watchindividualchangestoalistofDeployment

--

`watch_namespaced_deployment_list_14(self,namespace)`

watchindividualchangestoalistofDeployment

--

`watch_namespaced_horizontal_pod_autoscaler(self,namespace,name)`

watchchangestoanobjectofkindHorizontalPodAutoscaler

--

`watch_namespaced_horizontal_pod_autoscaler_list(self)`

watchindividualchangestoalistofHorizontalPodAutoscaler

--

`watch_namespaced_horizontal_pod_autoscaler_list_15(self,namespace)`

watchindividualchangestoalistofHorizontalPodAutoscaler

--

`watch_namespaced_ingress(self,namespace,name)`

watchchangestoanobjectofkindIngress

--

`watch_namespaced_ingress_list(self)`

watchindividualchangestoalistofIngress

--

`watch_namespaced_ingress_list_16(self,namespace)`

watchindividualchangestoalistofIngress

--

`watch_namespaced_job(self,namespace,name)`

watchchangestoanobjectofkindJob

--

`watch_namespaced_job_list(self)`

watchindividualchangestoalistofJob

--

`watch_namespaced_job_list_17(self,namespace)`

watchindividualchangestoalistofJob

--

`watch_namespaced_replica_set(self,namespace,name)`

watchchangestoanobjectofkindReplicaSet

--

`watch_namespaced_replica_set_list(self,namespace)`

watchindividualchangestoalistofReplicaSet

--

`watch_namespaced_replica_set_list_18(self)`

watchindividualchangestoalistofReplicaSet

--

`watch_third_party_resource(self,name)`

watchchangestoanobjectofkindThirdPartyResource

--

`watch_third_party_resource_list(self)`

watchindividualchangestoalistofThirdPartyResource

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
