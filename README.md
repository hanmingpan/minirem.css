# minirem.css

rem layout

# Install
    npm i minirem.css --save

# Usage

## Module
    import 'minirem.scss'

## Browser
    <link rel="stylesheet" href="rem.css">

# Example
    .main {
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
