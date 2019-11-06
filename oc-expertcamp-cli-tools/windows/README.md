# OpenShift Clients

The OpenShift client `oc.exe` simplifies working with Kubernetes and OpenShift
clusters, offering a number of advantages over `kubectl.exe` such as easy login,
kube config file management, and access to developer tools.

To learn more about OpenShift, visit [docs.openshift.com](https://docs.openshift.com)
and select the version of OpenShift you are using.

## Installing the tools

After extracting this archive, move the `oc.exe` binary	to a location on your
PATH. Then run:

    oc login [API_URL]

to start a session against an OpenShift cluster. After login, run `oc.exe` and
`oc.exe help` to learn more about how to get started with OpenShift.

If you would like to use `kubectl.exe` instead, copy the `oc.exe` file
and rename it to `kubectl.exe`. The interface will follow the conventions of that
CLI.

## License

OpenShift is licensed under the Apache Public License 2.0. The source code for this
program is [located on github](https://github.com/openshift/origin).
