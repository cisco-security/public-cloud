################################################################################
#                                                                                                                                                            #
# Copyright (c) 2017 Cisco Systems                                                                                                      #
# All Rights Reserved.                                                                                                                            #
#                                                                                                                                                            #
#    Licensed under the Apache License, Version 2.0 (the "License"); you may                                       #
#    not use this file except in compliance with the License. You may obtain                                        #
#    a copy of the License at                                                                                                                   #
#                                                                                                                                                            #
#         http://www.apache.org/licenses/LICENSE-2.0                                                                          #
#                                                                                                                                                            #
#    Unless required by applicable law or agreed to in writing, software                                                #
#    distributed under the License is distributed on an "AS IS" BASIS, WITHOUT                                    #
#    WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the                            #
#    License for the specific language governing permissions and limitations                                      #
#    under the License.                                                                                                                           #
#                                                                                                                                                            #
################################################################################

Cisco ASAv template deployment in Microsoft Azure Public Cloud
=========================================

Following JSON template is posted here on GitHub as an example of how to deploy ASAv into existing Availability Set.
Currently, Azure console allows you to deploy ASAv only into a new Availability set.  Published template also allows for
quicker workflow, scripted deployment, and ability to deploy multiple ASAv into the same availability set.  Multiple
ASAv devices in the same availability set allow for load-balancing to these firewalls and ability to offer stateless HA.

Following JSON template is posted to GitHub:

https://github.com/cisco-security/public-cloud/tree/master/asav-in-azure

Video instructions on how to use this template is posted on YouTube:

Cisco ASAv Template Deployment in Azure:

https://youtu.be/fKWB8gUgnZc




