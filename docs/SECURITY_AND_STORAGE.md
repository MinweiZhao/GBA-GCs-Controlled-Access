# Security And Storage Requirements

Approved users must:

- store controlled files on encrypted or institutionally managed storage
- restrict access to named project members
- avoid syncing controlled files to public cloud folders or personal devices
- keep raw archives out of public Git repositories
- verify archives with SHA-256 checksums before use
- delete temporary extracted copies after analysis when possible
- report suspected exposure or misuse promptly

Recommended local layout:

```text
controlled_data/
  archives/              # encrypted or access controlled
  extracted/             # temporary, not synced publicly
  derived_aggregate/     # publishable only after review
  logs/
```

