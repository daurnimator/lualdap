# LuaLDAP

[![CircleCI](https://circleci.com/gh/lualdap/lualdap.svg?style=shield)](https://circleci.com/gh/lualdap/lualdap)
[![Build Status](https://travis-ci.org/lualdap/lualdap.svg?branch=master)](https://travis-ci.org/lualdap/lualdap)
[![codecov](https://codecov.io/gh/lualdap/lualdap/branch/master/graph/badge.svg)](https://codecov.io/gh/lualdap/lualdap)

LuaLDAP is a simple interface from Lua to an LDAP client, in fact it is a bind to
OpenLDAP or to ADSI. It enables a Lua program to:

    * Connect to an LDAP server;
    * Execute any operation (search, add, compare, delete, modify and rename);
    * Retrieve entries and references of the search result.

# License

LuaLDAP is free software and uses the same license as Lua 5.1.

# Dependencies

Current version is 1.2.2. It was developed for both Lua 5.1 and Lua 5.2,
and both OpenLDAP 2.1 or newer and ADSI.

Files in the distribution:

    /doc/us/*.html  -- Documentation
	/src/*			-- Source files
	/tests/*        -- Test files
	/vc6/*          -- Build files for MS Visual C 6 (deprecated)
    /rockspecs/         -- luarocks build system releases
    Makefile        -- Makefile for Unix systems (deprecated)
    config          -- Configurations to build on Unix systems (deprecated)
    Makefile.win    -- Makefile for Windows systens with MS Visual C 8
    config.win      -- Configurations to build on Windows systems
    README.md       -- This file
    CONTRIBUTORS.md -- Who contributed what
    LICENSE.md      -- MIT License reference

Please see CONTRIBUTORS for contribution information and documentation on original source
