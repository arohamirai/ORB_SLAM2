# Monocular Examples

## TUM Data

通用格式

```
./Examples/Monocular/mono_tum Vocabulary/ORBvoc.txt Examples/Monocular/TUMX.yaml PATH_TO_SEQUENCE_FOLDER
```

例子

```
./Examples/Monocular/mono_tum Vocabulary/ORBvoc.txt Examples/Monocular/TUM2.yaml /mnt/hgfs/Download/rgbd_dataset_freiburg2_xyz/
```





## KITTI Dataset

通用格式

```
./Examples/Monocular/mono_kitti Vocabulary/ORBvoc.txt Examples/Monocular/KITTIX.yaml PATH_TO_DATASET_FOLDER/dataset/sequences/SEQUENCE_NUMBER
```

例子

```
./Examples/Monocular/mono_kitti Vocabulary/ORBvoc.txt Examples/Monocular/KITTI04-12.yaml /mnt/hgfs/Download/data_odometry_gray/dataset/sequences/08
```



# Stereo Examples

## KITTI Dataset

通用格式

```
./Examples/Stereo/stereo_kitti Vocabulary/ORBvoc.txt Examples/Stereo/KITTIX.yaml PATH_TO_DATASET_FOLDER/dataset/sequences/SEQUENCE_NUMBER
```

例子：

```
./Examples/Monocular/mono_kitti Vocabulary/ORBvoc.txt Examples/Monocular/KITTI04-12.yaml /mnt/hgfs/Download/data_odometry_gray/dataset/sequences/08
```



# RGB-D Examples

## TUM Dataset

通用格式

```
python associate.py PATH_TO_SEQUENCE/rgb.txt PATH_TO_SEQUENCE/depth.txt > associations.txt

./Examples/RGB-D/rgbd_tum Vocabulary/ORBvoc.txt Examples/RGB-D/TUMX.yaml PATH_TO_SEQUENCE_FOLDER ASSOCIATIONS_FILE
```

例子

```
./Examples/RGB-D/rgbd_tum Vocabulary/ORBvoc.txt Examples/RGB-D/TUM3.yaml /mnt/hgfs/Download/rgbd_dataset_freiburg3_nostructure_texture_far/ /mnt/hgfs/Download/rgbd_dataset_freiburg3_nostructure_texture_far/associations.txt
```