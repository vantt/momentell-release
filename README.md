# momentell releases

Bản phát hành của `momentell`: hỏi Claude Desktop về graph của vault Obsidian (note nào nối với note nào, đi từ ý này
tới ý kia qua đâu, note nào lạc khỏi mạng). Mã nguồn ở repo private; repo này chỉ dựng, thử và đăng bản phát hành.

Tải ở [Releases](https://github.com/vantt/momentell-release/releases). Cài một dòng (thay `vX.Y.Z` bằng tag của bản
muốn cài; bản thử `-rc` phải ghi tag vì GitHub không coi pre-release là bản mới nhất):

- Windows (PowerShell): `irm https://github.com/vantt/momentell-release/releases/download/vX.Y.Z/install.ps1 | iex`
- macOS, Linux: `curl -fsSL https://github.com/vantt/momentell-release/releases/download/vX.Y.Z/install.sh | sh`

Mọi file được kiểm sha256 theo `checksums.txt` của bản phát hành.

Workflow ở `.github/workflows/` được chép từ repo mã nguồn bằng `scripts/sync-release-repo.sh`; sửa ở đó, không sửa ở
đây.
