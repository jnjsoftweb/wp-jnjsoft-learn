# 최초 생성(windows11)

## local sites

"""
name: wp-jnjsoft-learn
user: jnjsoft.web
password: Jnjsoft******
email: jnjsoft.web@gmail.com
"""

## files

### folder.file 삭제, 복사

```sh
cd "/Users/youchan/Local Sites/wp-jnjsoft-learn/app/public"
rmdir /s /q "wp-content/themes/twentytwentythree"
rmdir /s /q "wp-content/themes/twentytwentytwo"
```

### 수정

> `/Users/youchan/Local Sites/wp-jnjsoft-learn/app/public/_docs/setup.md`

## github

```sh
github -e pushRepo -u jnjsoftweb -n wp-jnjsoft-learn -d "JNJSOFT 학습관"
```