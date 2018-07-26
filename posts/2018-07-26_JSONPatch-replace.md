Today I learned

- JSONPatch, the good, the bad and the ugly
    - replacing an object property
        - foo.bar = {}
        - {"op": "replace", "path": "foo/bar", "value": {"baz":"baf"}}
        - no trelling slashes
    - whats not possible
        - foo = {}
        - {"op": "add", "path": "foo/bar/baz", "value": "baf"}
