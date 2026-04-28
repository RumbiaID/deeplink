# Asset Links (Android App Links)

## Endpoint

<https://deeplink.rumbia.id/.well-known/assetlinks.json>

## Fungsi

Digunakan untuk verifikasi domain ke aplikasi Android (App Links / deep linking).

## Relation

- delegate_permission/common.handle_all_urls → untuk membuka semua URL ke app

## SHA256

Sumber:

- Development: EAS (eas credentials -p android) -> SHA256 Fingerprint ["2D:EC:57:.....:F1:95:A8"]
  
- Production: Play Console → App Integrity → App Signing Key → SHA256 Fingerprint ["7D:46:64:.....:D8:14:B5"]
