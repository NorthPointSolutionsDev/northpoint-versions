# Northpoint Versions

Public version tracking for **Northpoint Solutions** in-game resources.

## About

**Northpoint Versions** is a public repository used exclusively to track the current versions of Northpoint Solutions in-game resources.

The repository does **not** contain source code, resource files, or development builds. It simply provides version information so systems and users can determine whether a resource is up to date.

## Structure

Each resource has its own JSON file directly within the repository:

```text
Northpoint-Versions/
├── resource-name.json
├── another-resource.json
└── ...
```

Each JSON file contains the version information for its corresponding resource.

## Version Tracking

The files in this repository are intended to be used by our resources, update systems, or other integrations to check for newer versions.

If the version reported by a resource does not match the latest version listed here, the installed resource may be outdated.

## Public Repository

This is intentionally one of the few **public repositories** within the Northpoint Solutions organization.

Only version information is published here. Private source code, internal tooling, and other development resources remain within their respective private repositories.

---

**Northpoint Solutions**
*Public version tracking for our in-game resources.*
