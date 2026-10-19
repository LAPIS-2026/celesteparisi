# Códigos para Práctico — Prof. Celeste Parisi (LAPIS 2026)

Repositorio de materiales y códigos para el práctico de la Profesora Celeste Parisi (*VISCACHA Survey: The Dynamical History of the Magellanic Clouds Told by Their Star Clusters*) en la escuela de astrofísica **XII LAPIS 2026**.

## Instrucciones del Práctico y Descripción Completa

- **Descripción completa del proyecto (Google Drive)**: [Ver documento de instrucciones](https://drive.google.com/file/d/1rmb1D3DQWjUif6HOHRlrk4chEcl-mfbV/view?usp=sharing)
- **Proyecto**: *CaT Metallicities of SMC Star Clusters* — determinación de metalicidades de cúmulos estelares mediante la técnica del Triplete del Calcio (CaT).

## Datos y Software

- **Datos y catálogos**: Serán provistos por la profesora.
- **Software y herramientas**: R e IRAF o PyRAF.
- `pyraf/` — Submódulo con el fork de [iraf-community/pyraf](https://github.com/iraf-community/pyraf) en [`LAPIS-2026/pyraf`](https://github.com/LAPIS-2026/pyraf).

## Cómo clonar este repositorio (incluyendo submódulos)

```bash
git clone --recurse-submodules https://github.com/LAPIS-2026/celesteparisi.git
```

Si ya clonaste el repositorio sin `--recurse-submodules`, inicializa y descarga todos los submódulos con:

```bash
git submodule update --init --recursive
```
