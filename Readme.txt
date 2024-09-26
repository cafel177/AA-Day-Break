              Axis & Allies Readme v1.0.0

The Axis & Allies website is located at
http://www.axisandalliesrts.com/

For more information about TimeGate Studios, please visit
http://www.timegate.com/

If you want to know more about Atari and their other titles, please visit
http://www.atari.com/

Unauthorized copying, reproduction, rental, public performance, or broadcast of
this game is a violation of applicable laws.

Windows is a trademark or registered trademark of Microsoft Corporation in the
U.S. and/or other countries.  All rights reserved.

Contents:
   Introduction
   1- Windows Related Issues
      a) Microsoft Office Toolbar
      b) Windows 2000/XP Access rights
      c) Compatibility
      d) Windows Update
   2- Troubleshooting
      a) Uninstalling
      b) Drivers
      c) DirectX
      d) Video Performance
      e) Multiplayer Performance
      f) Resetting User Preferences
      g) Reporting Problems
   3- Known Problems
      a) Graphics
      b) System
      c) Sound
   4- Asian Fonts
   5- Command Line Parameters
   6- Contact Information
   7- Additional Credits
   8- Copyright

Introduction

This file contains additional information that supplements the Axis & Allies manual. 
For more information on playing Axis & Allies, please refer to the manual 
supplied with the game.


1- Windows Related Issues

   a) In the event that the Microsoft Office toolbar appears in front of the
      A&A game screen, you will have to disable the toolbar before 
      starting the game.

   b) Windows 2000/XP: Administrator access rights are required to install 
      Axis & Allies on Windows 2000/XP, but Limited Users will be able
      to run the game after it is installed.

   c) Axis & Allies will work on Windows 98, Windows Me, Windows 2000, 
      and Windows XP (Home or Professional). Note that Windows 95 is not 
      supported.

   d) Be sure to regularly update your Windows operating system to receive 
      the benefit of any patches and Service Packs Microsoft has made 
      available. Microsoft provides this service to licensed users of 
      Windows at http://windowsupdate.microsoft.com/
	
	
2- Troubleshooting

   a) Uninstalling

   When uninstalling Axis & Allies, certain files and folders may 
   be left behind in the folder where the game was installed, such as saved 
   games, and other game generated files. If this is the case you may need 
   to remove them manually.

   b) Drivers

   If you experience any problems running Axis & Allies, you should 
   verify that you have the latest drivers for your hardware from the 
   appropriate manufacturer - particularly for your sound card and video card.

   c) DirectX

   DirectX 9.0c or later is required. The latest version of DirectX can be obtained
   from http://www.microsoft.com/directx

   If you experience problems after the new Microsoft DirectX drivers have
   been installed, please contact your local Microsoft subsidiary, or write to:

   Microsoft Customer Sales and Service,
   One Microsoft Way,
   Redmond, WA 98052-6399, USA

   USA telephone: 1-800-426-9400
   International telephone: ++1-206-882-8080

   d) Video Performance

   You may experience decreased frame rates in 5+ player games on large maps
   with several regiments.  If you do not have a powerful machine, we suggest
   the following options to improve performance:

      1) Turn off music - go to the Options Dialog and reduce volume to 0.

      2) Use the Options Dialog to reduce the resolution to 800x600 pixels.

      3) Select the lowest quality video settings available.

      4) Use the Options Dialog to zoom in to the map as close as you can 
      tolerate, this will let you see only a relatively small portion of 
      the map which will improve your frame rate.  The Options Dialog can 
      also be used to change the zoom.

      5) Avoid playing games with more than 4 players or games on large maps.
   
   e) Multiplayer Performance

   If you have a firewall in place, we recommend visiting the following web page for 
   information on how to configure your firewall to allow you to host multiplayer games.
   Axis & Allies uses UDP on ports 6900 and 5860.

        http://www.gamespyarcade.com/support/firewalls.shtml

   You may experience lag problems if the host does not have a high bandwidth 
   connection.  These lag problems are related to the number of players, the 
   number of regiments, and whether or not your game is listed publicly on GameSpy.   
   If you are hosting a game on a low bandwidth connection, we suggest the following 
   options to improve multiplayer performance:

      1) Avoid playing games with more than 4 players on a 56K modem particularly on large 
         maps with several regiments.

      2) If playing large maps with lots of regiments, reduce the number of
         computer AI players (each AI player consumes bandwidth).

      3) If you are hosting a game on a modem and having multiplayer problems, turning
         off "Report In Progress" may help. This will prevent your game from being listed
         publicly.

   f) Resetting User Preferences
  
   User preferences can be reset by deleting the .RUP file located under
   "My Documents/A&A/Data/User/". This may be necessary, for example, if you
   have recently changed video cards and the saved game resolution is
   no longer valid. 

   g) Reporting Problems

   You can get help from a variety of sources. Atari technical support can be reached at:
  
        http://www.atari.com/us/support/

   TimeGate technical support can be reached at:

        http://www.timegate.com/

   A&A generates a lot of information to help track down problems. When
   reporting a crash or other problem, please build a ZIP file with the 
   following data.  These files can be retrieved from the "A&A"
   folder under "My Documents." Some files are located in the folder where
   A&A is installed.

   For all problems:

   - any .DMP file generated from the crash

   - any .LOG files generated (LOGS folder)

   - if appropriate, screenshots generated with the "PrintScreen" 
     key.  Screenshot files have the form A&A_0000.png and are located in
     the Screenshots folder under "My Documents/A&A/Data/".

   - if appropriate, save games (.RSG files located under SAVE, 
     or .RCG located under the CAMPAIGNSAVE folder for campaign missions).   

   - if appropriate, films (.RFM files located under /FILMS) if you have
     used the "Save Film" option. If you have not, then the "LAST FILM.RFM"
     file is automatically generated.

   - if appropriate, preferences file (.RUP file located under USER)

   On a custom map:
  
   - the appropriate .RMP file from the MAPS folder 


3- Known Problems

   a) Graphics
      No known problems.

   b) System
      No known problems.

   c) Audio
      No known problems.

   d) Input
      Note: On Windows 2000/XP you will need Administrator access to perform these steps.

      If you are experiencing problems with the mousewheel on your Logitech mouse,
      first download and install the latest Mouseware drivers for your Logitech mouse from
      http://www.logitech.com. Restart your machine after installing the drivers
      and run Axis & Allies. If the problem is still not resolved, create
      a shortcut to the Axis & Allies executable, in the "Shortcut" tab,
      in the "Target" editbox, add "+FixLogitech" (without the quotes) right after
      the name of the A&A executable, separated by one space. Run this shortcut
      by double-clicking on it, the game will run briefly, adding special registry
      entries that tell the Logitech mouse driver how A&A is going to use the
      mousewheel. Reboot your system one more time, run A&A normally (not using
      the shortcut you created, which you can delete), and the problem should
      be resolved. Note that it is only necessary to do this once per installation, do
      not continue to use the "+FixLogitech" option, since this command requires a reboot.
      This command adds the Axis & Allies executable name to Logitech's registry key
      at {HKEY_LOCAL_MACHINE}\Software\Logitech\MouseWare\CurrentVersion\GamingCompatibility.


4- Asian Fonts

   To be able to see Asian text (or any left-to-right non-Latin-based text) 
   you will need to have the necessary fonts installed or you will see 
   Asian text as pound signs ('#'). For Windows XP, you can install Asian 
   fonts by opening your Control Panel in Windows, double-clicking on the 
   "Regional and Language Options" icon, selecting the "Languages" tab, 
   and checking the "Install files for East Asian Languages" box. For 
   other versions of Windows, please consult your Windows documentation.

   Note that running with Asian fonts requires significantly more memory on 
   your system, so there may be a noticeable loss in performance when compared 
   to not running with Asian fonts.

   Also note that players you are sending Asian text to must also have 
   Asian fonts installed or they will see your text as pound signs as well. 
   Having Asian fonts on your machine only lets you see the Asian text 
   properly on your machine, how the text is seen by other players depends on
   what Asian fonts they have installed on their machines.

   As of May 2004, Axis & Allies uses these Asian fonts if they 
   are installed in the Windows Fonts folder:

   Korean (Hangul Jamo and Hangul Johab): GulimChe (gulim.ttc)
   Japanese (Katakana and Hiragana): MS Gothic (MSGOTHIC.TTC)
   Chinese (Han, may also be used for Japanese Kanji and Korean): MingLiU (mingliu.ttc)


5- Command Line Parameters

   To run these commands, make a Windows shortcut to the application's 
   executable file, the easiest way to do this is by making a copy of the
   A&A shortcut on the desktop (if you had one installed) or by 
   dragging the A&A icon from the program group in the Windows 
   Start menu to the desktop. Right click on the shortcut icon and select
   "Properties." In the "Shortcut" tab in the "Target" editbox add the desired 
   command right after the executable name, with one space between the executable 
   name and the command, put a '+' character in front of the command, like this: 
	 "C:\Program Files\Atari\Axis & Allies\AA.exe +CommandName".

   Some useful commands are listed here:

   a) FixLogitech (see "Input" in section 3)

   b) CDKeyClear - causes the application to "forget" about a previously-
      entered CD Key, so a new one can be entered. This is useful if you 
      have installed one copy of Axis & Allies on two machines, but 
      you want to be able to play multiplayer on both machines simultaneously. 
      You will need to purchase a second copy of the game (to get a second 
      CD key which is necessary for online play) and run "CDKeyClear" on one 
      of the machines to be prompted for the CD key of the second copy.


6- Contact Information

   Please refer to the manual for specific technical support contact details.

   Atari Technical Support can also be reached through the Atari web site:
   http://www.atari.com/support.php
      
   (Please read our FAQ or use the Technical Support page before
    writing or calling us.)

   Game site:
   http://www.timegate.com/aa/

7- Additional Credits

   Portions of this software are included under license.  (c)2004 Numerical Design, Ltd.
   All rights reserved. Gamebryo(r) is a registered trademark of Numerical Design, Ltd.

   Uses Bink Video.  Copyright (c)1997-2004 by RAD Game Tools, Inc.

   MPEG Layer-3 playback supplied with the Miles Sound System from RAD Game Tools, Inc. 
   MPEG Layer-3 audio compression technology licensed by Fraunhofer IIS and THOMSON multimedia.

   This product contains software technology licensed from GameSpy Industries, Inc.  
   (c) 1999-2004 GameSpy Industries, Inc.  GameSpy and the "Powered by GameSpy" design are
   trademarks of GameSpy Industries, Inc.  All rights reserved.

   libpng versions 1.0.7, July 1, 2000, through 1.2.5, October 3, 2002, are Copyright 
   (c)2000-2002 Glenn Randers-Pehrson.

   zlib.h -- interface of the 'zlib' general purpose compression library version 1.2.1, 
   November 17th, 2003. Copyright (c)1995-2003 Jean-loup Gailly and Mark Adler.


8- Copyright

   © 2003-2004 Atari, Inc. All Rights Reserved. Portions licensed from and © 2002-2004 TimeGate Studios, Inc. All Rights Reserved.

   
   
   
END-USER LICENSE AGREEMENT

IMPORTANT - READ CAREFULLY:  Please be sure to carefully read and understand all of the rights and restrictions described in this End-User License Agreement ("EULA").

AGREEMENT

This document is an agreement between you and Atari, Inc. and its affiliated companies, and its licensors ("Company").  The enclosed software game disc(s), cartridge or Game Pak ("Software") and any accompanying printed materials are licensed to you only on the condition that you accept all of the terms contained in this EULA.

By opening this package and installing or otherwise using the Software you agree to be bound by the terms of this EULA.  If you do not agree to the terms of this EULA you may not install or use the Software and within 15 days of purchase you must call the Tech Support telephone number listed in the manual accompanying the Software (the "Manual").  Select the Automated Phone System's Main Menu option for Consumer Services and follow the prompts.

You will be given a Return Merchandise Authorization number (RMA #) by the technician.  You then have 15 days from the date of this contact to return the Software in its protective covering, the Manual and the original sales invoice to the address supplied to you.

If this is a PC product, when you install the Software you will be asked to review and either accept or not accept the terms of the EULA by clicking the "I Accept" button.  By clicking the "I Accept" button you acknowledge that you have read the EULA, understand it and agree to be bound by its terms and conditions.

COPYRIGHT

The Software is protected by copyright laws and international copyright treaties, as well as other intellectual property laws and treaties.  All title and copyrights in and to the Software (including but not limited to any images, photographs, animations, video, music, text and "applets" incorporated into the Software) and any printed materials accompanying the Software are owned by the Company or its Licensors.

GRANT OF LICENSE

The Software is licensed and not sold to you and its use is subject to this EULA.  The Company grants you a limited, personal, non-exclusive license to use the Software in the manner described in the user documentation.  The Company reserves all rights not expressly granted to you in this EULA.

PERMITTED USES

1.	If the Software is configured for loading on a hard drive, you may install and use the Software on a single computer.
2.	You may make and maintain one copy of the Software for backup and archival purposes, provided that the original and copy of the Software are kept in your possession.
3.	You may permanently transfer all your rights under this EULA, provided you retain no copies, you transfer all of the Software (including all component parts, the media and printed materials and any upgrades) and the recipient reads and accepts this EULA.

RESTRICTIONS

1.	You may not delete or obscure any copyright, trademark or other proprietary notice on the Software or accompanying printed materials.
2.	You may not decompile, modify, reverse engineer, disassemble or otherwise reproduce the Software.
3.	You may not copy, rent, lease, sublicense, distribute, publicly display the Software, create derivative works based on the Software (except to the extent expressly permitted in the Editor and End-User Variation section of this Agreement or other documentation accompanying the Software) or otherwise commercially exploit the Software.
4.	You may not electronically transmit the Software from one computer, console or other platform to another or over a network.
5.	You may not use any backup or archival copy of the Software for any purpose other than to replace the original copy in the event it's destroyed or becomes defective.

EDITOR AND END-USER VARIATIONS

If the Software includes a feature that allows you to modify the Software or to construct new variations (an "Editor"), you may use such Editor to create modifications or enhancements to the Software, including the construction of new levels (collectively the "Variations"), subject to the following restrictions.  Your Variations: (i) must only work with the full, registered copy of the Software; (ii) must not contain modifications to any executable file; (iii) must not contain any libelous, defamatory or other illegal material, material that is scandalous or invades the rights of privacy or publicity of any third party; (iv) must not contain any trademarks, copyright-protected work or other property of third parties; and (v) may not be commercially exploited by you, including but not limited to making such Variations available for sale or as part of a pay-per-play or timesharing service.

TERMINATION

This EULA is effective until terminated.  You may terminate this EULA at any time by destroying the Software.  This EULA will terminate automatically without notice from the Company if you fail to comply with any provisions of this EULA.  All provisions of this EULA as to warranties, limitation of liability, remedies and damages will survive termination.

LIMITED WARRANTY AND DISCLAIMER OF WARRANTIES

You are aware and agree that use of the Software and the media on which is recorded is at your sole risk.  The Software and media are supplied "AS IS."  Unless otherwise provided by applicable law, the Company warrants to the original purchaser of this product that the Software storage medium will be free from defects in materials and workmanship under normal use for ninety (90) days from the date of purchase.  The warranty is void if the defect has arisen through accident, abuse, neglect or misapplication.  If the Software fails to conform to this warranty, you may at your sole and exclusive remedy, obtain a replacement free of charge if you return the defective Software.  Follow the Product Return Procedures described in the Manual.  The Company does not warrant that the Software or its operations or functions will meet your requirements, or that the use of the Software will be without interruption or error.

TO THE FULLEST EXTENT PERMISSIBLE UNDER APPLICABLE LAW, EXCEPT FOR THE EXPRESS WARRANTY SET FORTH ABOVE, THE COMPANY DISCLAIMS ALL WARRANTIES, EXPRESS OR IMPLIED, INCLUDING AND WITHOUT LIMITATION, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT. EXCEPT FOR THE EXPRESS WARRANTY SET FORTH ABOVE, THE COMPANY DOES NOT WARRANT, GUARANTEE OR MAKE ANY REPRESENTATION REGARDING THE USE OR THE RESULTS OF THE USE OF THE SOFTWARE IN TERMS OF ITS CORRECTNESS, ACCURACY, RELIABILITY, CURRENTNESS OR OTHERWISE.  SOME JURISDICTIONS DO NOT ALLOW THE EXCLUSION OF OR LIMITATIONS ON IMPLIED WARRANTIES, SO THE ABOVE EXCLUSIONS AND LIMITATIONS MAY NOT APPLY TO YOU.
LIMITATION OF LIABILITY

IN NO EVENT WILL THE COMPANY OR ITS EMPLOYEES OR LICENSORS BE LIABLE FOR ANY INCIDENTAL, INDIRECT, SPECIAL, CONSEQUENTIAL OR PUNITIVE DAMAGES, OR ANY DAMAGES WHATSOEVER (INCLUDING, WITHOUT LIMITATION, DAMAGES FOR INJURY TO PERSON OR PROPERTY, FOR LOSS OF PROFITS, BUSINESS INTERRUPTION, LOSS OF BUSINESS INFORMATION, LOSS OF PRIVACY, FAILURE TO MEET ANY DUTY AND NEGLIGENCE) ARISING OUT OF OR IN ANY WAY RELATED TO THE USE OR INABILITY TO USE THE SOFTWARE, EVEN IF THE COMPANY OR AN AUTHORIZED REPRESENTATIVE OF THE COMPANY HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.  SOME JURISDICTIONS DO NOT ALLOW THE EXCLUSION OF LIABILITY FOR INCIDENTAL OR CONSEQUENTIAL DAMAGES, SO THE ABOVE EXCLUSION MAY NOT APPLY TO YOU.

IN NO EVENT WILL THE LIABILITY OF THE COMPANY FOR DAMAGES WITH RESPECT TO THE SOFTWARE EXCEED THE AMOUNTS ACTUALLY PAID BY YOU FOR THE SOFTWARE.

CHOICE OF LAW AND VENUE

This EULA is governed by the laws of the United States of America and the State of New York, exclusive of its conflicts of law provisions.  The exclusive venue for litigation regarding or arising from this EULA is New York County, New York and you agree to submit to the Jurisdiction of the courts of New York County, New York for any such litigation.

MISCELLANEOUS

If any provision or portion of this EULA is found to be unlawful, void, or for any reason unenforceable, it will be severed from and in no way affect the validity or enforceability of the remaining provisions of the EULA.

This EULA constitutes the entire agreement between you and the Company regarding the Software and its use.


TECHNICAL SUPPORT (U.S. & Canada)
Help Via the Internet
Up-to-the-minute technical information about Atari products is generally available 24 hours a day, 7 days a week via the Internet at:
http://www.atarisupport.com
Through this site you’ll have access to our FAQ (Frequently Asked Questions) documents, our FTP (File Transfer Protocol) area where you can download patches if needed, our Hints/Cheat Codes if they’re available, and an E-Mail area where you can get help and ask questions if you do not find your answers within the FAQ.
Note: In the event we must send you a Hint Sheet, FAQ document, patch or update disc via E-mail, we may require verifiable consent from a parent or guardian in order to protect children’s privacy and safety online. Consent Forms are available at the web site listed above.
Help Via Telephone in the United States & Canada
For phone assistance, call Atari Technical Support at (425) 951-7108. Our Interactive Voice Response system is generally available 24/7, providing automated support solutions immediately.
Great News! We’ve improved our Automated Systems so that you can get product-specific Troubleshooting help more quickly. All you need to do is enter the product’s Part # when prompted to do so. This will take you directly to all of our known issues and solutions for this title. The product’s Part # is located in several places (on the CD label, package and/or plastic disc case) and is usually identified by a number such as 04-12345. When prompted by the Automated System, enter the last five digits of your product’s Part #. (For example, Part # 04-12345 would require that you enter the “12345” portion of the number for that product.) Note: Some products simply feature a five-digit Part # without an “04-” prefix.
Live support is generally available Monday through Friday, 8:00 AM until 6:00 PM (Pacific Time). Note: We may be closed on major holidays.
Before making your call, we ask that you be at your computer, have the following information available, and be ready to take notes:
•	System Make and Model 
•	Processor Type
•	Operating System, including version number if possible (such as Windows® 98; Windows® Me)
•	RAM (Memory)
•	Video and sound card data and drivers
•	Any screen or error messages you’ve encountered (and where)
Product Return Procedures in the United States & Canada
In the event our technicians at (425) 951-7108 determine that you need to forward materials directly to us, please include a brief letter explaining what is enclosed and why. Make sure you include the Return Merchandise Authorization Number (RMA#) supplied to you by the technician, and your telephone number in case we need to call you. You will receive the mailing address when the technician gives you the RMA#. Any materials not containing this RMA# will be returned to you unprocessed.
Warranty Policy in the United States & Canada
If our technicians determine that the product storage medium is found to be defective within ninety (90) days of original purchase, (unless otherwise provided by applicable law), Atari will replace the item free of charge, to the original purchaser, if the item is accompanied by the original dated receipt and packaging.
