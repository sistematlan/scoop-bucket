# scoop-bucket

Bucket oficial de [sistematlan](https://sistematlan.com) para
[Scoop](https://scoop.sh) (gestor de paquetes de línea de comandos para
Windows).

## Uso

```powershell
scoop bucket add sistematlan https://github.com/sistematlan/scoop-bucket
scoop install mistah
```

## Paquetes

| Paquete | Descripción |
|---|---|
| [`mistah`](bucket/mistah.json) | CLI open-source multiplataforma que recupera espacio en disco: cachés, papelera, backups viejos y más. Sin telemetría, código auditable. |

Los manifiestos en este bucket se actualizan automáticamente vía
[GoReleaser](https://goreleaser.com) en cada release de sus respectivos
proyectos — no se editan a mano. Ver `.goreleaser.yaml` en
[sistematlan/mistah](https://github.com/sistematlan/mistah) para el
mecanismo exacto.

## Licencia

Cada paquete respeta la licencia del proyecto que empaqueta. Este
bucket en sí (metadata, no el software empaquetado) es MIT.
