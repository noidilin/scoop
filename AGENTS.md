# AGENTS.md - Development Guidelines for Scoop Bucket

## Build/Test Commands
- **Run all tests**: `.\bin\test.ps1` (PowerShell) or `pwsh .\bin\test.ps1`
- **Format JSON manifests**: `.\bin\formatjson.ps1`
- **Check versions**: `.\bin\checkver.ps1`
- **Check URLs**: `.\bin\checkurls.ps1`
- **Check hashes**: `.\bin\checkhashes.ps1`

## Code Style Guidelines
- **Encoding**: UTF-8 with CRLF line endings
- **Indentation**: 4 spaces for all files, 2 spaces for YAML
- **JSON formatting**: Use formatjson.ps1 to ensure proper formatting
- **Manifests**: Follow Scoop manifest schema in `bucket/app-name.json.template`
- **Required fields**: version, description, homepage, license, architecture, url, hash
- **PowerShell**: Use approved verbs, proper error handling, requires statements
- **File names**: Use kebab-case for manifests, PascalCase for PowerShell scripts
- **Comments**: Use `##` for template comments in JSON manifests
- **Arrays**: Use array notation for multiple values (bin, shortcuts, notes)
- **URLs**: Use HTTPS when available, follow autoupdate patterns
- **Hashes**: Always include SHA256 hashes for downloads

This is a Scoop bucket repository containing Windows package manifests in JSON format.