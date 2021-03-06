.. _installation-centos:

======================
Installation on CentOS
======================

CentOS 7
========

1.  Install the `EPEL repository <http://fedoraproject.org/wiki/EPEL>`_
    configuration using the RPM package linked to from the
    `epel-release repository view page <http://mirror.switch.ch/ftp/mirror/epel/beta/7/x86_64/repoview/epel-release.html>`_.

    .. parsed-literal::

        # :command:`rpm -Uhv http://url/to/epel-release.rpm`

2.  Install the Kolab Groupware repository configuration:

    .. parsed-literal::

        # :command:`cd /etc/yum.repos.d/`
        # :command:`wget http://obs.kolabsys.com/repositories/Kolab:/3.3/CentOS_7/Kolab:3.3.repo`
        # :command:`wget http://obs.kolabsys.com/repositories/Kolab:/3.3:/Updates/CentOS_7/Kolab:3.3:Updates.repo`

Next, continue with step #3 below.

CentOS 6
========

1.  Install the `EPEL repository <http://fedoraproject.org/wiki/EPEL>`_
    configuration using the RPM package linked to from the
    `epel-release repository view page <http://download.fedoraproject.org/pub/epel/6/i386/repoview/epel-release.html>`_.

    .. parsed-literal::

        # :command:`rpm -Uhv http://url/to/epel-release.rpm`

2.  Install the Kolab Groupware repository configuration:

    .. parsed-literal::

        # :command:`cd /etc/yum.repos.d/`
        # :command:`wget http://obs.kolabsys.com/repositories/Kolab:/3.3/CentOS_6/Kolab:3.3.repo`
        # :command:`wget http://obs.kolabsys.com/repositories/Kolab:/3.3:/Updates/CentOS_6/Kolab:3.3:Updates.repo`

Next, continue with step #3 below.

Both CentOS 6 and 7
===================

3.  Install Kolab Groupware:

    .. parsed-literal::

        # :command:`yum install kolab`

Continue to :ref:`install-setup-kolab`.
