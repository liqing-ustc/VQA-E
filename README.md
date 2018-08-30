# VQA-E: Explaining, Elaborating, and Enhancing Your Answers for Visual Questions

## Dataset Download
[COCO](http://cocodataset.org/#download) Images:
[Training images \[83K/13GB\]](http://images.cocodataset.org/zips/train2014.zip), [Validation Images \[41K/6GB\]](http://images.cocodataset.org/zips/val2014.zip)

VQA-E dataset:
[Google Drive](https://drive.google.com/open?id=1SD6-ktSyOPpSwq1vsHbfmee8ueHvrf5a)

Annotation format:
```
annotation{
    "image_id" : int,
    "question_type" : str,
    "answer_type" : str,
    "answers" : [answer],
    "multiple_choice_answer" : str,
    "explanation": [explanation, score]
}
```

### Reference
If you use the VQA-E dataset as part of any published research, please acknowledge the following paper
```
@@article{li2018vqae,
  title={VQA-E: Explaining, Elaborating, and Enhancing Your Answers for Visual Questions},
  author={Li, Qing and Tao, Qingyi and Joty, Shafiq and Cai, Jianfei and Luo, Jiebo},
  journal={ECCV},
  year={2018}
}
```
### License

MIT License.
