# [Command] _datadog monitor delete_

Deletes an existing Datadog monitor resource from your Azure subscription, removing the integration and stopping the observability of your Azure resources through Datadog.

## Versions

### [2021-03-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kYXRhZG9nL21vbml0b3JzL3t9/2021-03-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.datadog/monitors/{} 2021-03-01 -->

#### examples

- Monitors_Delete
    ```bash
        datadog monitor delete --resource-group myResourceGroup --monitor-name myMonitor
    ```
