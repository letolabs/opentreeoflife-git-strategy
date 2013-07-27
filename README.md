# Open Tree Of Life: Git Strategy

This is a strategic document which describes how the Open Tree Of Life currently uses Git, current pain
points and a transition plan to a future where OTOL leverages as many of Git's features as possible,
for code, data, configuration files of servers and various other uses.

# Current Infrastructure

Github, Bitbucket, NCBI, GBIF, S3, EC2, Linode, etc...

## High Level Overview

Input taxonomies come in from [NCBI](https://www.nescent.org/wg_evoinfo/NCBI_Taxonomy_Information), GBIF and the "patch system". These are synthesized by X, then processed by Y and
then are accessible via the Argus browser and the Treemachine API.

The [NCBI FTP server](ftp://ftp.ncbi.nih.gov/pub/taxonomy/) seems to be updated daily with the latest dumps.

NCBI currently has [http://www.ncbi.nlm.nih.gov/Taxonomy/taxonomyhome.html/index.cgi?chapter=STATISTICS&uncultured=hide&unspecified=hide](387,000) nodes in their taxonomy tree.

# Author(s)

Jonathan "Duke" Leto, Leto Labs LLC

# License

GPLv3. See LICENSE file for details. If you would like to use this content under a different license, please feel
free to contact duke@leto.net. I don't bite.

