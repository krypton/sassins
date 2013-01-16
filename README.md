sassins
=======

A set of SASS mixins


## Dependencies

### css

    * {
      -webkit-box-sizing: border-box; /* Safari */
      -moz-box-sizing: border-box; /* Firefox */
      box-sizing: border-box;
    }
    
### html     

    <!--[if lt IE 7]>      <html class="no-js lt-ie9 lt-ie8 lt-ie7"> <![endif]-->
    <!--[if IE 7]>         <html class="no-js lt-ie9 lt-ie8"> <![endif]-->
    <!--[if IE 8]>         <html class="no-js lt-ie9"> <![endif]-->
    <!--[if gt IE 8]><!--> <html class="no-js"> <!--<![endif]-->

    
## Examples

    @include sizes('div', '200px', '270px', '20px', '2px');
    @include vcenter('div');
