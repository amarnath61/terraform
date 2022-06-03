# Terraform
This repository is for Terraform Learning.
<h1>Terraform:</h1>
Terraform is an open source infrastructure as code tool created by HashiCorp. It is written in Go Language and first released in 2014. It offers HCL (HashiCorp Configuration Language) to implement simple and clean syntax. You can provision whole infrastructure with the help of Terraform including storage, networking, computing and many more...

* Terraform supports a number of Cloud infrastructure provider such as Amazon Web Services, Microsoft Azure, Google Cloud Platform, Oracle cloud, Open stack, Digital Ocean, VMware vSphere.....any more more... 

* Terraform is a tool for building , changing and versioning infrasctucture safely and efficiently
<h2> Terraform common command: </h2> 
	$ terraform init  ==> repare your working directory for other command <br />
	$ terraform plan ==> Show changes required by the current configuration <br />
	$ terraform apply  ==> Create or update infrastructure <br />
  $ terraform destroy  ==> Destroy previously-created infrastructure <br />
<h2> terraform --help </h2>
		Usage: terraform [global options] <subcommand> [args]
	
	The available commands for execution are listed below.
	The primary workflow commands are given first, followed by
	less common or more advanced commands.
	
	Main commands:
	  init          Prepare your working directory for other commands
	  validate      Check whether the configuration is valid
	  plan          Show changes required by the current configuration
	  apply         Create or update infrastructure
	  destroy       Destroy previously-created infrastructure
	
	All other commands:
	  console       Try Terraform expressions at an interactive command prompt
	  fmt           Reformat your configuration in the standard style
	  force-unlock  Release a stuck lock on the current workspace
	  get           Install or upgrade remote Terraform modules
	  graph         Generate a Graphviz graph of the steps in an operation
	  import        Associate existing infrastructure with a Terraform resource
	  login         Obtain and save credentials for a remote host
	  logout        Remove locally-stored credentials for a remote host
	  output        Show output values from your root module
	  providers     Show the providers required for this configuration
	  refresh       Update the state to match remote systems
	  show          Show the current state or a saved plan
	  state         Advanced state management
	  taint         Mark a resource instance as not fully functional
	  test          Experimental support for module integration testing
	  untaint       Remove the 'tainted' state from a resource instance
	  version       Show the current Terraform version
	  workspace     Workspace management
	
	Global options (use these before the subcommand, if any):
	  -chdir=DIR    Switch to a different working directory before executing the
	                given subcommand.
	  -help         Show this help output, or the help for a specified subcommand.
	  -version      An alias for the "version" subcommand.
