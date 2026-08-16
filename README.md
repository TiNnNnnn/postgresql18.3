PostgreSQL Database Management System
=====================================

This directory contains the source code distribution of the PostgreSQL
database management system.

PostgreSQL is an advanced object-relational database management system
that supports an extended subset of the SQL standard, including
transactions, foreign keys, subqueries, triggers, user-defined types
and functions.  This distribution also contains C language bindings.

Copyright and license information can be found in the file COPYRIGHT.

General documentation about this version of PostgreSQL can be found at
<https://www.postgresql.org/docs/18/>.  In particular, information
about building PostgreSQL from the source code can be found at
<https://www.postgresql.org/docs/18/installation.html>.

The latest version of this software, and related software, may be
obtained at <https://www.postgresql.org/download/>.  For more information
look at our web site located at <https://www.postgresql.org/>.

# Building PostgreSQL

To build PostgreSQL from source, follow these steps:

1. **Featch Submoudle**: `git submodule update --init --recursive`
2. **Configure**: Run `./configure --prefix ${your install path} --enable-debug` to prepare the build environment.
3. **Compile**: Execute `make -j${number of cores}` to compile the source code.
4. **Install**: Use `sudo make install` to install PostgreSQL on your system.

For detailed instructions, refer to the [installation documentation](https://www.postgresql.org/docs/18/installation.html).
