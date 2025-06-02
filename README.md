# idb-cache

> ⚠️ Work in Progress — This package is currently under development.

---

`idb-cache` aims to be a lightweight, flexible, and developer-friendly caching layer for React (or general JS apps) using **IndexedDB** under the hood.

The goal is to simplify front-end caching of API responses, large datasets (like GeoJSON), or version-controlled assets, all while ensuring performance and reliability in offline-first scenarios.

---

## 📦 Why is this published?

This package is published early to **secure the name `idb-cache`** on npm.  
Implementation is **not yet complete**, and **not recommended for production use** at this stage.

---

## 📅 Roadmap (Planned Features)

- ✅ Simple API for setting/getting cache with expiration and version control
- 🔄 Background cache refresh (stale-while-revalidate model)
- 🧠 Auto garbage collection of outdated entries
- 📁 Namespace and key scoping
- ⚛️ React integration via custom hooks (optional)
- 🌐 Multi-tab synchronization support

---

## 🛠️ Installation (for testing/dev purposes only)

```bash
npm install idb-cache
