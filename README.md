# HexSchool Week2-個人網頁

設計稿：https://xd.adobe.com/view/3d28af46-ac66-480d-a9a5-4b07454e6f79-687b/specs/
Github：https://github.com/hsiung0322/HexSchool-week2-profile4
Pages：https://hsiung0322.github.io/HexSchool-week2-profile4/
Youtube：https://www.youtube.com/watch?v=Knp59XTIckw

## margin-bottom (以4px為一單位)
scss
```scss
@for $i from 1 through 17 {
    .mb-#{$i} {
        margin-bottom: #{$i*4}px;
    }
}
```
css
```css
.mb-1 {
  margin-bottom: 4px;
}

.mb-2 {
  margin-bottom: 8px;
}

.mb-3 {
  margin-bottom: 12px;
}

.mb-4 {
  margin-bottom: 16px;
}
```
## padding-top、padding-bottom
```css
.pt-7 {
  padding-top: 28px;
}

.pt-14 {
  padding-top: 56px;
}

.pt-16 {
  padding-top: 64px;
}

.pb-24 {
  padding-bottom: 96px;
}

.pb-30 {
  padding-bottom: 120px;
}
```