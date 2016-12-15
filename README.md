# awsip
Find ip addresses of AWS resources

# Usage

    Usage:
       awsip cf [options...] <stack name>
    Options:
       -h --help        Show this usage information
       -v --version     Report the current version
       -n --name        Specific EC2 Resource name
          --prefix      Prefix for resource names, e.g. ClusterBox
       -p --profile     AWS profile (default default)

# Installation

Install via brew.

    brew tap ashatch/homebrew-repo
    brew install awsip
