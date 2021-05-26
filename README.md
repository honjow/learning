# Learning

The easy way to use Machine Learning Kit in Flutter.

## Getting Started

Add dependency to your flutter project:

```
$ flutter pub add learning
```

or

```yaml
dependencies:
  learning: ^0.0.1
```

Then run `flutter pub get`.

**Optimization**

For best performance (and to minimize application size), it's better to add dependency directly from each of sub-plugins you want to use in your application. 

## Usage

Learning consists of 13 different plugins that we can add separately depending on our application needs.

<table>
  <tr>
    <th>Vision Plugins</th>
    <th>Status</th>
    <th>Version</th>
    <th>Links</td>
    <th>Example App</th>
  </tr>
  <tr>
    <td>learning_text_recognition</td>
    <td><b>Published</b></td>
    <td>^0.0.1</td>
    <td>
      https://pub.dev/packages/learning_text_recognition<br>
      https://github.com/salkuadrat/learning/tree/master/packages/learning_text_recognition
    </td>
    <td>
      <a href="https://github.com/salkuadrat/learning/tree/master/apk/text_recognition.apk">text_recognition.apk</a>
    </td>
  </tr>
  <tr>
    <td>learning_face_detection</td>
    <td><b>Published</b></td>
    <td>^0.0.2</td>
    <td>
      https://pub.dev/packages/learning_face_detection<br>
      https://github.com/salkuadrat/learning/tree/master/packages/learning_face_detection
    </td>
    <td>
      <a href="https://github.com/salkuadrat/learning/tree/master/apk/face_detection.apk">face_detection.apk</a>
    </td>
  </tr>
  <tr>
    <td>learning_pose_detection</td>
    <td><b>Published</b></td>
    <td>^0.0.1</td>
    <td>
      https://pub.dev/packages/learning_pose_detection<br>
      https://github.com/salkuadrat/learning/tree/master/packages/learning_pose_detection
    </td>
    <td>
      <a href="https://github.com/salkuadrat/learning/tree/master/apk/pose_detection.apk">pose_detection.apk</a>
    </td>
  </tr>
  <tr>
    <td>learning_selfie_segmentation</td>
    <td><b>Published</b></td>
    <td>^0.0.1</td>
    <td>
      https://pub.dev/packages/learning_selfie_segmentation<br>
      https://github.com/salkuadrat/learning/tree/master/packages/learning_selfie_segmentation
    </td>
    <td>
      <a href="https://github.com/salkuadrat/learning/tree/master/apk/selfie_segmentation.apk">selfie_segmentation.apk</a>
    </td>
  </tr>
  <tr>
    <td>learning_image_labeling</td>
    <td><b>Published</b></td>
    <td>^0.0.1</td>
    <td>
      https://pub.dev/packages/learning_image_labeling<br>
      https://github.com/salkuadrat/learning/tree/master/packages/learning_image_labeling
    </td>
    <td>
      <a href="https://github.com/salkuadrat/learning/tree/master/apk/image_labeling.apk">image_labeling.apk</a>
    </td>
  </tr>
  <tr>
    <td>learning_barcode_scanning</td>
    <td><b>Published</b></td>
    <td>^0.0.2</td>
    <td>
      https://pub.dev/packages/learning_barcode_scanning<br>
      https://github.com/salkuadrat/learning/tree/master/packages/learning_barcode_scanning
    </td>
    <td>
      <a href="https://github.com/salkuadrat/learning/tree/master/apk/barcode_scanning.apk">barcode_scanning.apk</a>
    </td>
  </tr>
  <tr>
    <td>learning_object_detection</td>
    <td><b>Published</b></td>
    <td>^0.0.1</td>
    <td>
      https://pub.dev/packages/learning_object_detection<br>
      https://github.com/salkuadrat/learning/tree/master/packages/learning_object_detection
    </td>
    <td>
      <a href="https://github.com/salkuadrat/learning/tree/master/apk/object_detection.apk">object_detection.apk</a>
    </td>
  </tr>
  <tr>
    <td>learning_digital_ink_recognition</td>
    <td>Development</td>
    <td></td>
    <td>https://github.com/salkuadrat/learning/tree/master/packages/learning_digital_ink_recognition</td>
    <td></td>
  </tr>
  <tr>
    <td>learning_input_image</td>
    <td><b>Published</b></td>
    <td>^0.0.5</td>
    <td>
      https://pub.dev/packages/learning_input_image<br>
      https://github.com/salkuadrat/learning/tree/master/packages/learning_input_image
    </td>
    <td></td>
  </tr>
</table>
<br>
<table>
  <tr>
    <th>NLP Plugins</th>
    <th>Status</th>
    <th>Version</th>
    <th>Links</th>
    <th>Example App</th>
  </tr>
  <tr>
    <td>learning_language</td>
    <td><b>Published</b></td>
    <td>^0.0.2</td>
    <td>
      https://pub.dev/packages/learning_language<br>
      https://github.com/salkuadrat/learning/tree/master/packages/learning_language
    </td>
    <td>
      <a href="https://github.com/salkuadrat/learning/tree/master/apk/language.apk">language.apk</a>
    </td>
  </tr>
  <tr>
    <td>learning_translate</td>
    <td><b>Published</b></td>
    <td>^0.0.2</td>
    <td>
      https://pub.dev/packages/learning_translate<br>
      https://github.com/salkuadrat/learning/tree/master/packages/learning_translate
    </td>
    <td>
      <a href="https://github.com/salkuadrat/learning/tree/master/apk/translate.apk">translate.apk</a>
    </td>
  </tr>
  <tr>
    <td>learning_smart_reply</td>
    <td><b>Published</b></td>
    <td>^0.0.2</td>
    <td>
      https://pub.dev/packages/learning_smart_reply<br>
      https://github.com/salkuadrat/learning/tree/master/packages/learning_smart_reply
    </td>
    <td>
      <a href="https://github.com/salkuadrat/learning/tree/master/apk/smart_reply.apk">smart_reply.apk</a>
    </td>
  </tr>
  <tr>
    <td>learning_entity_extraction</td>
    <td><b>Published</b></td>
    <td>^0.0.2</td>
    <td>
      https://pub.dev/packages/learning_entity_extraction<br>
      https://github.com/salkuadrat/learning/tree/master/packages/learning_entity_extraction
    </td>
    <td>
      <a href="https://github.com/salkuadrat/learning/tree/master/apk/entity_extraction.apk">entity_extraction.apk</a>
    </td>
  </tr>
</table>