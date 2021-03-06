.. Copyright 2010-2017 Amazon.com, Inc. or its affiliates. All Rights Reserved.

   This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0
   International License (the "License"). You may not use this file except in compliance with the
   License. A copy of the License is located at http://creativecommons.org/licenses/by-nc-sa/4.0/.

   This file is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND,
   either express or implied. See the License for the specific language governing permissions and
   limitations under the License.

.. _ec2-apis-intro:

##################################
Deploying Applications Using |EC2|
##################################

.. meta::
   :description:
   :keywords: AWS SDK for .NET code examples

The |sdk-net| supports |EC2|, which is a web service that provides resizable computing
capacity |mdash| literally, servers in Amazon's data centers |mdash| that you use to build and host
your software systems. The |EC2| APIs are provided by the `AWSSDK.EC2 <http://www.nuget.org/packages/AWSSDK.EC2>`_ assembly.

The :doc:`Amazon EC2 instances examples <how-to-ec2>` are intended to help you get started
with |EC2|.

The :doc:`Amazon EC2 Spot instances examples <how-to-spot-instances>` show you how to use Spot instances,
which enable you to bid on unused |EC2| capacity and run any instances that you acquire for as
long as your bid exceeds the current Spot price. |EC2| changes the Spot price periodically
based on supply and demand; customers whose bids meet or exceed it gain access to the available
Spot instances. For more information, see :ec2-ug:`Spot Instances <using-spot-instances>` in the |EC2-ug|
and :ec2-ug-win:`Spot Instances <using-spot-instances>` in the |EC2-ug-win|.

.. toctree::
    :titlesonly:
    :maxdepth: 1

    how-to/ec2/how-to-ec2
    how-to/ec2/how-to-spot-instances



