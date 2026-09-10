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








   
