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

## css
    .main {
        width: 1rem;
    }

## sass
    // variable.scss

    $baseFontSize:100;

    @function px2rem($px){
        @return $px / $baseFontSize * 1rem;
    }

    // index.scss
    @import "variable";

    .main {
        width: px2rem(100);
    }
