# ¡Hola!

_____________________________________________________________________
🖥️ Soy estudiante de la Universidad Autónoma Benito Juárez de Oaxaca, me gusta mucho los distintos lenguajes de programación, actualmente trabajo como programador de un modo multijugador de la plataforma SAMP que lleva como base el lenguaje de C++.
_____________________________________________________________________
🧑‍💼Actualmente estoy estudiando en la Universidad Autónoma Benito Juárez de Oaxaca y en mi trabajo actual es programar a distintos clientes de distintos países en la plataforma San Andreas MultiPlayer.
_____________________________________________________________________
# Lenguajes que estoy aprendiendo
- C++
- Java Script (Actualmente  me lo encuentro aprendiendo gracias a ser autodidacta y a explicaciones de nuestro catedrático) 
[jorrge.cruz@gmail.com ]()
- Lua
- C#
#### 
_____________________________________________________________________

🎯 Mis editores en uso actualmente:
- SublimexText3D
- Visual Studio Code


## Algo de lo que hago actualmente


```c

stock OBTENER_IDT(playerid,listitem)
{
    new slot,negls = 0;
    for(new i = 0; i < 4; i++)
    {
        if(Info[playerid][Trabajo_Player][i] == 0) continue;
        if(listitem <= negls)
        {
            slot = i;
            break;
        }
        negls++;
    }
    return slot;
}
```
