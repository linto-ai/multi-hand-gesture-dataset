# multi-hand-gesture-dataset
Multi-hand gesture dataset contains 10 annotated hand gestures in VOC Pscal format using [labelImg](https://github.com/tzutalin/labelImg) tool.

Our gests are presented as follows:
1. hello
2. hand up
3. vectory
4. i love you
5. yes
6. no
7. ok
8. okay
9. call me
10. thaks

Our dataset is divided into 669 images for the train and 146 images for test

.

├── test  (669 annotated images)

└── train (146 annotated images)

Here is the content of the (.xml) file resulting from annotations:

```
<annotation>
        <folder>hello</folder>
        <filename>hello.53.jpg</filename>
        <path>/Tensorflow/workspace_mohamed/images$
        <source>
                <database>Unknown</database>
        </source>
        <size>
                <width>640</width>
                <height>480</height>
                <depth>3</depth>
        </size>
        <segmented>0</segmented>
        <object>
                <name>hello</name>
                <pose>Unspecified</pose>
                <truncated>0</truncated>
                <difficult>0</difficult>
                <bndbox>
                        <xmin>136</xmin>
                        <ymin>176</ymin>
                        <xmax>288</xmax>
                        <ymax>432</ymax>
                </bndbox>
        </object>
</annotation>

```

To use our dataset, type the following command:
```
git clone https://github.com/linto-ai/multi-hand-gesture-dataset.git
```
