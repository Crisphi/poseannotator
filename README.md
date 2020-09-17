# Pose Annotator

Pose Annotator allows you to manually improve 2D poses from OpenPose results.

Specifically, you can import images and the corresponding poses recognized by OpenPose as JSON files
and then modify them by click and drag, as well as add and delete parts of the poses and whole poses.

In addition to a work file, which records whether an image and its annotations have already been checked,
the improved poses can be exported as JSON files in OpenPose format.

As a HTML one pager you can use the tool without installation via your browser.
At the moment the app is optimized for standard Firefox.

The app is available [online](https://crisphi.github.io/poseannotator/ "Pose Annotator"), however, I would highly recommend
downloading the tool, as the app is designed for offline use and a sample data set is included.

For further information have a look at the [user manual](https://docs.google.com/document/d/1t2OCi7HAAHCphB0O1CmdNRlzamoxoq1w4XdWJdLQ6aI/edit?usp=sharing "User manual") and feel free to contact me.

## Currently working on

* Tutorial

## To Do's

* fix issues with nightly Firefox browser / improve browser compatibility

* (support single file json annotations)
* (moving whole pose)

## Things to think about

* How do we want to proceed with confidence levels? Do we overwrite them?

## Already done

  ### Loading
  * Load original json and image files
  * Load working file with poseannotator schema

  ### Export
  * Export working file with poseannotator schema
  * Export zipped json files in original openpose schema

  ### Annotation
  * Move single points of the pose annotations

  ### Deletion Mode
  * Undo recent changes
  * Undo all made changes on specific image
  * Delete specific Point completely
  * Deletion of whole pose

  ### Creation Mode
  * Possibility of adding new points without violating body schema rules
  * Create whole new pose

  ### Settings
  * Possibility to change file paths

  ### Diverse
  * Key controls
  * Show file list in toolbar
  * Change color of annotations for better contrast
  * Show which files have already been checked
  * Selection of whole pose (deletion / movement)
  * Table of shortcuts
