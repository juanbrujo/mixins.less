mixins.less
===========

My basic mixins collection for **LESS** projects. Is is basically separated in 2 main structures:

- debug mixin
- common mixins


.out();
--
used for debugging, add it to a selector and it will surround it with an:
    
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

.background-size();
--

    @arguments

.box-shadow();
--

    @arguments
    
.border-radius(@radius);
--

    @radius
    
.opacity();
--
deals with those crappy prefixes and the filter for IE:

    @opacity:0.5

.transform();
--

    @arguments
        
.transform-origin();
--

    @arguments

.transition-delay();
--

    @time
    
.transition();
--

    @arguments

.animation-delay();
--

    @time
    
.animation();
--

    @arguments
        
.perspective();
--

    @arguments 

.columns();
--

    @arguments 