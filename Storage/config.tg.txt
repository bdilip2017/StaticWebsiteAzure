terraform {
  required_providers {
    azurerm = {
      source  = "hashicorp/azurerm"
      version = "~>2.0" # The version of the provider will use the last version of v2 available at time 
    }
  }
  backend "azurerm" { }
}
