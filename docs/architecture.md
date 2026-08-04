# معماری اولیه وب‌اپ کارخانه

## انتخاب فنی

Architecture: Option A

- Framework: Next.js
- Language: TypeScript
- Styling: Tailwind CSS
- Backend & Database: Supabase
- Authentication: Supabase Auth
- Storage: Supabase Storage

## Multilingual Strategy

The application will support Persian and English from the beginning.

Requirements:

- Full RTL support for Persian
- LTR support for English
- Language-aware routing

Suggested structure:

```
app/
 └── [locale]/
     ├── page.tsx
     ├── about/
     ├── store/
     ├── repair/
     ├── darkroom/
     └── library/
```

Locales:

- fa (Persian - default)
- en (English)

## Main Domains

### Store

Products, inventory, new and used equipment.

### Repair Center

Repair requests, service status, customer communication.

### Darkroom

Film processing, scanning, analog equipment.

### Library

Photography, cinema and art books.

## Development Approach

Build the foundation first:

1. Project setup
2. Design system
3. Internationalization
4. Core pages
5. Database models
6. Management panel
