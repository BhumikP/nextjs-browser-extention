# Demo Next.js Browser Extension

This demo project was created to serve as a template Next.js application that can be bundled into a browser extension.

# Do following to Run the Package as Browser Extention

1> npm run build

2> npm run export

3> Change \_next file name from out file according to your path:-

# Windows/Linux

mv ./out/\_next ./out/next && cd ./out && grep -rl '/\_next' \* | xargs sed -i 's|/\_next|/next|g'

# MacOS

mv ./out/\_next ./out/next && cd ./out && grep -rli '\_next' \* | xargs -I@ sed -i '' 's|/\_next|/next|g' @;
