# rem.css

rem layout

# install
    npm install rem.css --save

# usage

## module
    import 'rem.scss'

## browser
    <link rel="stylesheet" href="rem.css">

# Example
    .main {
        // width: 100px;
        width: 1rem;
    }

    // variable.scss
    $baseFontSize:100;
    @function px2rem($px){
        @return $px / $baseFontSize * 1rem;
    }

    .main {
        width: px2rem(100);
    }
