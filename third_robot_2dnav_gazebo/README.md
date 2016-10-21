# Third Robot 2d Navigation gazebo

## 雰囲気
- [デモ動画](https://youtu.be/t8RvtNwTC90)
- まだまだ怪しい…．

## 準備
`wstool`を使ったことがなかったら`ros`のワークスペースで以下のコマンドを実行する．

```
$ cd ~/catkin_ws/src
$ wstool init .
```

## ビルド方法

```
$ cd ~/catkin_ws/src
$ wstool set --git third_robot_2dnav https://github.com/CIR-KIT/third_robot_2dnav.git
$ wstool update
```

## 使い方
- amcl の自己位置推定

```bash
roslaunch third_robot_2dnav_gazebo autorun.launch 
```

- gmapping の地図作成

```bash
roslaunch third_robot_gmapping_gazebo autorun.launch 
```
