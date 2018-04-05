Release Notes for TYPO3 CMS 6.2.7
=================================

This document contains information about TYPO3 CMS 6.2.7 which was
released on November 27th, 2014.

News
----

This release is a bug fix release.

Notes
-----

This is part of a combined release of TYPO3 CMS 4.5.38 and 6.2.7.

Download
--------

<https://typo3.org/download/>

MD5 checksums
-------------

    f4d8f9211012e5922f7f25b9cb2c169a  typo3_src-6.2.7.tar.gz
    86f1bd0642093dc91c4b5cb9364b5ad5  typo3_src-6.2.7.zip

Upgrading
---------

The [usual upgrading
procedure](https://docs.typo3.org/typo3cms/InstallationGuide/) applies.
No database updates are necessary.

Changes
-------

Here is a list of what was fixed since
[6.2.6](TYPO3_CMS_6.2.6 "wikilink"):

    2014-11-27  38ca1ac                  [RELEASE] Release of TYPO3 6.2.7 (TYPO3 Release Team)
    2014-11-27  73e7e81  #63345          [BUGFIX] Follow up: Use strrpos to find last occurence (Andreas Fernandez)
    2014-11-26  d8511d1  #63350          [BUGFIX] Pagination wrong in IndexedSearch (Markus Klein)
    2014-11-26  cd75c44  #61654          [BUGFIX] Introduce chunking for large expression lists (Andreas Fernandez)
    2014-11-25  97e9d19  #63107          [BUGFIX] Source element within picture element has wrong src attribute (Arnd Messer)
    2014-11-24  0f47f24  #63281          [BUGFIX] Fix typo of variable (Andreas Fernandez)
    2014-11-24  145c36e  #61361          [FEATURE] Allow fallback paths in FLUIDTEMPLATE (Markus Klein)
    2014-11-24  f582179  #61361          [FEATURE] Template Path fallback for Fluid Standalone View (Anja Leichsenring)
    2014-11-24  411fe21  #60998          [BUGFIX] Fix PHP warning in shouldFieldBeOverlaid() (Markus Klein)
    2014-11-23  0c5486c  #63273          [BUGFIX] The raw search must check if field exists (Georg Ringer)
    2014-11-21  48f3fd9  #61630          [BUGFIX] Output dashed name for missing CLI arguments (Mathias Brodala)
    2014-11-21  8d9ed03  #62553          [BUGFIX] Fix access to empty ObjectStorage with numeric key (Mathias Brodala)
    2014-11-20  3dc31de  #63113          [TASK] Disable a test on PHP 5.3 (Christian Kuhn)
    2014-11-20  84faee0  #63113          [TASK] Update to phpunit 4.3 (Christian Kuhn)
    2014-11-20  be27106  #51982          [BUGFIX] Fix type check in advanced query search (Georg Ringer)
    2014-11-20  3391af0  #48529          [BUGFIX] Fix absolute link generation for files (Markus Klein)
    2014-11-20  77f7fa2  #63086          [BUGFIX] Properly match html tags with data-* attributes (Ludwig Rafelsberger)
    2014-11-20  c3443df  #62966          [TASK] Clear opcode cache on Core update (Markus Klein)
    2014-11-20  5f77b4e  #63096          [BUGFIX] Remove unused files_upload (Alexander Opitz)
    2014-11-20  c7e8c74  #63087          [BUGFIX] Correctly remember acquired shared locks (Ludwig Rafelsberger)
    2014-11-19  160def4  #61251          [BUGFIX] Never show hidden domains in preview (Markus Klein)
    2014-11-19  351d55f  #62089          [TASK] Inform about invalid index.php symlink (Markus Klein)
    2014-11-19  1d3304e  #62932          [BUGFIX] Correctly parse timestamps in format.date VH (Markus Klein)
    2014-11-19  341d9cc  #63080          [BUGFIX] mysqli_stmt::reset may throw a PHP warning (Xavier Perseguers)
    2014-11-19  7140e80  #59133          [BUGFIX] Handling of umlauts/accents in convertFileLinks in upg. wizard (Joachim Rinck)
    2014-11-19  1d967bf  #58053          [BUGFIX] Handle opacity for IE in prototype.js (Jigal van Hemert)
    2014-11-18  9046423  #63042          [BUGFIX] Implement wrapper for array_column function (Markus Klein)
    2014-11-18  43c16ad  #62930          [BUGFIX] RTE maxWidth for magic images (Bernhard Kraft)
    2014-11-17  0b467c4  #63038          [BUGFIX] RTE: Incorrect text in language combo of abbreviation dialogue (Stanislas Rolland)
    2014-11-17  976a5a5  #62843          [TASK] RTE: Update some references to core documentation (Stanislas Rolland)
    2014-11-17  016ae93  #63030          [BUGFIX] RTE: JS error raised in Abbreviation dialogue (Stanislas Rolland)
    2014-11-17  7d43291  #60343          [BUGFIX] Make sys_file_metadata publishable (Helmut Hummel)
    2014-11-16  c5abb44  #59998          [TASK] Increase verbosity of exception (Björn Fromme)
    2014-11-16  43eefb7  #63003          [TASK] Add css and less files to .editorconfig (Frank Nägler)
    2014-11-16  d065b56  #60235          [BUGFIX] Register the exception handler early in bootstrap (Helmut Hummel)
    2014-11-16  a10bcc5  #62365          [BUGFIX] Enable links in install tool configuration sections (Björn Fromme)
    2014-11-15  686679e  #62965          [TASK] Add XLF file checker for TRAVIS CI (Markus Klein)
    2014-11-15  7d8bd4d  #62892          [TASK] Add missing language unique ids (Christian Kuhn)
    2014-11-15  2e13984  #62961          [BUGFIX] Avoid warning caused by missing array key noScale (Kay Strobach)
    2014-11-14  5600b11                  Revert "[BUGFIX] Make sys_file_metadata publishable" (Helmut Hummel)
    2014-11-14  8f06c8d  #60343          [BUGFIX] Make sys_file_metadata publishable (Helmut Hummel)
    2014-11-14  1b82aa3  #62892          [!!!][TASK] Add unique identifier to language files (Eugene Kenah Djomo)
    2014-11-14  5b1fa3d  #61900          [BUGFIX] ClassLoader: Clear after Exception (Alexander Opitz)
    2014-11-14  f297713  #62950          [BUGFIX] Add namespace argument for inline settings array (Frank Nägler)
    2014-11-14  8b2d9ba  #62482          [BUGFIX] Fix bug in HMENU special prev (Frederic Gaus)
    2014-11-13  098522b  #50450          [BUGFIX] Correct order of key / field deletion (Alexander Stehlik)
    2014-11-13  00006b5  #60958          [BUGFIX] Page module Quickedit: wizards are broken (Benjamin Mack)
    2014-11-13  10d27be  #62918          [BUGFIX] TypoScript userFunc condition does not work with static methods (Oliver Hader)
    2014-11-12  0f1a9aa  #59305          [BUGFIX] Fix broken form wizard with MSIE (Romain Leleu)
    2014-11-10  2eb3cca  #62839          [BUGFIX] Add label for the description of scheduler group record (Georg Ringer)
    2014-11-10  acdeaa1  #61173          [BUGFIX] Bring datetime picker time fields back in IE10+ (Nikola Stojiljkovic)
    2014-11-10  0551d35  #62835          [BUGFIX] Wrong hint in deprecation log for usage of feInterface (Xavier Perseguers)
    2014-11-10  6d6418f                  Revert "[TASK] Add verbose output to report mail for failed tests" (Helmut Hummel)
    2014-11-10  2f323a9  #62805          [BUGFIX] RTE: Multi-line lists in default PageTS configs cause problems (Stanislas Rolland)
    2014-11-09  ba3a267  #59574          [BUGFIX] RTE: JS exception regarding property disableStyleOnOptionLabel (Stanislas Rolland)
    2014-11-09  725f7a0  #58034          [BUGFIX] RTE.default.buttons.blockstyle not configurable (Stanislas Rolland)
    2014-11-06  9a8c9bf  #62245          [BUGFIX] Extension installer: Handle multiple blanks (Stefan Froemken)
    2014-11-05  3d741a7  #61747          [BUGFIX] RTE: Inconsistent delete behaviour (Stanislas Rolland)
    2014-11-05  ea485fb  #56408          [BUGFIX] Quickedit mode: RTE has no user CSS (Stanislas Rolland)
    2014-11-05  b0357fc  #61738          [BUGFIX] ADOdb: Set charset properly (Andreas Fernandez)
    2014-11-04  df600c6  #62559,#59559,  [BUGFIX] RTE wraps p tags around ol/ul in chrome and opera (Stanislas Rolland)
    2014-11-03  2772c88  #62658          [BUGFIX] RTE: In IE, the pasting pad sometimes shows an error page (Stanislas Rolland)
    2014-11-03  f8bc9be  #62296          [TASK] RTE: Cleanup references to AllowClipboardHelper for Mozilla (Stanislas Rolland)
    2014-11-03  58621d4  #58786          [TASK] Add verbose output to report mail for failed tests (Benedict Burckhart)
    2014-11-03  af1c6b5  #62636          [CLEANUP] Correct phpDoc of FrontendLoginController->getDisplayText Function (Frederic Gaus)
    2014-11-02  b8edc67  #60258          [BUGFIX] Fix links of shortcuts to restricted pages in menus (Helmut Hummel)
    2014-11-01  7c3b83f  #62569          [BUGFIX] Fix script URLs for traditional modules (Helmut Hummel)
    2014-11-01  8653ca5  #52470          [BUGFIX] RTE: In Chrome RTE inserts weird span tags (Stanislas Rolland)
    2014-11-01  fa86241  #62559          [BUGFIX] RTE wraps p tags around ol/ul in chrome and opera (Stanislas Rolland)
    2014-11-01  4fb4e69  #56408          [BUGFIX] RTE: Quickedit mode - RTE has no user CSS (Stanislas Rolland)
    2014-10-31  6bbb0d9  #62032          [BUGFIX] Fix PHP warning with date function in FormEngine (Wouter Wolters)
    2014-10-31  c43f002  #42457          [BUGFIX] Fix column layout for New Content Element wizard (Martin Kästner)
    2014-10-30  9cd9cb0  #62575          [BUGFIX] Add proper URL check to TemplateService::getFileName() (Markus Klein)
    2014-10-30  140ae24  #51781          [BUGFIX] IMAGE content object accepts directories (Tomita Militaru)
    2014-10-30  de7dbde  #60773          [BUGFIX] Add check if $fileObject is a correct instance (Frank Nägler)
    2014-10-29  ea22cdf  #62532          [BUGFIX] Fix active page calculation in indexed_search (Georg Ringer)
    2014-10-29  7f0c6c3  #60437          [BUGFIX] Remove wrong escaping of email sender (Markus Klein)
    2014-10-28  3cd222a  #62503          [BUGFIX] Let save and preview button behave as user initiated (Helmut Hummel)
    2014-10-27  2ce44f2  #50549          [BUGFIX] Fix suggest wizard for new CE in flexforms (Markus Klein)
    2014-10-27  02c85f5  #62501          [BUGFIX] Declare statically called method static (Helmut Hummel)
    2014-10-27  3c74402  #40687          [BUGFIX] Only reload pagetree if pages are changed (Helmut Hummel)
    2014-10-27  eea2fac  #58105          [BUGFIX] RTE: Documentation of enableWordClean is wrong (Stanislas Rolland)
    2014-10-26  a457434  #27955          [TASK] Replace old fe_users icon with new one (Felix Kopp)
    2014-10-26  9515f6e  #62459          [BUGFIX] Link to ext:perm in clickmenu not working (Wouter Wolters)
    2014-10-25  90fcd4a  #62438          [BUGFIX] Fix JS error in SuggestWizard (Markus Klein)
    2014-10-24  33aaf53  #61529          [FEATURE] Add multiple parameter in f:form.checkbox (Stefan Froemken)
    2014-10-24  d435d0c  #52470          [BUGFIX] RTE: In Chrome RTE inserts weird span tags (Stanislas Rolland)
    2014-10-24  d7fd945  #62399          [BUGFIX] RTE: Multilingual classesAnchor titleText not possible (Stanislas Rolland)
    2014-10-24  75f21f0  #61992          [BUGFIX] Misaligned radio buttons (Francois Suter)
    2014-10-24  a79bb23  #58913          [BUGFIX] Missing and invalid warnings on referenced files (Oliver Hader)
    2014-10-23  92f9daf  #60296          [BUGFIX] Respect different object mapping for scheduler tasks (Mathias Brodala)
    2014-10-23  e44019a  #61213          [BUGFIX] ErrorHandler: Stop execution if E_RECOVERABLE_ERROR occurs (Markus Klein)
    2014-10-23  d99fb24  #62212          [BUGFIX] ClassLoader also needs to check for interfaces (Markus Klein)
    2014-10-23  ded8651  #51936          [BUGFIX] Make ContentSlide work correctly if last element is empty (Robert Vock)
    2014-10-22  a947db5                  [TASK] Set TYPO3 version to 6.2.7-dev (TYPO3 Release Team)

