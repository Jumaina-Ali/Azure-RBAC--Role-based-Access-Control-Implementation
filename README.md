# Azure-RBAC--Role-based-Access-Control-Implementation
# PROJECT OVERVIEW -                                                                                         ## Implemented Azure Role-based Access control (RBAC) to manage access to azure resources using the principle of least privilege. 
# PROJECT SCENARIO -                                                                                        ## ABC business needs to control access to its Azure resources based on user responsibilities.
# AZURE RESOURCES                                                                                            ## Resource  group :RG-ABC-Production                                                                        ## Storage Account : stabcproduction01                                                                       ## Blob Container : rbac-test
# RBAC Roles Implemented -                                                                                   ## ROLE                              SCOPE                                    PURPOSE                       Owner                             Subscription                             Full access                     Contributor                       Resource Group                           Manage Azure Resources          Reader                            Storage Account                          View Resources                  Storage blob data                 Storage Account                          Read , write and delete blob   Contributer                                                                data
# RBAC Scope Hierarchy -                                                                                      Subscription 
##            └── RG-ABC-Production 
##                    └── stabcproduction01  
##                                     └── rbac-test 
##                                              └── Test File
# IMPLEMENTATION STEPS                                                                                     ## Created the RG-ABC-Production resource group.                                                           ## Created the stabcproduction01 storage account.                                                          ## Configured RBAC through Access control (IAM).                                                           ## Assigned the Reader role at the Storage Account scope.                                                  ## Assigned Storage Blob Data Contributor for Blob data access.                                            ## Used Check access to verify effective permissions.                                                      ## Removed the test Reader assignment to demonstrate access revocation.                                    ## Downloaded the Role Assignments report for documentation. 
# KEY CONCEPTS LEARNED -                                                                                   ## Azure RBAC                                                                                            ## Role assignments                                                                                        ## Management-plane vs data-plane access                                                                   ## RBAC scopes                                                                                             ## Scope inheritance                                                                                       ## Least-privilege access                                                                                  ## Access verification                                                                                     ## Access removal 
# SCREENSHOTS - 
## Resource group - <img width="1351" height="620" alt="Screenshot (64)" src="https://github.com/user-attachments/assets/3072f044-7e29-4478-b63c-dab3351b270c" />
## Storage Account - <img width="1356" height="623" alt="Screenshot (65)" src="https://github.com/user-attachments/assets/b3aa466e-2cc1-4895-86ff-e03000034e43" />
## IAM Role Assignments - <img width="1350" height="621" alt="Screenshot (60)" src="https://github.com/user-attachments/assets/6d367beb-8a05-4306-8631-161629f675ab" /> 
## Check Access - <img width="1350" height="621" alt="Screenshot (60)" src="https://github.com/user-attachments/assets/e41cd6a6-8539-41e6-a593-1f03a13d4a8c" />











   
