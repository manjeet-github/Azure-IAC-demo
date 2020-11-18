# Provision resources in Azure
# IAC for standing the resources to run an instance.
=======
Terraform code for provisioning the resources
- Azure Resource Group
- VNET resource
- Subnet Resource
- Network Security Group
- Public IP Resource for NIC
- Network Interface Resource
- Virtual Machine Instance



resource "azurerm_resource_group" "rg" {
resource "azurerm_virtual_network" "vnet" {
resource "azurerm_subnet" "subnet" {
resource "azurerm_public_ip" "publicip" {
resource "azurerm_network_security_group" "nsg" {
resource "azurerm_network_interface" "nic" {
resource "azurerm_virtual_machine" "vm" {

