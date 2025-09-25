---
title: Update Server Artifact
---

# Updating Your FiveM Server Artifact

Keeping your server artifact up-to-date ensures compatibility with the FiveM platform, prevents crashes, and provides access to the latest features.

---

## Windows

1. Download the latest Windows artifact from the official repository [Windows Server Artifacts](https://runtime.fivem.net/artifacts/fivem/build_server_windows/master/).

2. Extract the contents of the downloaded `.zip` file to a temporary folder.

3. Update your server files:
   - Replace the existing artifact files with the new ones, **or**
   - Delete the old files and copy the new ones into your server directory.
   *(Make sure not to remove your `server.cfg` or resource folders.)*

4. Restart your server to apply the update.

## Linux

The update process on Linux is essentially the same as on Windows. Download the latest artifact, extract it, replace the old files, and restart your server.

You can find the latest [Linux Server Artifacts here](https://runtime.fivem.net/artifacts/fivem/build_proot_linux/master/)é

*(As with Windows, do not overwrite your `server.cfg` or resource folders when updating.)*

---
## Verify the Update

After updating, confirm that your server is running the new artifact version.

1. Start your server.
2. In the server console, run the command `version`. This will display the currently running artifact build number.
3. Compare the build number with the one from the official artifacts repository download.

{{% alert title="Tip" theme="success" %}}
If the number in your console matches, your update was successful.
{{% /alert %}}

---
## Server artifact version is outdated

If players encounter the following error messages when trying to join your server:

* **Server artifact version is outdated**
* **End of Support (EOS)**
* **End of Life (EOL)**

It means your server is running an unsupported artifact version.

{{% alert title="Fix" theme="danger" %}}
Update to the latest server artifact by following the steps above.
{{% /alert %}}

For more details and troubleshooting, see the official support article:
[Server artifact version is outdated or End of Support / End of Life error messages](https://support.cfx.re/hc/en-us/articles/12242287993500-Server-artifact-version-is-outdated-or-End-of-Support-End-of-Life-error-messages-when-trying-to-join-a-server)

---
## Custom Artifact Builds

It is possible to use a custom artifact build for your server. However, this is **not recommended** as it may introduce instability, compatibility issues, or unexpected crashes.

{{% alert title="Important" theme="warning" %}}No official support will be provided for servers running custom artifact builds. For best performance and stability, always use the **latest official release**.{{% /alert %}}
