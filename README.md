# Learn Git Flow

## Feature Branch
แตก branch จาก develop
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
เปิด PR merge เข้า develop

## Release Branch
แตก branch จาก develop
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
เปิด PR merge เข้า develop กับ master

## Hotfix Branch
แตก branch จาก master
```
git co master
git co -b hotfix/bugfix
```
แก้ไข bug
```
git add .
git commit -m "Fix bug"
git push origin hotfix/bugfix
```
เปิด PR merge เข้า develop กับ master
