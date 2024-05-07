# tfot-depup

TerraForm OpenTofu Dependency Updater

Creating this as I've noticed, over time, if using pinned versions of TF/OT
providers and modules, projects can quickly fall-behind. I've rarely
noticed impact when updating providers, somewhat more so modules, so the aim
of this project is to check for updates to providers/modules, run init/validate
steps to check for any changes, and open an MR if the test passes.

I plan on creating native GitHub Action Workflows, GitLab CI/CD components, and
plain docker/binaries. 

This will be my first public GO project so MRs and suggestions accepted.

Not affiliated with OpenTofu or HashiCorp/Terraform.