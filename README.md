SproutAlignmentProblem
======================

Problem Description:

A customer is requesting that their ad be centered on devices when it is viewed. The current behavior is to align the ad to the top left corner of the screen.

Your task is to modify the included ad code to display the ad vertically and horizontally centered as requested.

Requirements:

* The ad in its initial orientation it should be centered horizontally and vertically.
* When the ad is tapped or clicked on, the ad will expand to a new width and height. Make sure the expanded ad is centered.
* If the ad is viewed on a desktop browser the ad should remain centered if you resize the browser.
* On orientation change of the device, the ad should be centered to the new width and height values. Make sure this works properly on physical Android devices.

See the videos in the extra directory for examples of how the ad should behave. Android behavior should be the same as the example in the iPhone video.

Notes: 

* The ad could be viewed on mobile web in various screen sizes. Make sure there are no hardcoded height and width values used in the code.
* You should only have to work on the code in index.html to complete the project.
* You will need to host the ad somewhere (localhost works). You will also need to update cdnBase and iframeSourceURL to point to where you are hosting the ad. Example: cdnBase : 'http://sprout.local/step3/' and iframeSourceURL : 'http://sprout.local/step3/ad.html?v=1'

Bonus points for using webkit animations to smoothly change the css top and left values when centering.

Note: Sprout ads will not work in Firefox. They must be viewed in a browser that supports Webkit.