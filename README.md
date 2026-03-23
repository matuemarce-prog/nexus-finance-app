# NEXUS FINANCE

Gerado pelo **APK FORGE** — HTML to Android Converter.

## Build via GitHub Actions (recomendado)

1. Faça push deste repositório para o GitHub
2. Vá em **Actions** → o workflow "Build APK" iniciará automaticamente
3. Aguarde ~5 minutos
4. Baixe o APK em **Actions → workflow concluído → Artifacts**

## Build local

### Pré-requisitos
- Android Studio ou Android SDK
- JDK 17+

```bash
chmod +x gradlew
./gradlew assembleDebug
```

APK gerado em: `app/build/outputs/apk/debug/app-debug.apk`

## Configuração

| Campo | Valor |
|---|---|
| App Name | NEXUS FINANCE |
| Package ID | com.nexusfinance.app |
| Version | 1.0.0 (code: 1) |
| Min SDK | API 26 |
| Orientation | portrait |
| Fullscreen | true |
