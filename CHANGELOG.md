## Changelog

### 2.73.3-5 (Not released yet)

* Added [anchore-container-scanner:1.0.11 plugin](https://wiki.jenkins.io/display/JENKINS/Anchore+Container+Image+Scanner+Plugin)
* Updated plugins:
    * blueocean-autofavorite:1.1.0
    * checkmarx:8.42.0
    * display-url-api:2.1.0
    * durable-task:1.16
    * gitlab-plugin:1.5.1
    * junit:1.22.2
    * lockable-resources:1.11.2
    * p4:1.8.1
    * pipeline-model-api:1.2.4
    * pipeline-model-definition:1.2.4
    * pipeline-model-extensions:1.2.4
    * pipeline-stage-tags-metadata:1.2.4
    * script-security:1.35
    * workflow-cps:2.41
    * workflow-step-api:2.13



### 2.73.3-4
* Generalize S3 Watch to be able to watch other sources [#51](https://github.com/odavid/my-bloody-jenkins/issues/51)
    * **NOTE:** The Following variables were renamed:
        * JENKINS_ENV_CONFIG_YML_S3_URL --> JENKINS_ENV_CONFIG_YML_URL
        * JENKINS_ENV_CONFIG_YML_S3_DISABLE_WATCH --> JENKINS_ENV_CONFIG_YML_URL_DISABLE_WATCH
        * JENKINS_ENV_CONFIG_YML_S3_POLLING --> JENKINS_ENV_CONFIG_YML_URL_POLLING

### 2.73.3-3
* add jenkins environment variables section [#45](https://github.com/odavid/my-bloody-jenkins/issues/45)
* Don't create docker group if GID already exist on start [#46](https://github.com/odavid/my-bloody-jenkins/issues/46)

### 2.73.3-2

* Docker cloud: multiple volumes are not working [#44](https://github.com/odavid/my-bloody-jenkins/issues/44)
* Add proxy configuration when Jenkins is running behind a proxy server [#41](https://github.com/odavid/my-bloody-jenkins/issues/41)


### 2.73.3-1

* First release, based on LTS 2.73.3