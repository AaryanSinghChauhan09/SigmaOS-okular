# SigmaOS-okular

SigmaOS integration component for **Okular document viewer**.

## Commands

```bash
sigmaos-okular install   # install package + deploy defaults
sigmaos-okular deploy    # copy config templates to $HOME
sigmaos-okular status    # binary/package/config report
sigmaos-okular reset     # remove deployed config
sigmaos-okular open      # launch the application
```

## Design

- Shell-based component manager (Omarchy-style per-app repos)
- Secure defaults; no secrets stored
- Deterministic `test.sh` with isolated `$HOME`
