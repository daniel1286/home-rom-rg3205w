# O recovery

O recovery é un pequeno sistema á parte que arrinca no canto de Home para instalar actualizacións. Home leva TWRP co seu propio deseño. Normalmente non fai falta entrar: Actualizacións úsao soa.

## Cando aparece

- **Ao actualizar**: despois de **Instalar e reiniciar**, a pantalla arrinca no recovery, instala a versión amosando como vai e volve soa a Home.
- **Se entras ti**, con [ADB](adb.md): `adb reboot recovery`.

## Que se pode facer

| Para | Toca |
| --- | --- |
| Volver a Home | **Reiniciar → Sistema** |
| Ir a fastboot, para volver instalar Home | **Reiniciar → Bootloader** |
| Apagar | **Reiniciar → Apagar** |

> [!CAUTION]
> No recovery pódese borrar todo. Se non sabes que fai unha opción, non a toques e volve a Home con **Reiniciar → Sistema**.

## Se queda no recovery

Se o recovery avisa dun erro ao instalar, toca **Reiniciar → Sistema**. Ao arrincar, Actualizacións di que pasou: tes isto en [Se unha actualización non se instala](si-no-se-instala.md). Se a pantalla xa non arrinca, [volve instalar Home](volver-a-instalar.md).
