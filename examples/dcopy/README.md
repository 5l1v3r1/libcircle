dcopy (distributed copy)
========================

WARNING: dcopy is NOT production quality. It WILL randomly delete files and
hurt small adorable animals (only cute ones!). Please only execute it on
systems that you don't care about or you'll regret it!

The purpose of dcopy is to perform a large number of file copy operations (such
as a directory tree with billions of files) across many different nodes in a
cluster. Using a filesystem that benefits from heavy parallel reads and writes
is recommended.
