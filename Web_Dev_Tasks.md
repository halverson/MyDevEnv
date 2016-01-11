# Common Task Runner Logic

## CSS
1. Compile Sass into CSS
2. Run CSS through autoprefixer
3. Concat any remaining separate CSS files (if they weren't in Sass compile)
4. Minify final CSS file and save to dist/build folder

## Javascript
1. Concat various scripts
2. Minify / Uglify script
3. Save to dist/build folder

## Images
1. Optimize Images
2. Save all images into sub-folder in dist/build

## Watch and Rebuild on changes
1. Watch all Sass, JS and images for changes.
2. When a file is changed > clean dist/build folder & rebuild it with new files.
