# File_Convert_using_RPS<br />
**Created Date:** 1/12/2004<br />
**Last Updated:** 10/15/2010<br />
**Description:** Convert a file from format A to format B, using the Synergy/DE Repository. (Update for Synergy 9.5 compatibility)<br />
**Platforms:** Windows; Unix; OpenVMS<br />
**Products:** Repository<br />
**Minimum Version:** 7.1<br />
**Author:** William Hawkins
<hr>

**Additional Information:**
The formats can either be two different files
in the same Repository, or files in different Repository's.

This program uses the ISMKEY routines, also available from the Synergy/DE
CodeExchange.

Uses the logical INC: to point to the include file directories.

Uses UTILITIES.ZIP and ISMKEY.ZIP

Compiler command: DBL iconvert
Link command DBLINK iconvert WND:tklib.elb, RPSLIB:ddlib.elb
