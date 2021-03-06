[Back to the Ling/Light_User api](https://github.com/lingtalfi/Light_User/blob/master/doc/api/Ling/Light_User.md)



The LightUserInterface class
================
2019-05-10 --> 2021-06-24






Introduction
============

The LightUserInterface interface.
See more info in the [conception page](https://github.com/lingtalfi/Light_User/blob/master/doc/pages/conception.md).



Class synopsis
==============


abstract class <span class="pl-k">LightUserInterface</span>  {

- Methods
    - abstract public [isValid](https://github.com/lingtalfi/Light_User/blob/master/doc/api/Ling/Light_User/LightUserInterface/isValid.md)() : bool
    - abstract public [getIdentifier](https://github.com/lingtalfi/Light_User/blob/master/doc/api/Ling/Light_User/LightUserInterface/getIdentifier.md)() : string | false
    - abstract public [hasRight](https://github.com/lingtalfi/Light_User/blob/master/doc/api/Ling/Light_User/LightUserInterface/hasRight.md)(string $right) : bool

}






Methods
==============

- [LightUserInterface::isValid](https://github.com/lingtalfi/Light_User/blob/master/doc/api/Ling/Light_User/LightUserInterface/isValid.md) &ndash; Returns whether the user is valid.
- [LightUserInterface::getIdentifier](https://github.com/lingtalfi/Light_User/blob/master/doc/api/Ling/Light_User/LightUserInterface/getIdentifier.md) &ndash; or false if the user is not valid.
- [LightUserInterface::hasRight](https://github.com/lingtalfi/Light_User/blob/master/doc/api/Ling/Light_User/LightUserInterface/hasRight.md) &ndash; Returns whether the user has the given right.





Location
=============
Ling\Light_User\LightUserInterface<br>
See the source code of [Ling\Light_User\LightUserInterface](https://github.com/lingtalfi/Light_User/blob/master/LightUserInterface.php)



SeeAlso
==============
Previous class: [LightOpenUser](https://github.com/lingtalfi/Light_User/blob/master/doc/api/Ling/Light_User/LightOpenUser.md)<br>Next class: [LightWebsiteUser](https://github.com/lingtalfi/Light_User/blob/master/doc/api/Ling/Light_User/LightWebsiteUser.md)<br>
