History
=======

0.8.0-tc
-----

* BaseMmStats no longer extends threading.local when used with
gevent thread local patching, which caused a file descriptor leak
