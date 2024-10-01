# 최초 생성 (macos)

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
rm -rf "wp-content/themes/twentytwentythree"
rm -rf "wp-content/themes/twentytwentytwo"

cp "/Users/youchan/Local Sites/wp-class101-from-planning-to-launch/app/public/.gitignore" "Users/youchan/Local Sites/wp-jnjsoft-learn/app/public/.gitignore"

cp -R "/Users/youchan/Local Sites/wp-class101-from-planning-to-launch/app/public/_env/". "Users/youchan/Local Sites/wp-jnjsoft-learn/app/public/_env/"

cp -R "/Users/youchan/Local Sites/wp-class101-from-planning-to-launch/app/public/_test/". "Users/youchan/Local Sites/wp-jnjsoft-learn/app/public/_test/"
```

### 수정

> `/Users/youchan/Local Sites/wp-jnjsoft-learn/app/public/_docs/setup.md`

## github

```sh
github -e pushRepo -u jnjsoftweb -n wp-jnjsoft-learn -d "JNJSOFT 학습관"
```

## vscode 작업영역에 폴더추가
"/Users/youchan/Local Sites/wp-jnjsoft-learn/app/public/"