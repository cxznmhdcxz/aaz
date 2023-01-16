# [Command] _network express-route port identity remove_

Remove the managed service identity of an ExpressRoute Port.

## Versions

### [2022-01-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXR3b3JrL2V4cHJlc3Nyb3V0ZXBvcnRzL3t9/2022-01-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.network/expressrouteports/{} 2022-01-01 identity -->

#### examples

- Remove an identity of the ExpressRoute Port
    ```bash
        network express-route port identity remove -g MyResourceGroup --name MyExpressRoutePort
    ```