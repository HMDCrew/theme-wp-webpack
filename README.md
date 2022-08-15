# theme-wp-webpack
 Webpack for wordpress theme

     git clone https://github.com/HMDCrew/theme-wp-webpack.git
     mv theme-wp-webpack assets

     cd assets
     npm i

# Add separate build file:
   *./webpack.config.js*
```js
const entry = {
    index: SRC_DIR + '/index.js',
    
    ...

    // Separated compilation file (for any other page added after this line you need restart webpack)
    home: PAGES_DIR + '/home.js',
};
```
