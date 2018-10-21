# AWS-RStudio-Server-Setup
Instructions for Setting up RStudio Server on Amazon Web Services (AWS).

This document covers the use of Amazon Web Services (AWS), a scalable cloud computing service, for compiling code written in
R by utilising a Linux based RStudio server. The instructions primarily focus on the following three topics; AWS account setup,
RStudio server installation and RStudio GUI usage. This is a comprehensive guide, complete with screenshots, so the length of
this document is misleading to the complexity of the entire process which can be completed in less than twenty minutes.

## Contents
#1     Introduction                                    3
1.1   What is Amazon Web Services?                    3
1.2   What is RStudio Server?                         3

#2     AWS Account Creation                            4
#3     AWS Account Login                               7
#4     AWS RStudio Server Setup                        8

#5     Accessing AWS Instance Via SSH                  14
5.1   Installing PuTTY                                14
5.2   PuTTYgen Key Conversion                         15
5.3   Connecting via SSH                              17
5.4   Changing RStudio GUI User Password              18
5.5   Adding Users                                    19

#6     Using RStudio Server Graphical User Interface   21

#7     Uploading Files via FTP                         23
7.1   Installing FileZilla Client                     23
7.2   Changing Folder Permissions Via SSH             24
7.3   Connecting to AWS Instance Via FTP              25
7.4   Adding Files for Use in R                       27
