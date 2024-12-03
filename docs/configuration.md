# ⚙️ Panduan Konfigurasi Cursor

## 🎨 Konfigurasi Dasar

### Tema dan Tampilan
1. Buka Settings (Ctrl/Cmd + ,)
2. Pilih tab Appearance
3. Sesuaikan:
   - Theme (Light/Dark)
   - Font Size
   - Font Family
   - Line Height
   - Editor Layout

### Keyboard Shortcuts
- Customize shortcuts di Settings > Keyboard
- Shortcut penting:
  - `Ctrl/Cmd + P`: Quick Open
  - `Ctrl/Cmd + Shift + P`: Command Palette
  - `Ctrl/Cmd + /`: Toggle Comment
  - `F1`: AI Command

## 🤖 Konfigurasi AI

### Model AI
1. Buka Settings > AI
2. Pilih model yang diinginkan:
   - GPT-4 (VIP)
   - GPT-3.5
   - Codex

### Prompt Templates
1. Buat custom prompt di Settings > AI > Templates
2. Format template:
   ```
   [INSTRUCTION]
   Tulis kode untuk: {input}
   [/INSTRUCTION]
   ```

### Auto-Complete
- Enable/disable di Settings > AI
- Atur delay time
- Set trigger characters

## 🔧 Konfigurasi Git

### Setup Git
1. Buka Settings > Git
2. Masukkan credentials:
   - Username
   - Email
   - Token (optional)

### Git Integration
- Enable/disable auto fetch
- Set fetch interval
- Configure remote

## 📦 Extensions

### Instalasi Extension
1. Buka Extension Panel
2. Browse available extensions
3. Klik Install pada extension yang diinginkan

### Recommended Extensions
- ESLint
- Prettier
- GitLens
- Path Intellisense
- Auto Close Tag

## 🛠️ Workspace Settings

### Project Config
1. Buat file `.cursor/settings.json`
2. Tambahkan konfigurasi:
   ```json
   {
     "editor.formatOnSave": true,
     "editor.tabSize": 2,
     "files.exclude": {
       "node_modules": true
     }
   }
   ```

### Language Specific
```json
{
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[python]": {
    "editor.rulers": [80]
  }
}
```

## 🔒 Keamanan

### API Keys
1. Buka Settings > Security
2. Masukkan API keys yang diperlukan
3. Pastikan keys tersimpan aman

### Firewall Settings
- Allow Cursor di firewall
- Buka port yang diperlukan
- Set rules yang sesuai

## 🔄 Sync Settings

### Enable Sync
1. Login ke akun Cursor
2. Buka Settings > Sync
3. Pilih item yang ingin disync:
   - Settings
   - Keybindings
   - Extensions
   - Snippets

### Backup Settings
1. Export settings ke file
2. Simpan di tempat aman
3. Restore saat diperlukan

## 📱 Performance

### Memory Usage
- Atur max memory di Settings
- Clear cache secara berkala
- Monitor penggunaan resource

### Startup Options
- Enable/disable auto start
- Set startup behavior
- Configure initial layout

## 🌐 Network

### Proxy Settings
1. Buka Settings > Network
2. Masukkan konfigurasi proxy:
   - Host
   - Port
   - Authentication

### Offline Mode
- Set offline mode options
- Configure cache behavior
- Manage local resources 