---
title: Image Key Points
type: templates
order: 103
meta_title: Image Keypoints Data Labeling Template
meta_description: Label Studio Image Keypoints Template for machine learning and data science data labeling projects.
---

Key Point labeling for images.

<img src="/images/screens/image_keypoints.png" class="img-template-example" title="Images Key Points" />

## Run

```bash
label-studio init image_keypoints_project
label-studio start image_keypoints_project 
```

After starting Label Studio, set up the labeling interface and browse to this template.

## Config 

```html
<View>
  <KeyPointLabels name="tag" toName="img" strokewidth="5">
    <Label value="Ear" background="blue"></Label>
    <Label value="Lip" background="red"></Label>
  </KeyPointLabels>
  <Image name="img" value="$image" zoom="true"></Image>
</View>
```
