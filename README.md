# How to recreate issue

Check out project, `npm install` then `npm start`. Webpack should crash with a missing dependency. If `require('dynamic-cdn-webpack-plugin')` is removed, webpack should run ok (kinda, it doesn't really do anything here :stuck_out_tongue:)
