.. _changelog:


***************
Changelog
***************

.. 

.. _0.2:

Version 0.2
-----------------
*October 2010*

* All helpers classes moved to the utils.py, added Table helper class
* *Incompatibility with previous release* Changed names of the methods' params to reflect real oDesk params - e.g. company_reference vs company name

.. _0.1.2:

Version 0.1.2
-----------------
*29 September 2010*

Bug fix release

* Fixed check_token method
* Fixed KeyError on empty workdiaries 

.. _0.1.1:

Version 0.1.1
-----------------
*15 July 2010*

Bug fix release

* Fixed HR2.get_user_role(user_id=None, team_id=None, sub_teams=False) method to correctly get user roles when both user reference and team reference were submitted - previously only one of them was used in the request
* Documentation fixes

.. _0.1:

Version 0.1
-----------------
*08 July 2010*

First public release

       