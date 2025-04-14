# CBT149
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 149 CONTAINS SEVERAL UTILITIES FROM UCLA.  THIS FILE IS   *   FILE 149
//*           IN IEBUPDTE SYSIN FORMAT - SEE THE MEMBER CALLED      *   FILE 149
//*           $$DOC FOR ADDITIONAL INFORMATION. THE FOLLOWING IS    *   FILE 149
//*           A BRIEF DESCRIPTION OF UTILITIES IN THIS FILE :       *   FILE 149
//*                                                                 *   FILE 149
//*         CCNEDFSE/CCNEDFSH - FULL SCREEN TSO EDIT SUBCOMMAND     *   FILE 149
//*              FOR 3270'S.  THIS INCLUDES MOVE/COPY/DELETE        *   FILE 149
//*              COMMANDS WHICH ALLOW LINE NUMBERS ON UNNUMBERED    *   FILE 149
//*              FILES.  REQUIRES ZAP TO IKJEBEMA TO ADD TO EDIT    *   FILE 149
//*              COMMAND TABLE.  (SEE INFO  CNEDFSE)                *   FILE 149
//*                                                                 *   FILE 149
//*         CMSLOAD  - LOAD "DISK DUMP" FILE FROM VM.               *   FILE 149
//*                                                                 *   FILE 149
//*         COMPARE  - LOAD MODULE / CSECT COMPARE PROGRAM.         *   FILE 149
//*                    *** REQUIRED ***                             *   FILE 149
//*                                                                 *   FILE 149
//*         COMPLOAD - LOAD MODULE / CSECT COMPARE PROGRAM.         *   FILE 149
//*                    *** REQUIRED ***                             *   FILE 149
//*                    Renamed to make its function clearer.        *   FILE 149
//*                    Same as COMPARE program, except that         *   FILE 149
//*                    printable bytes are displayed in EBCDIC,     *   FILE 149
//*                    next to the HEX bytes.                       *   FILE 149
//*                                                                 *   FILE 149
//*         DUMPINFO - TSO CP TO DISPLAY SYS1.DUMP DATASET          *   FILE 149
//*                    STATUS.  INCLUDES TITLE, DATE AND TIMES.     *   FILE 149
//*                                                                 *   FILE 149
//*         ENQ      - SP 1.3 ENQ DISPLAY TSO CP                    *   FILE 149
//*                                                                 *   FILE 149
//*         ESDXREF  - LOAD MODULE / CSECT XREF PGM                 *   FILE 149
//*                                                                 *   FILE 149
//*         IEAVNP99 - SAMPLE USER NIP EXIT ROUTINE.                *   FILE 149
//*                    SEE   EAVNP99 FOR SAMPLE SMP INSTALL.        *   FILE 149
//*                                                                 *   FILE 149
//*         IEFU83   - SMF 83 EXIT WITH CODE TO WTO OLD IEC209I     *   FILE 149
//*                    TAPE STATISTICS MESSAGE.  (THE REST OF THE   *   FILE 149
//*                    LOCAL CODE SHOULD BE DELETED).               *   FILE 149
//*                                                                 *   FILE 149
//*         IXTOFMT5 - SUBROUTINE USED TO UPGRADE PGMS TO WORK      *   FILE 149
//*                    ON INDEXED VTOC'S.  RETURNS "FAKE" FMT5'S    *   FILE 149
//*                    FOR INDEXED PACKS.  (USED BY LISTSPC AND     *   FILE 149
//*                    VTOCLIST)                                    *   FILE 149
//*                                                                 *   FILE 149
//*         JOIN     - VERY SIMPLE & POWERFUL GENERAL MATCH MERGE   *   FILE 149
//*                    PGM.                                         *   FILE 149
//*                                                                 *   FILE 149
//*         LISTGRP  - LISTS UNITS IN GENERICS, OR ESOTERICS.       *   FILE 149
//*                                                                 *   FILE 149
//*         LISTSPC  - OLD LISTSPC CP FROM CBT TAPE UPDATED FOR     *   FILE 149
//*                    INDEXED VTOCS.  (USES IXTOFMT5               *   FILE 149
//*                    SUBROUTINE).                                 *   FILE 149
//*                                                                 *   FILE 149
//*         MOVEZAP  - ZAPS TO (COPY) OF IEHMOVE TO ALLOW           *   FILE 149
//*                    RUNNING FASTER & NON-AUTHORIZED.             *   FILE 149
//*                                                                 *   FILE 149
//*         OACFSORT - ASM SUBROUTINE TO DO FIXED LENGTH            *   FILE 149
//*                    QUICKSORTS.  (FINAL ORDER CHECK COULD BE     *   FILE 149
//*                    REMOVED FOR HIGH USAGE CASES)                *   FILE 149
//*                                                                 *   FILE 149
//*         OACMOVE  - IEHMOVE PRELOAD PGM. (SEE ALSO MOVEZAP)      *   FILE 149
//*                                                                 *   FILE 149
//*         OACNSWAP - PGM TO RUN PROBLEM PROGRAMS NON-SWAPPABLE    *   FILE 149
//*                    WITH ONLY ONE PPT ENTRY.  PGM IS NOT APF     *   FILE 149
//*                    AUTHORIZED.  (SEE  ACNSWAP FOR PPT ENTRY     *   FILE 149
//*                    INFO).                                       *   FILE 149
//*                                                                 *   FILE 149
//*         PTFXREF  - PE CHAIN RUNNER (PLIX).                      *   FILE 149
//*                                                                 *   FILE 149
//*         SALVAGE  - HDA / PACK CLEAN UP PGM (& CP).              *   FILE 149
//*                                                                 *   FILE 149
//*         SMPULCMP - SMP LMOD ENTRY (FROM SMP UNLOAD) COMPARE.    *   FILE 149
//*                    USED IN SP 1.0 TO SP 1.3 CONVERSION (AND     *   FILE 149
//*                    OTHER TIMES). (PLIX)                         *   FILE 149
//*                                                                 *   FILE 149
//*         UNIQUE   - VERY SIMPLE PGM TO SELECT ONE OF THINGS.     *   FILE 149
//*                    (SEE ALSO JOIN)                              *   FILE 149
//*                                                                 *   FILE 149
//*         USERS    - TSO USERS CP (SELECTS USERS WITH WILDCARDS). *   FILE 149
//*                                                                 *   FILE 149
//*         VTOCLIST - OLD VTOCLIST PGM UPDATE TO WORK ON           *   FILE 149
//*                    INDEXED VTOCS.  (USES IXTOFMT5 SUBROUTINE)   *   FILE 149
//*                                                                 *   FILE 149
```
