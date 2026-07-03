# White Paper v2.0 Release Checklist

## Required artifacts

- [ ] `Guardianship_Doctrine_White_Paper_v2.0.tex`
- [ ] `sources.bib`
- [x] `README.md`
- [x] `CHANGELOG.md`
- [x] `release_manifest.json`
- [ ] `appendices/`
- [ ] `figures/` when referenced by the LaTeX source
- [ ] `Guardianship_Doctrine_White_Paper_v2.0.pdf`

## Compile readiness

- [ ] Placeholder count is zero.
- [ ] No bracketed stubs remain in the LaTeX source.
- [ ] Markdown-style bullets are converted to LaTeX environments.
- [ ] Mermaid is removed or explicitly supported by the build chain.
- [ ] All bibliography entries resolve.
- [ ] All tables compile cleanly.
- [ ] All figure paths resolve.
- [ ] Dependency check passes.
- [ ] `latexmk` or `pdflatex` completes without fatal errors.
- [ ] Final PDF exists.
- [ ] Release manifest matches the source tree.
- [ ] Release tag `v2.0` is created only after all gates pass.

## Release gate

```text
if placeholder_count = 0
and latex_compile = PASS
and pdf_exists = true
and manifest_complete = true
and dependency_check = PASS
then release_status = READY
else release_status = BLOCKED
```

Current status: **BLOCKED — source, bibliography, appendices, and compiled PDF are not yet present on this branch.**
