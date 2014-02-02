mixins.less
===========

My basic mixins collection for LESS projects. Is is basically separated in 2 main stuctures:

- colors variables
- useful mixins

.out();
--
this is used for debugging, add it to a selector and it will surround it with an:
    
    outline: 1px solid @color // (red is default).

.escondetxt()
--
hides text with the common:

    text-indent: -9999px;
    overflow: hidden;

.zero();
--
basic universal reseter:

    margin:0; padding:0;

.gradient-vertical();
--
deals with those crappy prefixes and the filter for IE:

    @startColor: #1e5799, @endColor: #7db9e8
    
.gradient-horizontal();
--
deals with those crappy prefixes and the filter for IE:

    @startColor: #1e5799, @endColor: #7db9e8
    
.box-shadow();
--
deals with those crappy prefixes:

    @arguments
    
.border-radius(@radius);
--
deals with those crappy prefixes:

    @radius
    
.opacity();
--
deals with those crappy prefixes and the filter for IE:

    @opacity:0.5
    
.transform();
--
deals with those crappy prefixes:

    @arguments
    
.transition();
--
deals with those crappy prefixes:

    @arguments
    
.columns();
--
deals with those crappy prefixes:

    @arguments 

