# ngx-webcam-demo
This is a simple Demo-Project for <a href="https://github.com/basst314/ngx-webcam">ngx-webcam</a>.

It shows how to use the Webcam-Component from `ngx-webcam` in a simple use-case, including parameters and event-bindings.

## Demo
Try the <a href="https://basst314.github.io/ngx-webcam/?">Live-Demo</a> to see everything in action.

## Usage
To see how `ngx-webcam` is being used, take a closer look at these files:
* <a href="https://github.com/basst314/ngx-webcam-demo/blob/master/package.json#L22">package.json</a>: Add the latest version of `ngx-webcam` to your project.
* <a href="https://github.com/basst314/ngx-webcam-demo/blob/master/src/app/app.module.ts#L15">app.module.ts</a>: See how the `WebcamModule` is imported into the Angular project.
* <a href="https://github.com/basst314/ngx-webcam-demo/blob/master/src/app/app.component.ts">app.component.ts</a>: The snapshot-trigger and event-handler for the `WebcamComponent` are placed here.
* <a href="https://github.com/basst314/ngx-webcam-demo/blob/master/src/app/app.component.html#L7">app.component.html</a>: The `<webcam>`-tag binds it all together - parameters and event-handlers. It displays the live view of the user's webcam.

## Issues
Please open issues at the original <a href="https://github.com/basst314/ngx-webcam">ngx-webcam repository</a>.
