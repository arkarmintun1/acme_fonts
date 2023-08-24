This flutter package is created to organize the fonts instead of manually adding into project. The explanation can be checked in this article.

## Fonts

- Inter
- Montserrat


## Getting started

- Add the package from github in the project `pubspec.yaml`
```yaml
dependencies:
  acme_fonts:
    git:
      url: https://github.com/arkarmintun1/acme_fonts.git
      ref: main
```
- Import the fonts
```yaml
flutter:
  fonts:
    - family: Inter
      fonts:
        - asset: packages/acme_fonts/fonts/Inter-Thin.ttf
          weight: 100
        - asset: packages/acme_fonts/fonts/Inter-ExtraLight.ttf
          weight: 200
        - asset: packages/acme_fonts/fonts/Inter-Light.ttf
          weight: 300
        - asset: packages/acme_fonts/fonts/Inter-Regular.ttf
          weight: 400
        - asset: packages/acme_fonts/fonts/Inter-Medium.ttf
          weight: 500
        - asset: packages/acme_fonts/fonts/Inter-SemiBold.ttf
          weight: 600
        - asset: packages/acme_fonts/fonts/Inter-Bold.ttf
          weight: 700
        - asset: packages/acme_fonts/fonts/Inter-ExtraBold.ttf
          weight: 800
        - asset: packages/acme_fonts/fonts/Inter-Black.ttf
          weight: 900
    - family: Montserrat
      fonts:
        - asset: packages/acme_fonts/fonts/Montserrat-Thin.ttf
          weight: 100
        - asset: packages/acme_fonts/fonts/Montserrat-ExtraLight.ttf
          weight: 200
        - asset: packages/acme_fonts/fonts/Montserrat-Light.ttf
          weight: 300
        - asset: packages/acme_fonts/fonts/Montserrat-Regular.ttf
          weight: 400
        - asset: packages/acme_fonts/fonts/Montserrat-Medium.ttf
          weight: 500
        - asset: packages/acme_fonts/fonts/Montserrat-SemiBold.ttf
          weight: 600
        - asset: packages/acme_fonts/fonts/Montserrat-Bold.ttf
          weight: 700
        - asset: packages/acme_fonts/fonts/Montserrat-ExtraBold.ttf
          weight: 800
        - asset: packages/acme_fonts/fonts/Montserrat-Black.ttf
          weight: 900
```

## Usage

```
Text(
  "Using the Inter font from the acme_fonts package",
  style: TextStyle(fontFamily: AcmeFonts.inter),
)
```

