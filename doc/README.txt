From - Mon Feb  7 17:50:06 2000
Received: from FNAL.FNAL.Gov by sdss.fnal.gov via ESMTP (951211.SGI.8.6.12.PATCH1502/951211.SGI)
	for <dtucker@sdss.fnal.gov> id RAA03156; Wed, 5 May 1999 17:00:59 -0500
Received: from proxima.as.arizona.edu ("port 33291"@proxima.as.arizona.edu)
 by FNAL.FNAL.GOV (PMDF V5.1-12 #3998)
 with ESMTP id <01JAUGBN351S00038Z@FNAL.FNAL.GOV> for dtucker@sdss.fnal.gov;
 Wed, 5 May 1999 17:00:59 -0500 CDT
Received: (from hlin@localhost) by proxima.as.arizona.edu (8.9.1/8.9.1)
 id PAA12135; Wed, 05 May 1999 15:00:55 -0700 (MST)
Date: Wed, 05 May 1999 15:00:54 -0700 (MST)
From: Huan Lin <hlin@as.arizona.edu>
Subject: LCRS spectra
In-reply-to: <3717DB15.15FB@fnal.gov>
To: dtucker@fnal.gov (Douglas Tucker)
Cc: hlin@as.arizona.edu
Message-id: <199905052200.PAA12135@proxima.as.arizona.edu>
MIME-version: 1.0
X-Mailer: ELM [version 2.4 PL23]
Content-type: text/plain; charset=US-ASCII
Content-transfer-encoding: 7bit
X-Mozilla-Status: 9001
Content-Length: 1809

Hi Douglas,

I'm sending out to you today by regular mail a dat tape
with all the LCRS object spectra. They are saved as a tar
archive of fits files, arranged by observing run (8811, 8905 ... 9410).
As I mentioned while I was in Chicago, I don't have a convenient
program to map the apertures to the public catalog entries, but
that can be done manually by matching the night and frame number
in the catalog headers to the run and fits file name, and by 
using the following table to match the fits file aperture numbers
to Shec's pseudo-hex id numbers (the last 2 digits of the "s#" in the 
catalogs):


  1 01      15 11      29 21      43 31    
  2 02      16 12      30 22      44 32
  3 03      17 13      31 23      45 33
  4 04      18 14      32 24      46 34
  5 05      19 15      33 25      47 35
  6 06      20 16      34 26      48 36
  7 07      21 17      35 27      49 37
  8 08      22 18      36 28      50 38
  9 09      23 19      37 29      51 39
 10 0A      24 1A      38 2A      52 3A
 11 0B      25 1B      39 2B      53 3B
 12 0C      26 1C      40 2C      54 3C
 13 0D      27 1D      41 2D      55 3D
 14 0E      28 1E      42 2E      56 3E

 57 41      71 51      85 61      99 71
 58 42      72 52      86 62     100 72
 59 43      73 53      87 63     101 73
 60 44      74 54      88 64     102 74
 61 45      75 55      89 65     103 75
 62 46      76 56      90 66     104 76
 63 47      77 57      91 67     105 77
 64 48      78 58      92 68     106 78
 65 49      79 59      93 69     107 79
 66 4A      80 5A      94 6A     108 7A
 67 4B      81 5B      95 6B     109 7B
 68 4C      82 5C      96 6C     110 7C
 69 4D      83 5D      97 6D     111 7D
 70 4E      84 5E      98 6E     112 7E


Have fun with the spectra, and let me know if there are any problems.


Huan

