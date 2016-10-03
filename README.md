# Confguring One Way Trust Between MIT KDC and AD
Many security environments have strict policies on allowing administrative access to Active Directory. Some performance issues can also require that Hadoop cluster principals for Kerberos are not created directly in AD. To aid in these situations, it may be preferable to use a local MIT KDC in the Hadoop cluster to manage service principals while using a one-way trust to allow AD users to utilze the Hadoop environment. This tutorial describes the steps necessary to create such a trust.


