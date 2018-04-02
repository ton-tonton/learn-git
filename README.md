# Learn Git Flow

## Feature Branch
แตก Branch จาก Develop
```
git co develop
git co -b feaure/feature_name
```
ทำงาน
```
git add .
git commit -m "Add feature feature_name"
git push origin feature/feature_name
```
เปิด PR


## Release Branch
แตก Branch จาก Develop
```
git co develop
git co -b release/version_number
```
แก้ไข version กับ release note
```
git add .
git commit -m "Release version_number"
git push orgin release/version_number
```
เปิด PR merge เข้า Develop กับ Master
