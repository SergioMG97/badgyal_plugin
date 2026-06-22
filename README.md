# Bad Gyal Skill para Codex CLI

Skill `/modo_pussy_exclusive` para que Bad Gyal guíe a Martita hasta sus regalos de cumpleaños.

## Instalación

```bash
# Clonar y usar desde aquí (lo que muestra la web)
git clone https://github.com/SergioMG97/badgyal_plugin bad-gyal
cd bad-gyal
codex           # abre Codex CLI en este directorio
```

## Uso

```
/modo_pussy_exclusive
```

## Preparación (Sergio)

El hash correcto (ya integrado en `AGENTS.md`) es:

```
FP7HXQX5H47AL34R63O4M2IZHGVQPGH6NLXS5SNGYBIZUI2TWBJA
```

Este hash es SHA-256 (base32, uppercase) de:
```
deberias mirar si hay algo en la despensa luego podrias echarte una partidita
a la play con el nuevo mando mientras escuchas un set de dj edo no te olvides
de arreglar el somier
```

## Mecánica del puzzle

1. La web `/regalos` muestra el hash con 10 huecos (`-`):
   `F-7HXQX5H47--34-63-4-2IZHGVQPGH6-LX-5SNGYBIZUI2-WBJ-`

2. Sergio envía 1 correo desde cuenta fake de Bad Gyal con la canción **"Pura Adrenalina"**.
   Las 10 iniciales que rellenan los huecos (en orden de posición en el hash) son:
   - Título (P, A): "**P**ura **A**drenalina"
   - 8 palabras clave en negrita en la letra: **L**oca · **R**elax · **O**ye · **M**ueve · **N**oche · **S**ola · **T**umbao · **A**hora

3. Martita coloca cada inicial en su hueco → hash completo

4. Ejecuta `/modo_pussy_exclusive`, da el hash → Bad Gyal verifica y revela las ubicaciones
