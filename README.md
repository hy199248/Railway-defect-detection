# 🚆 Railway Track Defect Detection Dataset (YOLO Ready)

[](https://pan.baidu.com/s/1iCqG31_ycszks5rR1CY8pQ )
🔐 **Extraction Code**: `Qf68 `

> 📥 **Direct Download**:  
> [T-铁轨缺陷检测4000YOLO.7z](https://pan.baidu.com/s/1iCqG31_ycszks5rR1CY8pQ)  
> *Open with Quark App | Account: Ja\*es Cameronm*

---

## 📊 Dataset Specifications
| Parameter           | Value         |
|---------------------|---------------|
| **Total Images**    | 4,020         |
| **Train Set**       | 3,216 images  |
| **Validation Set**  | 804 images    |
| **Defect Classes**  | 4 categories  |
| **Annotation Types**| YOLO, COCO, VOC |
| **Resolution**      | 1920×1080     |

## 🔍 Defect Categories & Distribution
| Defect Type        | Images | Bounding Boxes | Class ID |
|--------------------|--------|----------------|----------|
| **Spalling**       | 1,506  | 2,208          | `0`      |
| **Squat**          | 1,710  | 2,949          | `1`      |
| **Wheel Burn**     | 474    | 546            | `2`      |
| **Corrugation**    | 987    | 1,452          | `3`      |

---

## 📁 Dataset Structure
```plaintext
T-铁轨缺陷检测4000YOLO/
├── images/
│   ├── train/       # 3,216 training images (.jpg)
│   └── val/         # 804 validation images (.jpg)
├── labels/
│   ├── train/       # YOLO .txt annotations
│   └── val/         # YOLO .txt annotations
├── annotations/
│   ├── coco/        # COCO format (.json)
│   └── pascal_voc/  # VOC format (.xml)
└── data.yaml        # Pre-configured YOLO dataset config
