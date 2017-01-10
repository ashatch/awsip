# awsip
Find ip addresses of AWS resources

# Usage

    Usage:
       awsip cf [options...] <stack name>
       awsip cfasg [options...] <stack name>
    Options:
       -h --help        Show this usage information
       -v --version     Report the current version
       -n --name        Specific EC2 Resource name
          --prefix      Prefix for resource names, e.g. ClusterBox
       -p --profile     AWS profile (default default)
       -l --list        Output as comma separated list

# Examples

Finding ips for an instance resource a particular name

    awsip cf --name LoadTester my-stack

Finding ips for instances with a resource name of a particular prefix:

    awsip cf --prefix ClusterNode my-stack

Finding ips for a cloudformed ASG

     awsip cfasg --name ClusterGroup my-stack

# Installation

Install via brew.

    brew tap ashatch/homebrew-repo
    brew install awsip
