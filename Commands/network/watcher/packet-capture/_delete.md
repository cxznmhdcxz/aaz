# [Command] _network watcher packet-capture delete_

Delete a packet capture session.

## Versions

### [2022-01-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXR3b3JrL25ldHdvcmt3YXRjaGVycy97fS9wYWNrZXRjYXB0dXJlcy97fQ==/2022-01-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.network/networkwatchers/{}/packetcaptures/{} 2022-01-01 -->

#### examples

- Delete a packet capture session. This only deletes the session and not the capture file.
    ```bash
        network watcher packet-capture delete -n packetCaptureName -l westcentralus
    ```
