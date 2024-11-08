# Tridentctl-protect

tridentctl plugin for NetApp Trident protect



NetApp Trident protect provides advanced application data management capabilities that enhance the functionality and availability of stateful Kubernetes applications backed by NetApp ONTAP storage systems and the NetApp Trident CSI storage provisioner. Trident protect simplifies the management, protection, and movement of containerized workloads across public clouds and on-premises environments.



To install this plugin, download `tridentctl-protect` binary from the release section, make it executable and copy it into a folder in your PATH. For details see documentation https://docs.netapp.com/us-en/trident/trident-protect/trident-protect-cli.html







```bash

> tridentctl protect --help

CLI for Trident Protect, a Kubernetes application data lifecycle management solution



Usage:

  tridentctl protect [command]



Available Commands:

  completion  Generate the autocompletion script for the specified shell

  create      Create Trident-Protect Resources

  delete      Delete a resource

  get         get or list resources

  help        Help about any command

  patch       Patch Trident-Protect Resources

  version     Show the version number

  wait        Wait for a resource to be in a final state, e.g. Ready, Complete, Available, Failed or Removed