## `shared` Folder

This folder contains reusable components, helpers, or middleware that can be used across the entire application but may have dependencies on internal logic (unlike pkg, which is fully independent).
shared is designed to reduce duplication and keep common utilities centralized.

### Example Structure

```
shared/
├── utils/
│   └── time.go
├── middleware/
│   └── auth.go
```
