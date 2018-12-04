# godb
Working with databases module for go
## Branch roles
At least 5 roles  
* master: production releases
* develop: integration
* release-*.*: for finalizing a major/minor release, branched from develop
* hotfix-*.*: for applying patches, branched from master (or support-* for older releases)
* feature-*.*: for developing features or wild speculation, branched from develop
See more at: [!https://gist.github.com/stuartsaunders/448036/5ae4e961f02e441e98528927d071f51bf082662f]