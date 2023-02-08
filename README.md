# ALOps-External-Deployer
Enables external deployment in Microsoft Business Central (API Deploy)

## Install
To install and import the powershell library run following

```
install-module ALOps.ExternalDeployer -Force
import-module ALOps.ExternalDeployer 
```

Currently (2023-01-29) this gives the following output
```
Use [Install-ALOpsExternalDeployer] to install [ALOps External Deployer] service with default.
 * When installing within a Docker-Container, the default installation can be done.

 * If the BC ServerInstance is not 'BC', you can specify the correct instance
   - Install-ALOpsExternalDeployer -ServerInstance BC200

 * When installing for multiple ServerInstances, specify a different port for each instance:
   - Install-ALOpsExternalDeployer -ServerInstance BC200 -ListenPort 7000
   - Install-ALOpsExternalDeployer -ServerInstance BC210 -ListenPort 7001
```

More information can be found at the powershell gallery
https://www.powershellgallery.com/packages/ALOps.ExternalDeployer

## Resources

**Waldos announcement of ALOps-External-Deployer**

Part 1: 
Deploying from DevOps the right way: enabling External Deployment in OnPrem Business Central environments
https://www.waldo.be/2020/06/15/deploying-from-devops-the-right-way-enabling-external-deployment-in-onprem-business-central-environments/

Part 2: 
Deploying from DevOps the right way (Part 2): Deploying to OnPrem Business Central environments with the automation API
https://www.waldo.be/2020/06/30/deploying-from-devops-the-right-way-part-2-deploying-to-onprem-business-central-environments-with-the-automation-api/

**Troubleshooting**

Following links has solved issues and current issues 

ALOps-External-Deployer/issues: https://github.com/HodorNV/ALOps-External-Deployer/issues

ALOps issue page: https://github.com/HodorNV/ALOps/issues?q=ALOps-External-Deployer