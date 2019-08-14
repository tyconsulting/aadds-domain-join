# Azure AD DS Domain Join Sample ARM Template

# Instruction
``` PowerShell
New-AzResourceGroupDeployment -Name DeployDomJoinVMExtension -ResourceGroupName <vm-rg-name> -Mode Incremental -TemplateFile .\vm.domain-join-azuredeploy.json -TemplateParameterFile .\parameters\lab\vm.domain-join-azuredeploy.parameters.inf.1.json -vmList '<vm-names>' -location '<vm-location>' -Verbose
```