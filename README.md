SASS-Library for RTL-Layout
===========================

A small library for lazily generating RTL layout. For flipping your layout, your body has to have a class "rtl".

Include into your _style.scss like this:

  @import 'rtl';

Use it like this:

  div.image {
    @include rtl-margin(0,0,0,1px);
    @include rtl-padding(3px,3px,3px,8px);
    @include rtl-float-right;
  }


Legal stuff
-----------

Author: Frank Boës

Company:     [BlueMars](http://www.bluemars.net)

Copyright & license: See LICENSE.txt