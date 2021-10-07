## 04 – Basic AWS Infrastructure

Trainees will create and tie AWS resources: VPC, Security Group and Instance. You'll need to create a new git project called basic_aws_infra.

##### Instructions

1. Create file `main.tf` and include the following resources:
    - Provider
    - azurerm_network_security_group
    - azurerm_ssh_public_key
    - azurerm_image
    - azurerm_virtual_machine


2. In the same file include a public VPC with the following resources:
    - azurerm_virtual_network
    - azurerm_subnet
    - azurerm_route_table
    - azurerm_virtual_network_gateway
    - azurerm_subnet_route_table_association
    - azurerm_route

* Configure the resources using the following diagram: https://gitlab.com/dou-university/planning-committee/grad-program/-/blob/terraform/11%20-%20Terraform/04_basic_aws_infra_diagram.pdf


# Modules (Optional)
* After you created the resources and confirmed that everything is working fine in AWS, we are going to proceed moduling these resources. Proceed with the following:

3. Inside your main project directory, create `modules` directory. Inside `modules`, create directories:
    - ami
    - security
    - securitygroup
    - vpc


4. Move resources in the directories as the following:
    - `azurerm_image` resource in `image` directory
    - `azurerm_ssh_public_key` in `security`
    - `azurerm_network_security_group` in `securitygroup`
    - `azurerm_virtual_network`, `azurerm_subnet`, `azurerm_route_table`, `azurerm_virtual_network_gateway`, `azurerm_subnet_route_table_association` and `azurerm_route` in `vpc`
    - Keep the `Provider` and `azurerm_virtual_machine` in `main.tf` file


5. In main.tf call the modules and then insert the required values in the aws_instance. To call these values you'll need to use the outputs inside each modules directory


##### Expected deliverables 

You have to be able to reach the server in port 22 using the public IP assigned to the instance after launch, submit proof of functionality and terraform code.

#### Measuring instrument
| Metric  |  Description | Value  |
| ------------ | ------------ | ------------ |
|  Security group | azurerm_network_security_group was implemented  | 8%  |
|   SSH Public Key | azurerm_ssh_public_key was implemented  |  8% |
|  Image | azurerm_image   |  8% |
|  VPC | azurerm_virtual_network was implemented   |  8% |
|  Subnet | azurerm_subnet was implemented   |  8% |
|  Route table | aws_route_table was implemented   |  8% |
|  Internet gateway | azurerm_virtual_network_gateway was implemented   |  8% |
|  Route table association | azurerm_subnet_route_table_association was implemented   |  8% |
|  Route | azurerm_route was implemented   |  8% |
|  Functional | Provided scripts is fully functional   |  28% |


