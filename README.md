[![Deploy](https://cdn.wedeploy.com/images/deploy.svg)](https://console.wedeploy.com/deploy?repo=https://github.com/vishal-reddy/zeppelin-example)

# Apache Zeppelin

An example of [Zeppelin](https://hub.docker.com/r/apache/zeppelin/). The project can provide a notebook environment to interact with your WeDeploy Data Service via the Android SDK. Add the following dependencies to your Spark interpreter to interface with a WeDeploy Data Service:

```
com.wedeploy:com.wedeploy.android:1.0.0
com.netflix.feign:feign-okhttp:8.14.1
org.json:json:20180130
io.reactivex.rxjava2:rxjava:2.1.9
```

## Instructions

1. Install the [WeDeploy CLI](https://wedeploy.com/docs/intro/using-the-command-line/).
2. Clone this repository.
3. Open the project with your command line and run `we deploy -p yourproject`.

## License

[BSD-3-Clause](./LICENSE.md), © Liferay, Inc.
